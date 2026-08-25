---
description: Generate a completely original Division-level Filipino radio script into its own division-scripts/[CONCEPT]/ folder — not a reskin of the old show; AWIT placeholders only, no generated songs
---

# Generate a completely NEW Division script

You are the orchestrator for this workspace's school radio broadcasting team. The user just invoked `/generate-new-script`.

This is **not** `/generate-division-script`. That command writes a **structure** as a flat file. **This** command writes a **complete new on-air script package** in its **own subfolder**. The result must not be similar or identical to `ORIGINAL-SCRIPT.md`.

Optional user arguments (may be empty — **empty is the normal case**):
$ARGUMENTS

**Default assumption:** the user does **not** know the concept. Invent a strong original concept and ship a finished script around it. Do not ask what the concept should be. Do not present a menu and wait. Privately consider 2–3 systems, pick the strongest, execute it fully.

If arguments conflict with `AGENTS.md`, `AGENTS.md` wins unless the argument is an explicit user lock. Output location for this command:

`division-scripts/[CONCEPT]/`

---

## 0. What you are producing

A **complete new Division-level radio script** — full spoken frame, original identity, original transitions, original close — with placeholders only for competition-day news and advocacy facts.

The station stays **DZRM 67.5**. The *show* must **not** be a polish, reorder, or reskin of *Tagahabi ng Balita* / aarangkada / PEPRENO. If someone who knows the old script could recognize this as “the same program with a new metaphor,” you failed. Rewrite.

**Fully write:**

- header and cast
- a new concept system on air (open, ID, slogan, bumpers, close)
- station ID, time-check slot, greeting, KBP line, paired intros (new wording)
- headline frame + handoff (not the headline text)
- named-question tosses, thank-you receipts, sign-off formulas (new wording)
- infomercial entry bumper, re-entry, scene architecture, station tag
- sports / showbiz launches and tone-shift cues
- production cues, bed map, pacing rundown
- **AWIT as empty placeholders only** (see §4). No generated song lyrics.

**Placeholders only:**

- four headlines, national / local / sports / showbiz bodies
- infomercial scene, sourced fact, named solution, CTA, paalala body
- AWIT slots (empty placeholders — no lyrics)
- in-story SFX that belong to a specific news event
- clock numbers

Do **not** invent news facts, scores, official names, laws, or infomercial statistics. Do **not** reuse previous stories (Geronimo, KVSHS, DepEd grading, Kris Aquino). Do **not** lift the National news pool (Ormoc ATM, WPS cyanide, Middle East oil, Alcantara, Oscars 2026).

Write files. Do not only paste the script in chat. Never overwrite `ORIGINAL-SCRIPT.md`. Never modify `transcripts/`, `NSPC-Samples/`, or completed analysis reports.

---

## 1. Output folder (required)

1. Create `division-scripts/` if missing.
2. Invent (or use a locked) concept, then a short `[CONCEPT]` slug: 1–4 words, ASCII, `UPPER-CASE`, hyphens. From the program title or core metaphor, not the long slogan.
   - Good: `BATINGAW`, `ILAW`, `PULSO`
   - Forbidden: `CONCEPT`, `NEW`, `DRAFT`, `V1`, `SCRIPT`, `PATROL`, `AARANGKADA`, `TAGAHABI` (unless the user kept weaving)
3. Create a **new subfolder** for this show:

   `division-scripts/[CONCEPT]/`

   Example: *Batingaw ng Balita* → `division-scripts/BATINGAW/`

4. Write at least:

   | File | Role |
   |------|------|
   | `division-scripts/[CONCEPT]/DIVISION-SCRIPT-[CONCEPT].md` | The on-air script |
   | `division-scripts/[CONCEPT]/DIVISION-CONCEPT-[CONCEPT].md` | Concept proposal (unless a lock already exists) |

5. If `division-scripts/[CONCEPT]/` already exists, do **not** overwrite. Choose a more specific slug or `division-scripts/[CONCEPT]-2/`.
6. Never write this package as a flat `division-scripts/DIVISION-SCRIPT-*.md`. That layout is for `/generate-division-script` only. Never write at repo root. Never name a file `ORIGINAL-SCRIPT.md`.

---

## 2. Authority and evidence

Follow `AGENTS.md` §4 when documents disagree.

Keep claims separate: **Source fact** · **Benchmark observation** · **Creative inference** · **New creative proposal**.

A National habit is not a contest rule. A slogan you just wrote is not approved until locked.

