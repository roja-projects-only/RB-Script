# AGENTS.md — Filipino Radio Broadcasting & Scriptwriting

This is the operating guide for AI agents working in this workspace.

Read this file first. Then open only the references the current task needs. Do not dump research findings back into this file, and do not treat National sample scripts as templates.

---

## 1. What this project is

This workspace belongs to a **school radio broadcasting and scriptwriting team**.

It holds:

- our **previous Division-level script** and a **placeholder skeleton** of that script
- **18 National-level (NSPC) sample recordings**, verified transcripts, and a completed analysis corpus
- a root **benchmark** that turns those analyses into principles for our next Division script

The team’s last on-air identity (historical, not automatically locked for the next contest):

- Station: **DZRM 67.5**
- Program: **Tagahabi ng Balita**
- Audience: **Montalbeños** (Montalban / Rodriguez), Luzon
- Concept overlay: **weaving/service** (“tagahabi ng kamalayan”) plus a **vehicle / aarangkada** frame (engine, horn, travel jingle, “pepreno” break)
- Cast as written: Rain Calites & Celine Asoy (anchors); Tyrah Inares & Carl Adlawan (reporters); Khassy Rada listed as Tagapagbalita 3 but unused on air; Rodger Pacumba Jr. (technical / writer); Gwyneth Ashley Damasen (director)

---

## 2. Current goal and phase

**Research is done. Creative and script-development work is the current purpose of the workspace.**

We are preparing a **new Division-level** radio broadcast script and concept.

That means:

- raise our quality target using the National benchmark
- keep what is genuinely strong about how *this team* writes and performs
- **do not** merely polish or reskin the previous script
- **do not** copy National station identities, slogans, jokes, or signature devices
- the new script does **not** yet exist — do not invent it until asked

Older analysis files still talk about “revising `ORIGINAL-SCRIPT.md`.” That was true during the study phase. **This file supersedes that workflow.** The previous script is historical context. The next deliverable is a **new** Division script, informed by the old one, not a silent overwrite of it.

---

## 3. What is already done vs what is not

### Done

- 18 National audio samples in `NSPC-Samples/`
- Verified transcripts in `transcripts/`
- Shared analysis spec, corpus inventory, 18 per-script analyses, 13 specialist reports, 3 cross-comparison reports
- Root synthesis: `NATIONAL-RADIO-SCRIPT-BENCHMARK.md` (v1.0, 2026-08-22)
- Previous filled script: `ORIGINAL-SCRIPT.md`
- Rundown skeleton of that script: `ORIGINAL-SCRIPT-PLACEHOLDER.md`

### Not done — do not assume these exist

- No approved **concept lock** file (the benchmark’s “approved concept reference” was never created)
- No **new Division script** yet (structures: `division-scripts/DIVISION-SCRIPT-[CONCEPT].md`; complete new packages: `division-scripts/[CONCEPT]/`)
- No current-competition **fact sheet**
- No root README / CLAUDE.md
- No official NSPC rubric, results, or rankings in this repo
- Specialist M’s quality ranking (C16 > C10 > C1 > C5 …) is **analyst judgment**, not an official result

Until a concept is explicitly approved, treat station identity, slogan, jingle, and metaphor as **proposals or historical material**, not locked brand.

---

## 4. Source authority

When documents disagree, use this order:

| Rank | What | Answers |
|------|------|---------|
| 1 | **This file (`AGENTS.md`)** plus the **user’s current request** | What we are doing now; which files may be edited; original vs new script |
| 2 | **`NATIONAL-RADIO-SCRIPT-BENCHMARK.md`** | Quality bar, architecture, techniques, “do not copy,” evaluation checklist. **Not** our identity. **Not** a fill-in template. |
| 3 | **`national-script-analysis/cross-comparison/`** | What is near-universal vs optional vs team-specific; how to apply a technique without copying |
| 4 | **`national-script-analysis/specialists/`** | Depth on one craft axis |
| 5 | **`national-script-analysis/per-script/script-NN-analysis.md`** | One National entry as an exemplar, including that file’s KEEP / ADAPT / DO NOT COPY |
| 6 | **`transcripts/Contestant-N/actual-script.md`** | Primary evidence for a National entry |
| 7 | **`full-transcript.md`** then **`formatted-script.md`** | Timing / unclear lines; then readability / intended wording |
| 8 | **`NSPC-Samples/*.mp3`** | Audio ground truth. Re-open only if a transcript is disputed or the question is actually about sound, not script. |
| 9 | **`ORIGINAL-SCRIPT.md`** | How *we* wrote and formatted last time; previous concept, cast, and local voice |
| 10 | **`ORIGINAL-SCRIPT-PLACEHOLDER.md`** | Slot map for competition-dependent content under the *previous* rundown |

