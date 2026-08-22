# Corpus Inventory — National-Level Radio Broadcasting Scripts

**Purpose:** Master inventory of the National-level benchmark corpus used by all analyses in this directory. Future agents should consult this file first to know what exists, what was analyzed, and what was deliberately excluded.

**Source of inventory data:** `transcripts/README.md` (verified master index), the per-contestant `actual-script.md` metadata tables, and file inspection. Audio verification status is carried over from the README ("Verified" = transcription checked against the `.mp3`).

---

## 1. Workspace Layout (relevant paths)

| Path | Content | Role in this study |
|---|---|---|
| `transcripts/Contestant-1/ … Contestant-18/` | Per-team folders | The benchmark corpus (18 entries) |
| `NSPC-Samples/Contestant-1.mp3 … Contestant-18.mp3` | Original audio recordings | Ground truth; transcripts were verified against these |
| `transcripts/README.md` | Master index (windows, durations, QC status, station IDs) | Inventory metadata source |
| `ORIGINAL-SCRIPT.md` | Our own Division-level script (DZRM 67.5 "Tagahabi ng Balita") | **NOT part of the benchmark corpus.** This is the script future agents will revise using the benchmark. |
| `scratch_transcripts/` | Python tooling used to produce transcripts | Not analysis material |
| `national-script-analysis/` | This directory | All analysis outputs |

---

## 2. Corpus Summary — 18 National Entries

All entries are **NSPC (National Schools Press Conference) Radio Broadcasting & Scriptwriting** competition performances, per the metadata embedded in the `actual-script.md` files (e.g., Contestant-1 lists "Competition Event: NSPC Radio Broadcasting & Scriptwriting"; at least one script references "NSPC 2026"). All recordings run ~8 minutes total, with the official broadcast occupying roughly the last 5 minutes after a mic-check/setup phase.

| # | Broadcast Window | Broadcast Duration | Station ID / Program Title (per README) | Language | QC |
|---|---|---|---|---|---|
| 1 | 02:49–07:54 | ~05:05 | DZJV 91.26 (*NSPC Patrol*) | Filipino / Taglish | Verified |
| 2 | 03:12–07:58 | ~04:46 | DZJB 91.26 kHz (*NSPC Patrol*) | Filipino / Taglish | Verified |
| 3 | 03:03–07:43 | ~04:40 | NSPC Patrol (*Radyo Patrol*) | Filipino / Taglish | Verified (room reverb; `[unclear]` tags) |
| 4 | 03:06–08:14 | ~05:08 | DCJV 91.26 (*NSPC Patrol*) | Filipino / Taglish / Bisaya | Verified (fast delivery; slips preserved) |
| 5 | 02:57–08:01 | ~05:04 | DZJV 91.26 (*NSPC Patrol*) | Filipino / Taglish | Verified |
| 6 | 03:02–07:54 | ~04:52 | DCJV / CJV (*NSPC Patrol*) | Filipino / Taglish | Verified |
| 7 | 02:43–07:54 | ~05:11 | DZJV-9126 (*SPC / NSPC Patrol*) | Filipino / Taglish | Verified |
| 8 | 02:50–08:17 | ~05:27 | DZJV 91.26 (*NSPC Patrol Online*) | Filipino / Taglish | Verified (longest window; unison "Offline!" sign-off) |
| 9 | 02:56–07:56 | ~05:00 | PCJV 91.26 (*NSPC Patrol*) | Filipino / Taglish / Bisaya | Verified |
| 10 | 02:59–07:51 | ~04:52 | NSPC Patrol (*Ormoc City*) | Filipino / Taglish | Verified (re-transcribed, Whisper large-v3) |
| 11 | 02:54–07:55 | ~05:01 | NSPC Patrol (*Radyo Patrol*) | Filipino / Taglish / Cebuano | Verified (fast delivery) |
| 12 | 02:58–07:57 | ~04:59 | PCTV 9126 (*NSPC Patrol*) | Filipino / Taglish | Verified |
| 13 | 02:41–07:58 | ~05:17 | DZJP 91.26 (*SPC Patrol*) | Filipino / Taglish | Verified |
| 14 | 03:05–08:01 | ~04:56 | NSPC Patrol (*Ormoc City*) | Filipino / Taglish | Verified (Whisper loop fixes) |
| 15 | 02:48–07:56 | ~05:08 | DZJB 91.26 (*NSPC Patrol*) | Filipino / Taglish | Verified |
| 16 | 02:38–07:58 | ~05:20 | DCJT 91.26 (*NSPC Patrol*) | Filipino / Taglish | Verified |
| 17 | 02:52–07:51 | ~04:59 | NSPC Patrol (*Radyo Patrol*) | Filipino / Taglish / Bisaya | Verified |
| 18 | 03:01–08:06 | ~05:05 | DCJV 91.26 (*NSPC Patrol*) | Filipino / Taglish / Bisaya | Verified (Whisper loop fixes) |