Study labels: **DIRECTLY OBSERVED**, **CROSS-SCRIPT PATTERN**, **ANALYST INFERENCE**.

---

## 3. Reading order

Read with tools. Do not dump research into `AGENTS.md`. Do not re-transcribe National audio.

### Phase A — law

1. `AGENTS.md` — **first, in full.**
2. `ORIGINAL-SCRIPT.md` — read as **what this draft must not resemble** (identity, metaphor, jingle, bumpers, open/close cadence, distinctive lines). Also note house **format** (labels, ALL CAPS, cue style) to keep. Do not copy glitches.
3. `ORIGINAL-SCRIPT-PLACEHOLDER.md` — National-style **slot functions** only (open → headlines → 2 hard news → infomercial → sports → showbiz → close). Do not carry old branding, bumper words, or jingle.

### Phase B — discovery

Search and open if present:

- everything under `division-scripts/` (flat files and subfolders)
- any lock / `DIVISION-CONCEPT-*`
- Pililla / Rodriguez / Montalban / audience research
- a current fact sheet (note it; still do not fill news)

If a concept is **LOCKED / APPROVED**, use it and still write **new** wording that is not the old Tagahabi script.

Existing drafts are previous proposals, not templates. This run must also be distinct from them unless the user asked to revise one named folder.

### Phase C — quality bar

4. `NATIONAL-RADIO-SCRIPT-BENCHMARK.md` — §3–21 and §23–28 especially.

### Phase D — bounded corpus

5. `national-script-analysis/specialists/originality-and-concept.md`
6. `national-script-analysis/specialists/openings-and-branding.md`
7. `national-script-analysis/specialists/structure-and-rundown.md`
8. `national-script-analysis/specialists/transitions-and-bumpers.md`
9. `national-script-analysis/specialists/sound-design.md`
10. `national-script-analysis/cross-comparison/reusable-techniques.md` (“What Would Become Copying”)
11. `national-script-analysis/cross-comparison/recurring-patterns.md`

Further only as needed (one file per gap): anchor-dynamics, headline-techniques, infomercial-analysis, sports-and-showbiz, pacing-and-timing, language-and-delivery. C5/C8 per-script analyses for *system functions only*.

Do not treat `mic-check.md` as judged content.

---

## 4. AWIT — placeholder only, no generated song

**Never write song lyrics.** Melody is hard to source, so invented words are unusable.

Keep the three slots in the rundown as **empty placeholders** (opening after ID, infomercial break, close):

```
**AWIT:** [AWIT-THEME]

**AWIT:** [INFOMERCIAL-AWIT]

**AWIT:** [AWIT-CLOSE]
```

- Do **not** fill those lines with lyrics, chorus, or “sample” verses.
- Do **not** copy the old lyrics (`HALINA’T MAGLAKBAY…`, teacher PSA song, `HANDOG PARA SA BAYAN, HATID ANG KAMALAYAN…`) or any National jingle.
- Carry identity with spoken slogan, unison money lines, a sonic SFX logo, stingers, and category beds. The AWIT lines are holes for a track the team already has or will pick later.

Production notes: `AWIT: PLACEHOLDER ONLY (no generated lyrics)`.

---

## 5. Concept (AI-owned by default)

**Normal case:** nothing locked. You invent and commit.

Must be a **system**: language at open / transitions / close; **one** sonic logo at the edges; close answers open; paid off ≥2 times. Container, not news-body metaphor. Bookended system is enough.

**Station ID is locked:** **DZRM 67.5**. On air: `D-Z-R-M`, `SAIS-SYETE-PUNTO-SINGKO`. Header: `D-Z-R-M 67.5`. Do not invent a different callsign or frequency. **Never** `91.26`, `Patrol` / `Patroller`.

Invent a **program title** and concept around that station. Do **not** default to *Tagahabi ng Balita* unless arguments keep weaving.

**Anti-clone vs the old *show* (mandatory):**

Do not use, echo, or lightly respell:

- Program / weaving (unless the user kept it): `Tagahabi ng Balita`, `tagahabi ng kamalayan`
- Vehicle overlay: aarangkada, biyahe, jeepney, makina ng sasakyan, busina, `PEPRENO`, `MULING AARANGKADA`, `AARANGKADA NA`, travel-jingle cadence
- C5 family: travel buddy, kabiyahero, ruta, red-light break, horn-as-logo
- Distinctive old lines: `KAAGAPAY NA SUBOK SA PAGHABI…`, `TATAK NG LEHITIMONG SERBISYO…`, `I-CHIKA MO NA`, `CHISMIS NA WALANG KAPARES`, `BALITAANG PALABAN`, `MONTALBEÑOS, IYAN ANG MGA BALITANG HATID NG UMAARANGKADANG ISTASYON`
- Old opening cadence cloned beat-for-beat (engine → `ITO ANG…` → stuttered `DZ-D-D-D-Z-R-M` → unison title → horn → `AARANGKADA NA` → theme)

Keep saying **D-Z-R-M** and **SAIS-SYETE-PUNTO-SINGKO**. That is the station, not the old program.

Weaving / Tagahabi: keep **only** if arguments say so. Otherwise retire the program name and invent something else — still on DZRM 67.5.

Truth/service slogans need a hook that is ours. Local address: Montalbeños / Luzon if no newer audience file; Pililla research if it exists. Do not invent a hometown.

Fix exact slogan / program / unison form and use it everywhere. Station ID is **LOCKED**. Program / slogan / metaphor: **PROPOSAL — not locked**.

Cast default: previous role map. Tagapagbalita 3 credited, silent.

**How to choose:** 2–3 original candidates → score originality, speakability, payoff, local fit, sonic logo → ship one. Do not dump rejects into the script. One sentence in production notes is enough.

---

## 6. Quarantine — never copy National either

Benchmark §21 + `reusable-techniques.md` + per-script DO NOT COPY.

No NSPC Patrol family, no 91.26, no Patroller titles, no borrowed personas, slogans, jokes, sonic logos, or exact lines.

Safe as **functions:** ~5:00 two-act spine, headline shape, 3-sentence reports, handoff loops, category beds, boundary stingers, infomercial skeleton, closing ritual.

After writing, originality-pass against §21 **and** against `ORIGINAL-SCRIPT.md`. If anything is close, rewrite.

---

## 7. House format, new content

Page look matches `ORIGINAL-SCRIPT.md` **format only**:

- `**ANGKOR 1:**`, `**TAGAPAGBALITA 1:**`, `**LAHAT:**`, `**BUMPER:**`, `**PAALALA:**`, `**AWIT:**`
- Spoken copy ALL CAPS Filipino; English terms *italics*
- Sound as bold cue lines (`**STINGER**`, `**TUNOG NG …**`, ellipsis combos)
- Spell station ID for air as `D-Z-R-M`, `SAIS-SYETE-PUNTO-SINGKO`
- Do not copy old markdown glitches

Preamble (not a replacement page look): rundown table, bed map, `[UP AND UNDER]`, placeholder legend. Note AWIT is placeholder-only (no lyrics).

---

## 8. Architecture

Hit the National spine (benchmark observation, 18/18) — **not** the old show's texture:

```
branded open → headlines → 2 hard-news reports → tease + promise
→ one infomercial → re-entry → sports → showbiz → recap close
```

Pacing bands: first news ~55–70 s; reports ~25–35 s; advocacy ~40–50 s; sports/showbiz ~30–35 s each; close ~15–25 s; total ~5:00.

The **opening sequence may differ** from the old script (clock-first, slogan-first, sonic-logo-first, etc.) as long as identity lands in ~20 s and the concept in ~45 s.

Required craft in the written parts:

1. Sonic hook + three-layer ID: promise/slogan (new) → **`D-Z-R-M` + `SAIS-SYETE-PUNTO-SINGKO`** (locked) → program name (new, unless Tagahabi is kept).
2. Time-check slot with blank clock. At most one diegetic beep in the show.
3. Greeting + KBP line (production realism; new surrounding lines).
4. Paired intros, new role wording tied to the new concept.
5. Four headline tokens, reveal hard / tease soft, frame + handoff, alternating anchors.
6. National then local; name-question toss + thank-you; category sign-off formula (new skeleton).
7. At most one mid-report Q&A slot.
8. Tease-then-promise bumper (new pair — not PEPRENO). Infomercial: hook → scene holes → problem → `[INFOMERCIAL-FACT]` → `[INFOMERCIAL-SOLUSYON]` → `[INFOMERCIAL-CTA]` → station tag → return. No child-shaming. No National game-show clone.
9. Re-entry restates **this** identity. Sports then showbiz with bed + lexicon shift.
10. Close: recap → IDs → unison identity → callback to **this** opening → fade. Include `**AWIT:** [AWIT-CLOSE]` as an empty placeholder — no lyrics.
11. 4–5 beds; boundary stingers; duck under speech; one sonic logo; theatrical SFX in the infomercial zone; no music-only gaps.