**Conflict rules**

- Workflow / “what file do I edit?” → this `AGENTS.md` and the user, not `corpus-inventory.md`.
- National technique / quality / originality quarantine → the benchmark, then specialists/cross-comparison.
- “Did contestant N actually say X?” → `actual-script.md`, then `full-transcript.md`. Analyses are derived.
- Our previous lines, jingle, callsign, or local address → `ORIGINAL-SCRIPT.md`, not National files.
- A new slogan, station name, or metaphor an agent just wrote → a **proposal**, not a workspace fact.

**National transcript precedence** (from `ANALYSIS-SPEC.md` / `corpus-inventory.md`):

1. `actual-script.md` — primary
2. `full-transcript.md` — timing and unclear lines; skip leaked mic-check content
3. `formatted-script.md` — production formatting / intended text, not the performance of record
4. `mic-check.md` — **never treat as judged content** (practice skits, roll-call, mock shows)

If `actual-script.md` looks condensed (known for Contestants 7, 8, 16), check `full-transcript.md`. Contestant 8’s infomercial is a placeholder note; Contestant 12’s is largely unintelligible — do not invent those segments.

---

## 5. The two original-script files

These are **not** the same file and **not** interchangeable.

### `ORIGINAL-SCRIPT.md` — historical filled script

The actual previous-competition script. Use it for:

- historical context
- our house **formatting**
- previous concept, branding, jingle, bumpers, close
- how this team assigns roles and writes Filipino for air
- production-cue style

**Do not overwrite it** unless the user explicitly asks. Fork new drafts into new files.

### `ORIGINAL-SCRIPT-PLACEHOLDER.md` — previous rundown with content holes

A working skeleton of **the same script and the same concept**. It does **not** introduce a new identity.

**Kept (previous branding + architecture):**

- header and cast
- vehicle opening, callsign build, unison “TAGAHABI NG BALITA,” “AARANGKADA NA,” theme song
- blanked time check (`___ MINUTO MAKALIPAS ANG ___ NG HAPON`)
- Luzon / Ilokano greeting, KBP line, anchor intros
- headline / news / sports / showbiz **slot structure** and reporter ownership
- break bumpers (`PEPRENO MUNA` / `MULING AARANGKADA`)
- close to Montalbeños + horn + split ID + closing song fragment
- reporter handoff and sign-off formulas

**Hollowed out (competition-dependent):**

| Slot | Placeholder token | Previous fill (for context only) |
|------|-------------------|----------------------------------|
| Headline 1 → national toss | `[PLACEHOLDER HEADLINE 1]` | Zero-based grading |
| Headline 2 → local toss | `[PLACEHOLDER HEADLINE 2]` | Geronimo school security |
| Headline 3 → sports toss | `[PLACEHOLDER HEADLINE 3]` | KVSHS municipal meet |
| Headline 4 → showbiz toss | `[PLACEHOLDER HEADLINE 4]` | Kris Aquino / Netflix |
| National body | `[NASYONAL NA BALITA]` | DepEd grading report (Tyrah) |
| Local body | `[LOKAL NA BALITA]` | School security (Carl) |
| Infomercial scene | `[INFOMERCIAL]` | Teacher-as-second-parent skit |
| Infomercial song | empty `AWIT:` | Teacher jingle |
| PSA tag | `[PLACEHOLDER]` inside `PAALALA:` | “Ating mga guro ay pahalagahan…” |
| Sports body | `[SPORTS NA BALITA]` | Volleyball scoreline (Carl) |
| Showbiz body | `[SHOWBIZ NA BALITA]` | Kris Aquino (Tyrah) |