**Counts:** 18 distinct teams/entries · 18 usable broadcast scripts (all complete enough for analysis) · each broadcast ~4:40–5:27 of a ~8:00 total recording.

> **Note on durations:** figures above are broadcast-window durations per README. Per-script analyses may refine them using the timestamped rundown tables inside each `actual-script.md`.

---

## 3. File Type Classification (per contestant folder)

| File | Nature | Used for |
|---|---|---|
| `actual-script.md` | **PRIMARY ANALYSIS SOURCE.** Broadcast production script: metadata tables (callsign, cast, window, language), rundown table with per-segment timestamps and audio cues, verbatim timed dialogue with SFX/stinger cues, and a content/fact sheet. | Most sections of every analysis (structure, dialogue, cues, timestamps). |
| `full-transcript.md` | Verbatim chronological transcript of the whole recording incl. mic-check phase, with timing metadata/Gantt. | Cross-checking unclear lines and detailed pacing evidence. |
| `formatted-script.md` | Cleaned production-format version of the script (uppercase dialogue, Filipino cue labels like `STINGER`, `PAGPASOK NG NEWS BED`). | **Section 20 (Script Readability)** and wording cross-check. |
| `mic-check.md` | Pre-broadcast technical setup / roll-call. | **EXCLUDED from all analyses** — not part of the official performance. Do not treat mic-check banter (e.g., Contestant-6 mock podcast, Contestant-13 letter skit, Contestant-15 food-show practice) as part of the judged broadcast. |

---

## 4. Known Competition Context

- **Level/Event:** National — NSPC (National Schools Press Conference) Radio Broadcasting & Scriptwriting. This is labeled directly in the source metadata; no external rules document exists in the workspace.
- **Year:** At least one script references "NSPC 2026" (Contestant-1). Do not infer more precision than this.
- **Program convention:** Nearly all teams use a "…Patrol" news-program frame with an invented callsign + frequency (e.g., DZJV 91.26) and a station slogan. The station IDs appear to be *creative props* (multiple teams reuse the same 91.26 pattern with different letters), not real frequencies — analysts should treat them as part of each entry's invented identity, not as real-world data.
- **Official judging criteria:** NOT present in the workspace. Analyses must not invent them; they may note this absence (Specialist M addresses observed quality vs. official criteria).
- **Content convention:** All entries deliver local news, national news, a mid-break infomercial/advocacy, sports, and showbiz within ~5 minutes — a shared NSPC radio-broadcasting format. Exact per-entry segment sets vary; document the actual sequence for each entry.

---

## 5. Limitations & Caveats

1. **Transcript fidelity:** Some entries contain `[unclear]`, `[possibly: …]`, and `*[intended text]*` annotations (notably Contestant-3, 4, 11) due to room reverb, rapid delivery, and slips of the tongue. Quote dialogue from the scripts but flag annotated/heavily-cleaned passages.
2. **Broadcast windows differ:** Entries start their official broadcast at 02:38–03:12; the mic-check window is NOT part of the performance.
3. **No official scoring data:** We do not know how these entries actually ranked. "National-level" here means the collection is from the National competition, NOT that each entry is a winner. Analyses should treat quality differences across entries as real (see weaknesses sections).
4. **No judging criteria in workspace:** Infer quality from the scripts themselves; do not cite official criteria.
5. **Some `actual-script.md` files are shorter than others** (e.g., Contestant-7, 8, 16) — they may present condensed versions of the broadcast; use `full-transcript.md` where the rundown/dialogue seems incomplete.
6. **Music/SFX details are cue labels, not recordings:** Audio analysis (e.g., exact bed styles) cannot be performed from text alone; treat music/SFX as *documented cues* only.

---

## 6. Output Map (all analysis deliverables)

| Artifact | Location | Owner |
|---|---|---|
| This inventory | `corpus-inventory.md` | Orchestrator |
| Shared analysis spec (25-section structure + evidence discipline) | `ANALYSIS-SPEC.md` | Orchestrator |
| Per-script analyses (18) | `per-script/script-01-analysis.md` … `script-18-analysis.md` | One analyst each |
| Specialist reports (13) | `specialists/*.md` | One specialist each |
| Cross-comparison reports (3) | `cross-comparison/*.md` | One agent each |
| Final benchmark | `NATIONAL-RADIO-SCRIPT-BENCHMARK.md` (workspace root) | Orchestrator |

**Source scripts are never modified.**