Speakability: short declaratives, short unison lines.

---

## 9. Placeholder contract

Use these tokens verbatim. Do not invent synonyms.

| Token | Meaning | Fill rule |
|-------|---------|-----------|
| `[HEADLINE 1]` | National | Reveal `[TOPIC], [RESULT STATE]!` 8–14 words |
| `[HEADLINE 2]` | Local | Same reveal |
| `[HEADLINE 3]` | Sports | **Tease** — no score/winner |
| `[HEADLINE 4]` | Showbiz | **Tease** |
| `[NASYONAL NA BALITA]` | National body | 3 sentences; `Ayon sa…`; `umano`/`diumano` |
| `[LOKAL NA BALITA]` | Local body | Same |
| `[SPORTS NA BALITA]` | Sports body | News register + energy |
| `[SHOWBIZ NA BALITA]` | Showbiz body | Tone shift |
| `[INFOMERCIAL-SCENE]` | Scene | Dignifying; 2–4 characters |
| `[INFOMERCIAL-FACT]` | Statistic | Sourced; never invent |
| `[INFOMERCIAL-SOLUSYON]` | Named solution | Named entity |
| `[INFOMERCIAL-CTA]` | CTA | Verb + object |
| `[INFOMERCIAL-PAALALA]` | PSA line | Then written station tag |
| `[AWIT-THEME]` | Opening theme slot | Placeholder only — **no lyrics** |
| `[INFOMERCIAL-AWIT]` | Infomercial song slot | Placeholder only — **no lyrics** |
| `[AWIT-CLOSE]` | Closing reprise slot | Placeholder only — **no lyrics** |
| `[SFX-KWENTO]` | In-story SFX | Only if the day's story needs it |

Toss shape: `[HEADLINE 1]. TYRAH INARES, ANO ANG BUONG DETALYE?` then body, then thank-you.

---

## 10. Subagents

Use only for real independent depth. You still synthesize and write the files.

Useful: concept comparison (private); originality vs §21 **and** vs `ORIGINAL-SCRIPT.md`; structure critique (§26, news N/A).

Do not leave the user with three half-shows.

---

## 11. Script file shape

`division-scripts/[CONCEPT]/DIVISION-SCRIPT-[CONCEPT].md`:

1. **Production notes (not for air)** — short:
   - status: COMPLETE NEW SCRIPT (competition-day holes)
   - station ID: **LOCKED** — DZRM 67.5 (`D-Z-R-M`, `SAIS-SYETE-PUNTO-SINGKO`)
   - concept status: PROPOSAL vs LOCKED (program / slogan / metaphor only)
   - identity block (callsign, frequency, program, slogan exact form, sonic logo, audience)
   - AWIT: placeholder only (no generated lyrics) — `[AWIT-THEME]`, `[INFOMERCIAL-AWIT]`, `[AWIT-CLOSE]`
   - placeholder legend
   - bed map
   - target rundown
   - role map
   - **dissimilarity note:** what was deliberately not taken from the old script
2. **The on-air script** in house format.

`DIVISION-CONCEPT-[CONCEPT].md`: proposal — system, vocabulary, sonic logo, payoff map, slug, not-locked banner. No research essay. No National quotes.

---

## 12. Stop checklist

- [ ] `AGENTS.md` read first
- [ ] Package is `division-scripts/[CONCEPT]/` with `DIVISION-SCRIPT-[CONCEPT].md`
- [ ] Station ID is **DZRM 67.5** (`D-Z-R-M`, `SAIS-SYETE-PUNTO-SINGKO`) — not a new callsign
- [ ] Concept invented and committed (unless user named/locked one)
- [ ] Not a reskin of the old *program* (Tagahabi / aarangkada / PEPRENO / old jingle / distinctive lines) — station ID stays the original
- [ ] Not a National identity; nothing from §21
- [ ] AWIT slots present as empty placeholders only — no generated lyrics
- [ ] Placeholders consistent; no invented news
- [ ] Named-question toss + thank-you around each report
- [ ] Close answers **this** open
- [ ] House format; Tagapagbalita 3 credited, silent
- [ ] `ORIGINAL-SCRIPT.md` untouched
- [ ] Chat reply: folder path, concept in one sentence, how to fill tokens — do not reprint the whole script unless asked

Begin. Stay on track.