In-story SFX that belonged to those stories (school bell, door, whistle, notification) were removed with the bodies. The infomercial is collapsed (the filled script had four characters).

**How to use it**

- **Content-only refresh under the old rundown:** copy this file (or a new draft forked from it); fill the tokens; keep structure. Do not fill the skeleton in-place if that would destroy the slot map — copy first.
- **New concept / new Division script:** use it as a **slot map** (open → headlines → 2 hard news → infomercial → sports → showbiz → close). Do **not** carry DZRM / Tagahabi / aarangkada / jingle / bumpers forward unless the user keeps them.
- Never fill slots from the National shared news pool (Ormoc ATM scam, WPS cyanide, Middle East oil, Alcantara, Oscars 2026). That pool is competition-prompt material from another event.

---

## 6. Workspace map

| Path | Role | Edit? |
|------|------|-------|
| `AGENTS.md` | This operating guide | Only to keep it true as the project evolves |
| `ORIGINAL-SCRIPT.md` | Historical filled script | **Preserve** |
| `ORIGINAL-SCRIPT-PLACEHOLDER.md` | Previous-concept skeleton | Mutable working file; copy before filling if you need to keep a clean slot map |
| `NATIONAL-RADIO-SCRIPT-BENCHMARK.md` | Agent-facing National → Division standard | Preserve unless asked to update the study |
| `national-script-analysis/ANALYSIS-SPEC.md` | How the National study was run; evidence labels | Preserve |
| `national-script-analysis/corpus-inventory.md` | Corpus layout and exclusions. **Inventory’s “revise ORIGINAL-SCRIPT.md” line is outdated.** | Preserve |
| `national-script-analysis/per-script/` | 18 entry analyses | Preserve |
| `national-script-analysis/specialists/` | 13 craft reports (A–M) | Preserve |
| `national-script-analysis/cross-comparison/` | Patterns, differences, reusable techniques | Preserve |
| `transcripts/` | Verified National transcripts | **Never modify** |
| `transcripts/README.md` | Master index (windows, QC, competitor IDs). Tree omits `formatted-script.md`, but every folder has one. | Preserve |
| `NSPC-Samples/` | Original `.mp3` recordings | **Never modify** |
| `scratch_transcripts/` | Gitignored Whisper dumps and one-off Python | Tooling only; not evidence if `transcripts/` disagrees |
| `division-scripts/` | New Division drafts and concept proposals | **Intended.** Create files here; never at repo root |
| `.agents/skills/` | Generic installed skills (research, transcription, planning) | Not radio-script canon |
| `.opencode/commands/` | Project OpenCode slash commands | Edit when the workflow changes |

**OpenCode commands (project):**

| Command | Writes | What it is |
|---------|--------|------------|
| `/generate-division-script` | `division-scripts/DIVISION-SCRIPT-[CONCEPT].md` (flat) | Competition-ready **structure** / skeleton |
| `/generate-new-script` | `division-scripts/[CONCEPT]/` (own subfolder) | **Completely new** on-air script package that must not resemble `ORIGINAL-SCRIPT.md` |

There is no `concept/`, `docs/`, `research/`, or `graphify-out/` directory. Concept research for *National teams* lives in `national-script-analysis/specialists/originality-and-concept.md` and benchmark §19. Our concept proposals live under `division-scripts/` (flat `DIVISION-CONCEPT-[CONCEPT].md` or `division-scripts/[CONCEPT]/DIVISION-CONCEPT-[CONCEPT].md`). Until marked **LOCKED** / **APPROVED**, they are proposals.

---

## 7. National materials are benchmarks, not templates

Study **how** strong entries work. Do not become them.

Safe to learn (functions and structures):

- ~5:00 two-act spine: branded open → 2–3 hard news → tease + promise → one infomercial → re-entry → sports/showbiz → recap close
- pacing bands, headline shape, report compression, handoff loops, sign-off discipline
- category beds, boundary stingers, beds under speech
- scripted anchor chemistry, branding consistency, speakable Filipino
- infomercial skeleton, sports/showbiz tone shift, closing ritual

Never copy:

- station identities, callsigns, frequencies (especially the **91.26 / “NSPC Patrol”** family), program titles, “Patroller” titles
- slogans, jingles, distinctive jokes, unique metaphors, signature transitions
- personas (Travel Buddy, kabiyahero, Yas Queen, Chika-Dora, Mamshie Kirby, Kuya Will, etc.)
- exact lines, sign-offs, bumper wording, PSA lines
- competitor sonic logos (C4 sweep, C5 horn as *their* logo, C8 “Offline!”, C15 theme)

The quarantine list is in **`NATIONAL-RADIO-SCRIPT-BENCHMARK.md` §21**. Cross-check `cross-comparison/reusable-techniques.md` (“What Would Become Copying”) and the per-script **DO NOT COPY** sections when adapting an exemplar.

A pattern seen in several National scripts is a **benchmark observation**, not a contest rule. No official judging criteria exist here.

### Travel-concept collision (important)

National **Contestant 5** built a complete **travel / road-trip** system (travel buddy, kabiyahero, ruta, red-light break, car horn). That system is quarantined.

Our previous script independently used a **vehicle / aarangkada / biyahe** overlay plus a **weaving** brand. That is *our* last identity, not a copy of C5 — but it is the **same metaphor family**.

For the new Division cycle:

- do **not** import C5 vocabulary or their horn-as-logo treatment
- do **not** assume we must keep aarangkada / horn / travel jingle
- weaving (*Tagahabi*) is a separate, original-to-us brand thread; keep or retire it only with the user
- a new concept is allowed and expected

---

## 8. Concept development

There is **no locked concept file**. Generate, compare, and revise freely when asked. Label new names and slogans as proposals.

**Before proposing a concept, read:**

1. `ORIGINAL-SCRIPT.md` — what we already own (so we do not accidentally discard a strong original thread, or accidentally keep a weak one)
2. `national-script-analysis/specialists/originality-and-concept.md` — complete system vs intro gimmick
3. `NATIONAL-RADIO-SCRIPT-BENCHMARK.md` §5, §19, §21, §23
4. `national-script-analysis/specialists/openings-and-branding.md` — first 20–30 seconds and ID architecture

**Informed constraints (not a creativity kill-switch):**

- A concept is a **system**: language for the frame (open / transitions / close), one sound at the edges, closing answers opening, paid off at least twice. A one-off slogan is a broken promise.
- Concept is a **container**, not the news body. Hard-news prose stays plain.
- Complete load-bearing metaphors are rare even at National (2/18). A simpler bookended system is a valid Division target.
- Invented callsign + frequency + program title is the genre. **Never reuse 91.26 or “Patrol.”** Our 67.5 / Tagahabi is distinct; replacing it is a creative choice, not a requirement.
- Truth/service slogans are the genre default — they do not differentiate unless they have a hook that is *ours*.
- Local anchoring (Montalbeños, Luzon greeting) is a strength of the previous script if the next contest is still local to that audience.
- Fix the exact form of any slogan before it goes into a script (variant drift kills brands).

When a concept is approved, **create a dedicated concept file** (mark it **LOCKED**) rather than hiding the lock only inside a script: `division-scripts/DIVISION-CONCEPT-[CONCEPT].md` or, for a package from `/generate-new-script`, `division-scripts/[CONCEPT]/DIVISION-CONCEPT-[CONCEPT].md`. The benchmark assumes that file exists; it does not yet.

The user usually does **not** arrive with a concept. Inventing one is expected when they run `/generate-division-script` or `/generate-new-script`. Label it a proposal until they lock it. Do not stall and ask them to pick.

---

## 9. New script development

The new Division script should be **informed by** the old script and the National study. It does not need to preserve every old line, gimmick, metaphor, or transition.

Preserve only what is still strong and still ours, for example:

- house formatting and spoken-Filipino habits, if they remain readable
- cast and role map, unless the user changes them
- local voice (Montalbeños) if still relevant
- production realism we already do well (KBP line, time-check slot, ensemble ID)

Improve from the benchmark, for example:

- cleaner headlines (reveal hard news, tease soft news — the old script reveals sports/showbiz outcomes)
- named-question tosses and thank-you receipts (mostly absent last time)
- 3-sentence attributed reports, speakable lines, fact hygiene
- infomercial with sourced fact + named solution + verb+object CTA
- the previous teacher PSA includes a **child-shaming beat**; National analysis flags that as a taste risk — do not treat it as a virtue to keep
- self-describing sound cues; beds that duck under speech
- a closing that answers the *new* opening

**Do not write the new script, choose the final concept, or fill news slots unless the user asks.** Running `/generate-division-script` *is* an ask for a **structure**. Running `/generate-new-script` *is* an ask for a **completely new script package** that must not be similar or identical to `ORIGINAL-SCRIPT.md`. Casual chat still does not invent a script unprompted.

New Division work lives in **`division-scripts/`**, never at repo root:

- **Structure (flat):** `division-scripts/DIVISION-SCRIPT-[CONCEPT].md` plus optional `DIVISION-CONCEPT-[CONCEPT].md`
- **New script package (subfolder):** `division-scripts/[CONCEPT]/DIVISION-SCRIPT-[CONCEPT].md` and `division-scripts/[CONCEPT]/DIVISION-CONCEPT-[CONCEPT].md`
- `[CONCEPT]` is a short slug from the program title or metaphor, e.g. `BATINGAW`
- later pass: `-2` suffix on the file, or `[CONCEPT]-2/` for a package
- a short **fact sheet** beside any filled news/infomercial, in the same folder as that draft

Never name a new draft `ORIGINAL-SCRIPT.md`. Never dump a `/generate-new-script` package as a flat root-level `DIVISION-SCRIPT.md`.

**AWIT is optional in every generated draft.** Opening theme, infomercial jingle, and closing reprise may each be written, left as a placeholder (`[AWIT-THEME]`, `[INFOMERCIAL-AWIT]`, `[AWIT-CLOSE]`), or omitted — whichever **fits the concept**. Do not copy the old Tagahabi songs. Do not force a jingle onto a non-musical identity, and do not always leave the slots empty.

---

## 10. Task routing

Read the left column’s files **before** generating. Use the right column for depth.

Unless a path starts with `transcripts/` or is a root file, `specialists/`, `per-script/`, and `cross-comparison/` live under `national-script-analysis/`. “Benchmark §N” means `NATIONAL-RADIO-SCRIPT-BENCHMARK.md`.

| Task | Read first | Also consult |
|------|------------|--------------|
| Develop / compare / revise a **concept** | `ORIGINAL-SCRIPT.md`; `specialists/originality-and-concept.md`; benchmark §19, §21 | `specialists/openings-and-branding.md`; `cross-comparison/recurring-patterns.md`; `per-script/script-05-analysis.md` and `script-08-analysis.md` for *system* principles only |
| Rewrite the **opening** / station ID / jingle | Previous opening in `ORIGINAL-SCRIPT.md`; benchmark §4–5; `specialists/openings-and-branding.md` | `specialists/sound-design.md`; originality report |
| Improve **headlines** | Benchmark §7; `specialists/headline-techniques.md` | `cross-comparison/reusable-techniques.md`; current news fact sheet if one exists |
| Replace **news** stories | Slot map in `ORIGINAL-SCRIPT-PLACEHOLDER.md`; benchmark §8–10; `specialists/news-writing.md` | Verify facts externally; never lift the National news pool |
| Revise **infomercial** | Benchmark §13; `specialists/infomercial-analysis.md`; previous PSA in `ORIGINAL-SCRIPT.md` | Taste risks in that specialist file; do not copy C1/C18 game-show frames |
| Improve **anchor chemistry** | Benchmark §6; `specialists/anchor-dynamics.md` | Our paired intros in `ORIGINAL-SCRIPT.md`; `per-script/script-16-analysis.md` as a clean exemplar |
| Improve **transitions / bumpers** | Benchmark §11; `specialists/transitions-and-bumpers.md` | Our `PEPRENO` / `MULING AARANGKADA` pair (previous-concept only) |
| Improve **sound design** | Benchmark §12; `specialists/sound-design.md` | House cue style in `ORIGINAL-SCRIPT.md`; `formatted-script.md` only for cue-language comparison |
| Sports / showbiz | Benchmark §14–15; `specialists/sports-and-showbiz.md` | Previous sign-off formulas in our script |
| Pacing / runtime | Benchmark §18; `specialists/pacing-and-timing.md` | Rundown tables inside National `actual-script.md` files |
| Language / speakability | Benchmark §17; `specialists/language-and-delivery.md` | `specialists/competition-quality.md` (delivery as the widest quality gap) |
| Full **new Division script** | This file; `ORIGINAL-SCRIPT.md` (format + **what not to clone**); placeholder slot map as functions only; **approved concept if it exists**; whole benchmark especially §3, §20–28 | Specialists for each weak dimension; `cross-comparison/differences-between-teams.md`; write a package under `division-scripts/[CONCEPT]/` via `/generate-new-script` |
| Score / critique a draft | Benchmark §25–27 | Matching specialist for each low score |
| “Did we copy someone?” | Benchmark §21; `reusable-techniques.md` copying notes | That contestant’s per-script **DO NOT COPY**; `originality-and-concept.md` |
| Quote a National line | `transcripts/Contestant-N/actual-script.md` | `full-transcript.md` if unclear |

**Exemplars (principles only):** C16 and C10 for clean delivery; C1 for a complete production package / fact sheet; C5 and C8 for *what a complete concept system does*, never for their identities.

---

## 11. Evidence vs creative decisions

Keep these separate in analysis and in proposals:

| Kind | Meaning |
|------|---------|
| **Source fact** | In our script, a transcript, or verified external news |
| **Benchmark observation** | Seen across National entries, with counts when the analyses give them |
| **Creative inference** | Why something works — always labeled. Includes Specialist M’s ranking. |
| **New creative proposal** | Something invented for *our* next script |

Do not present a proposal as if it were already approved. Do not present a National habit as an official rule.

Reuse the study’s labels when analyzing: **DIRECTLY OBSERVED**, **CROSS-SCRIPT PATTERN**, **ANALYST INFERENCE**.

---

## 12. Editing safety

**Do not modify**

- `ORIGINAL-SCRIPT.md` (unless the user explicitly says to)
- anything under `transcripts/`
- anything under `NSPC-Samples/`
- completed analysis reports, unless the user asks to update the study

**Safe / intended to edit**

- new draft files you create under `division-scripts/`
- `ORIGINAL-SCRIPT-PLACEHOLDER.md` when the task is a content swap under the old skeleton (copy first if the empty map must be kept)
- this `AGENTS.md` when the workspace’s real state changes
- `.opencode/commands/` when the generate-script workflow changes

**Hygiene**

- Put generated analyses in a new dated folder; do not mix them into `transcripts/` or `NSPC-Samples/`
- `scratch_transcripts/` is gitignored working debris
- Keep a clean original, a placeholder slot map, and named drafts as three different things
- New Division structures go in `division-scripts/DIVISION-SCRIPT-[CONCEPT].md`; complete new scripts go in `division-scripts/[CONCEPT]/`; never the repo root
- If you must change identity, do it in a new draft + concept file in that folder, not by silently rewriting history

---

## 13. Format and production style

Our house script format is in `ORIGINAL-SCRIPT.md` (and is close to National `formatted-script.md` files). Match it for new drafts unless the user asks for a timestamped production rundown.

Conventions to preserve:

- Bold, all-caps speaker labels: `**ANGKOR 1:**`, `**TAGAPAGBALITA 1:**`, `**LAHAT:**`, `**BUMPER:**`, `**PAALALA:**`, `**AWIT:**`
- Spoken copy in **ALL CAPS** Filipino
- English or technical terms in *italics* when they sit inside Filipino lines
- Sound and music as their own bold cue lines: `**STINGER**`, `**TUNOG NG …**`, `**PAGPASOK NG MUSIKA…**`, combined cues with ellipsis (`**STINGER… PAGPALIT NG MUSIKA…**`)
- Station ID spelled for air (`D-Z-R-M`, `SAIS-SYETE-PUNTO-SINGKO`) when that identity is still in use
- `**AWIT:**` is a legal cue, not a required slot. Opening theme, infomercial jingle, and close reprise: write original lyrics if they fit, else placeholder or omit. Never reuse the previous jingles.

National `actual-script.md` files add timestamps, rundown tables, and `[UP AND UNDER]` / `[SFX: …]` brackets. Those are useful **production ideas** (especially ducking beds under speech and a timestamped rundown). They are not our default page look.

The previous script has a few markdown glitches (broken emphasis on Tagapagbalita 3 / Technical; extra space in one `ANGKOR 2` label). Do not copy the glitches.

**Cast note:** Tagapagbalita 3 (Khassy Rada) is credited and never speaks. Do not write her in or drop her without asking.

---

## 14. Factual / current news

Headlines, local/national reports, sports, showbiz, and infomercial issues **will change** between contests. Do not freeze this guide to the previous stories.

When filling news:

- verify facts; do not invent numbers, names, laws, scores, or quotes
- keep one internally consistent fact sheet (the National corpus contradicts itself on shared facts — that is a warning)
- attribute (`Ayon sa…`); hedge allegations (`umano` / `diumano`)
- infomercial statistics need a source and a named call to action
- previous local stories (Geronimo, KVSHS, DepEd grading, Kris Aquino) are **old content**, not a required topic list

---

## 15. Subagents

This workspace was built with parallel specialist analysis under `ANALYSIS-SPEC.md`. Use subagents when independent depth actually helps:

- concept comparison
- script critique against the §26 checklist
- headline, pacing, sound, or infomercial review
- National-benchmark comparison on one dimension
- fact-checking a news block
- alternative openings
- consistency pass (names, slogans, tease promises, sign-offs)

Do **not** spawn subagents for small line edits.

The orchestrator (you) still:

- understands the user’s actual request
- chooses what to read
- resolves conflicts
- synthesizes
- makes the final file edits

One specialist file per question is usually enough; do not re-run the entire 18-script study.

---

## 16. Known gaps and ambiguities

Future agents should not paper over these:

1. **No approved concept.** Propose; do not lock identity unless the user does.
2. **Inventory vs this file.** `corpus-inventory.md` still calls `ORIGINAL-SCRIPT.md` “the script future agents will revise.” Wrong now. Fork a new Division draft.
3. **Benchmark §25 “Preserve” rules** apply to an *approved* draft (facts, roles, locked branding). They do **not** forbid a new concept or a new script. During concept work, those preserve rules are on hold for identity. They come back once the user locks a concept and a draft.
4. **Travel overlap with C5** — see §7. Do not treat the old horn/aarangkada system as automatically safe or automatically banned; it is a decision.
5. **No fact sheet** for the next contest’s news pool.
6. **No official rules packet** in the repo. Do not invent judging criteria.
7. **Thank-you receipts, Q&A loops, UP AND UNDER** are National high-ROI techniques missing from our last script — apply them in *new* writing, not by rewriting history.
8. **`.agents/skills`** are generic tools. They do not override this file for radio work.
9. **AWIT is optional.** Include a song when it fits the concept; otherwise placeholder or omit. Not every draft needs the old three-song shape.

---

## 17. Default working order

For almost any non-trivial request:

1. Read the user’s ask. If it is a tiny edit, do that — do not tour the corpus.
2. If it touches identity, concept, or a full script: read §5–9 here, then `ORIGINAL-SCRIPT.md`.
3. If it needs a quality bar: `NATIONAL-RADIO-SCRIPT-BENCHMARK.md` (especially §20–28).
4. Drill into **one** specialist or one exemplar, not all 18 analyses.
5. Distinguish historical material, benchmark principle, and new proposal.
6. Write new work in **`division-scripts/`** — flat `DIVISION-SCRIPT-[CONCEPT].md` for a structure, or `division-scripts/[CONCEPT]/` for a complete new script package — unless the user named a working file.
7. Leave `ORIGINAL-SCRIPT.md`, transcripts, audio, and the analysis corpus intact.
