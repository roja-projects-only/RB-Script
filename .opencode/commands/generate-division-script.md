---
description: Generate a new Division-level Filipino radio script STRUCTURE into division-scripts/DIVISION-SCRIPT-[CONCEPT].md — AI invents the concept unless the user already locked one
---

# Generate a Division-level radio script STRUCTURE

You are the orchestrator for this workspace's school radio broadcasting team. The user just invoked `/generate-division-script`.

This command writes a **structure / skeleton** as a flat file under `division-scripts/`. For a **completely new on-air script package** in its own subfolder (must not resemble the old show), the user should run `/generate-new-script` instead. If they invoked this command, produce the structure.

Optional user arguments (may be empty — **empty is the normal case**):
$ARGUMENTS

**Default assumption:** the user does **not** know the concept and is not going to pick one. They expect **you** to invent a strong, original concept system and ship a polished structure around it. Do not ask them what the concept should be. Do not present a menu of options and wait. Privately consider 2–3 original systems, pick the strongest, and execute it fully.

If arguments are present, treat them as optional overrides (audience, cast, "keep weaving", a named concept, an output path). If they conflict with `AGENTS.md`, `AGENTS.md` wins unless the argument is an explicit user lock. This command's output location (`division-scripts/DIVISION-SCRIPT-[CONCEPT].md`) is the current workspace convention and is also recorded in `AGENTS.md`.

---

## 0. What you are producing (read this twice)

Produce a **competition-ready STRUCTURE / skeleton**, not a fully filled news script.

**Fully write and polish (fixed parts):**

- header and cast
- concept system as used on air (opening language, ID build, slogan, unison money lines, bumper pair, close that answers the open)
- station ID, time-check slot, greeting, KBP line, paired anchor intros
- headline **frame and handoff lines** (not the headline text)
- reporter toss loops (named-question toss + thank-you receipt) and sign-off **formulas**
- infomercial **entry bumper, re-entry, character/SFX architecture, station tag**
- sports / showbiz **category launches, tosses, tone-shift cues, sign-off formulas**
- production cues, bed map, self-describing SFX language
- pacing architecture (target rundown)
- **AWIT as empty placeholders only** (see §7b). No generated song lyrics. Identity via spoken slogan, unison, stingers, and beds.

**Leave as clear, consistent placeholders (competition-day content):**

- four headlines
- national news body
- local news body
- sports body
- showbiz body
- infomercial scene, sourced fact, solution, CTA, and PSA/paalala body
- AWIT slots (empty placeholders — no lyrics)
- any in-story SFX that would belong to a specific news event
- clock numbers in the time check

Do **not** invent news facts, scores, names of officials, laws, or infomercial statistics. Do **not** reuse previous stories (Geronimo security, KVSHS volleyball, DepEd zero-based grading, Kris Aquino / Netflix). Do **not** lift the National shared news pool (Ormoc ATM scam, WPS cyanide, Middle East oil, Alcantara, Oscars 2026).

Do **not** generate this script in chat as the only deliverable. **Write a new file under `division-scripts/`.** Never write new Division drafts at the repo root. Never overwrite `ORIGINAL-SCRIPT.md`. Never modify `transcripts/`, `NSPC-Samples/`, or completed analysis reports.

**Output path (required):**

1. Create `division-scripts/` if it does not exist.
2. Invent (or use the locked) concept first, then derive a short `[CONCEPT]` slug (see §3 / §9).
3. Write:

   `division-scripts/DIVISION-SCRIPT-[CONCEPT].md`

   Example: program *Batingaw ng Balita* → `division-scripts/DIVISION-SCRIPT-BATINGAW.md`

4. Do **not** name it `DIVISION-SCRIPT.md`, `DIVISION-SCRIPT-v2.md`, `DIVISION-SCRIPT-CONCEPT.md`, or `DIVISION-SCRIPT-NEW.md`.

---

## 1. Authority and evidence labels

When documents disagree, follow `AGENTS.md` §4.

Keep these kinds of claim **separate** in your own reasoning and in any concept/production notes you write:

| Kind | Meaning |
|------|---------|
| **Source fact** | In our previous script, a transcript, or a lock file |
| **Benchmark observation** | Seen across National entries (use counts when the analyses give them) |
| **Creative inference** | Why something works — always labeled. Includes Specialist M's ranking. |
| **New creative proposal** | Something you invent for *our* next script |

A National habit is **not** a contest rule. A slogan you just wrote is **not** an approved brand unless a lock file or the user says so.

Reuse study labels when citing the corpus: **DIRECTLY OBSERVED**, **CROSS-SCRIPT PATTERN**, **ANALYST INFERENCE**.

---

## 2. Mandatory reading order (do not skip)

Read with tools. Do not dump research back into `AGENTS.md`. Do not re-analyze all 18 National audio files.

### Phase A — law of the workspace (always)

1. `AGENTS.md` — **read first, in full.** Highest authority.
2. `ORIGINAL-SCRIPT.md` — house format, production-cue style, previous concept, cast, spoken-Filipino habits. Historical only; do not reskin it.
3. `ORIGINAL-SCRIPT-PLACEHOLDER.md` — slot map and placeholder philosophy. Use as a **slot map**, not as identity to copy forward.

### Phase B — discovery (always, before writing)

Search the workspace for, and open if they exist:

- anything under `division-scripts/` (`DIVISION-SCRIPT-*.md`, `DIVISION-CONCEPT-*.md`)
- a root `DIVISION-CONCEPT.md` or any file that explicitly **locks / approves** station identity
- any **Pililla / local-audience / concept-research** files (filenames or headings containing Pililla, Rodriguez, Montalban, concept, identity)
- any current-competition **fact sheet** (do not fill news from it in this command — this command still outputs placeholders; note the sheet's existence in production notes only)

If a lock file exists, **use it** (slug the filename from the locked program title / metaphor). Do not invent a competing identity.

Existing drafts in `division-scripts/` are previous proposals, not locks, unless a file says **LOCKED** / **APPROVED**. Do not overwrite them. A new run with a new concept gets a new `[CONCEPT]` slug. A collision on the same slug becomes `DIVISION-SCRIPT-[CONCEPT]-2.md`.

### Phase C — quality bar (always)

4. `NATIONAL-RADIO-SCRIPT-BENCHMARK.md` — especially §3 (architecture), §4–6 (open / brand / anchors), §7–11 (headlines, news, handoffs, sign-offs, transitions), §12–16 (sound, infomercial, sports, showbiz, close), §17–19 (language, pacing, concept), §20–21 (adopt vs quarantine), §23–28 (Division target, agent rules, checklist).

### Phase D — intelligent corpus drill (required, bounded)

Read these, not the whole 18-script pile:

5. `national-script-analysis/specialists/originality-and-concept.md`
6. `national-script-analysis/specialists/openings-and-branding.md`
7. `national-script-analysis/specialists/structure-and-rundown.md`
8. `national-script-analysis/specialists/transitions-and-bumpers.md`
9. `national-script-analysis/specialists/sound-design.md`
10. `national-script-analysis/cross-comparison/reusable-techniques.md` — especially “What Would Become Copying”
11. `national-script-analysis/cross-comparison/recurring-patterns.md`

Drill further **only as needed** (one specialist or one exemplar per gap):

| If you are designing… | Also read |
|-----------------------|-----------|
| Anchor chemistry / toss loops | `specialists/anchor-dynamics.md`; `per-script/script-16-analysis.md` (principles only) |
| Headline placeholder shape | `specialists/headline-techniques.md` |
| Infomercial skeleton | `specialists/infomercial-analysis.md` (taste risks; no child-shaming; do not copy C1/C18 game-show frames) |
| Sports / showbiz tone shift | `specialists/sports-and-showbiz.md` |
| Pacing numbers | `specialists/pacing-and-timing.md` |
| Speakability | `specialists/language-and-delivery.md` |
| Concept *system* principles | `per-script/script-05-analysis.md` and `script-08-analysis.md` — **functions only, never identity** |

Open National `transcripts/` **only** to verify a disputed line or a DO NOT COPY item. Never treat `mic-check.md` as judged content. Prefer `actual-script.md` over `full-transcript.md` over `formatted-script.md`.

**Exemplars are principles only:** C16 and C10 for clean delivery; C1 for a complete production package; C5 and C8 for *what a complete concept system does*. Never become them.

---

## 3. Concept (AI-owned by default)

**Normal case:** nothing is locked and the user did not name a concept. You own the creative decision. Invent one good system and build the whole structure on it. Quality is the point of this command — a vague, generic, or reskinned identity is a failed run.

### If a concept is locked (file or explicit user arguments)

Use the exact approved program title, slogan, sonic logo, metaphor vocabulary, and sign-off forms. No variant drift. Callsign + frequency stay **DZRM 67.5** even if the lock is only about concept. Do not revive Tagahabi / aarangkada unless the lock or arguments say so. Slug the output filename from the program / metaphor, not from DZRM.

### If no concept is locked (the usual run)

Do **not** stall. Do **not** interview the user. Commit to one original concept and write it fully.

**What “good” means here:**

- A **system**, not an intro gimmick: language for open / transitions / close; **one** sound at the edges; closing **answers** opening; paid off at least twice. A one-off slogan is a broken promise.
- Distinctive enough that a judge remembers the station after 5 minutes — not a generic truth/service sticker.
- Speakable by *this* student cast: short unison lines, no tongue-twister slogan, no English-heavy brand.
- Concept is a **container**. Hard-news placeholder bodies stay plain (no metaphor inside `[NASYONAL NA BALITA]` etc.).
- A simpler bookended system is a valid Division target. Complete load-bearing metaphors are rare even at National (2/18) — prefer a clean bookend over a forced epic metaphor.
- **Station ID is locked:** **DZRM 67.5**. On air: `D-Z-R-M`, `SAIS-SYETE-PUNTO-SINGKO`. Header: `D-Z-R-M 67.5`. Do not invent a different callsign or frequency. **Never** reuse `91.26` or `Patrol` / `Patroller`.
- Invent a **program title** and concept system around that station. Do **not** default to *Tagahabi ng Balita* unless arguments keep weaving.
- **Do not reskin the previous jeepney / aarangkada / biyahe / horn / PEPRENO script.** That overlay is historical. It is also the same metaphor family as quarantined National Contestant 5. Do not import C5 vocabulary (`travel buddy`, `kabiyahero`, `ruta`, `red-light break`, horn-as-logo).
- Weaving / *Tagahabi* is original-to-us and separate from the vehicle overlay. **Keep it only if arguments say to keep it.** Otherwise retire the program name and invent something else — still on DZRM 67.5.
- Truth/service slogans are the genre default — they do not differentiate unless they have a hook that is *ours*.
- Local address: keep **Montalbeños** / Luzon greeting if discovery finds no new audience. If Pililla (or other) research exists, local-anchor the open and close to **that** audience instead. Do not invent a new hometown.
- Fix the **exact form** of slogan, ID, and unison lines before they enter the script. Use that form everywhere.
- In production notes: station ID **LOCKED** (`DZRM 67.5`); program / slogan / metaphor **PROPOSAL — not locked** unless a lock file exists. Also write `division-scripts/DIVISION-CONCEPT-[CONCEPT].md` as a **proposal** (title it clearly as proposal, not approval). Never overwrite an approved lock.

**How to choose (private, then commit):**

1. Generate 2–3 original candidates that pass the quarantine in §4.
2. Score them yourself: originality, speakability, open-to-close payoff, local fit, operator-feasible sonic logo.
3. Ship the winner only. Do not dump the rejected list into the script file. One sentence in production notes is enough ("Concept chosen: … because …").

**`[CONCEPT]` slug (for the filename):**

- Take the program title or the core metaphor — not the long slogan.
- 1–4 words, ASCII letters only, `UPPER-CASE`, hyphen-separated.
- Good: `BATINGAW`, `ILAW`, `HABING-LIWANAG`, `PULSO`.
- Forbidden slugs: `CONCEPT`, `NEW`, `DRAFT`, `V1`, `SCRIPT`, `PATROL`, `AARANGKADA`, `TAGAHABI` (unless the user kept weaving).

Cast default (unless arguments change it): keep the previous role map. Tagapagbalita 3 (Khassy Rada) is credited and does **not** speak. Do not write her in and do not drop her from the header.

---

## 4. Quarantine — never copy

Study **how** strong entries work. Do not become them.

**Never copy** (benchmark §21 + `reusable-techniques.md` “What Would Become Copying” + per-script DO NOT COPY):

- National station identities, callsigns, frequencies (especially the **91.26 / “NSPC Patrol”** family), program titles, “Patroller” titles
- slogans, jingles, distinctive jokes, unique metaphors, signature transitions
- personas (Travel Buddy, kabiyahero, Yas Queen, Chika-Dora, Mamshie Kirby, Kuya Will, etc.)
- exact lines, sign-offs, bumper wording, PSA lines
- competitor sonic logos (C4 sweep, C5 horn as *their* logo, C8 “Offline!”, C15 theme)
- previous-script **exact** jingle lyric, `PEPRENO` / `MULING AARANGKADA` pair, horn close, or other distinctive old wording — unless the user kept that old concept

Safe to learn as **functions**: ~5:00 two-act spine; headline shape; 3-sentence reports; handoff loops; category beds; boundary stingers; beds under speech; infomercial skeleton; closing ritual.

After writing, run an originality pass against §21. If anything is even close, rewrite it.

---

## 5. House format (match `ORIGINAL-SCRIPT.md`, fix the glitches)

Default page look is **our** production script, not National `actual-script.md`.

- Bold, all-caps speaker labels: `**ANGKOR 1:**`, `**TAGAPAGBALITA 1:**`, `**LAHAT:**`, `**BUMPER:**`, `**PAALALA:**`, `**AWIT:**`
- Spoken copy in **ALL CAPS** Filipino
- English or technical terms in *italics* inside Filipino lines
- Sound and music as their own bold cue lines: `**STINGER**`, `**TUNOG NG …**`, `**PAGPASOK NG MUSIKA…**`, combined cues with ellipsis (`**STINGER… PAGPALIT NG MUSIKA…**`)
- Spell station ID for air as `D-Z-R-M`, `SAIS-SYETE-PUNTO-SINGKO`
- Do **not** copy markdown glitches from the old script (broken emphasis on Tagapagbalita 3 / Technical; extra space in `ANGKOR  2`)

**Allowed production extras** (put in a preamble, not as a replacement format):

- a timestamped target rundown table (~5:00)
- self-describing cue labels
- `[UP AND UNDER]` / duck-under-speech notes on beds
- a placeholder legend

Do not turn the spoken script itself into a National-style timestamped transcript.

---

## 6. Architecture the skeleton must implement

**Spine (benchmark observation, 18/18):**

```
branded open → headlines → 2 hard-news reports → tease + promise
→ exactly one infomercial → re-entry → sports → showbiz → recap close
```

**Pacing targets (benchmark observation, not a law — hit the bands):**

| Block | Target |
|-------|--------|
| Open through headlines | first hard news ~55–70 s |
| Each hard-news report | 3 sentences, ~25–35 s, named sign-off |
| Break + infomercial | ~40–50 s advocacy; tease-then-promise in; identity on return |
| Sports / showbiz each | ~30–35 s |
| Close | ~15–25 s, median ~19 s |
| Total | ~5:00 |

**Fixed craft that must appear in the written (non-placeholder) parts:**

1. **First ~20 s:** sonic hook + three-layer ID (promise/slogan → callsign+frequency → program name), each on its own beat.
2. **First ~45 s:** concept revealed (if any).
3. Time-check slot with blank clock (`___ MINUTO MAKALIPAS ANG ___ NG HAPON` or equivalent). Optional one diegetic beep — only one in the whole show.
4. Local/Luzon greeting if still relevant; KBP membership line.
5. Paired self-intros: name + role, tied to the concept without stuffing the news.
6. Headline block: frame line → 4 alternating items with per-item stinger → handoff. **Reveal-shape instruction** on hard-news placeholders; **tease-shape instruction** on sports/showbiz placeholders (do not reveal outcomes).
7. National then local hard news (2 reports). Named-question toss + thank-you receipt around each body placeholder. Reporter sign-off formula carrying station/beat identity (same skeleton, category-word swap).
8. At most **one** scripted mid-report Q&A slot (optional placeholder question), not one per story.
9. Break: **tease-then-promise** bumper (fully written). Infomercial skeleton:

   `hook → scene placeholders → problem → [FACT + SOURCE] → [NAMED SOLUTION] → [VERB+OBJECT CTA] → station tag → return stinger`

   No child-shaming beat (the old teacher PSA had one — do not treat that as a virtue). Do not copy National game-show frames.
10. Re-entry restates identity (and may time-check). Then sports, then showbiz, with category bed changes and a tone shift (lexicon + bed, not a new persona unless the locked/proposed concept already contains one — and contain any persona to the showbiz slot).
11. Close: recap line → anchor IDs → station identity / unison slogan → spoken theme callback to the opening → fade. Same ID form as the open. Closing `**AWIT:** [AWIT-CLOSE]` is a **placeholder with no lyrics**.
12. Sound: **4–5 category beds max**; stingers at **boundaries only**; beds duck under speech; ~1 cue / 15–25 s at rest; self-describing labels; one sonic logo at open and close (and optionally the return), not looped inside reports. Theatrical SFX live in the infomercial zone. No music-only gaps.

Speakability: short declaratives, one main clause per sentence, verbalize numbers when they later get filled, cap English tokens, write lines the cast can actually say. Unison lines must be short.

---

## 7. Placeholder contract (must be consistent)

Use these tokens **verbatim** everywhere that slot appears (headline text, toss reprise, etc.). Do not invent parallel synonyms.

| Token | Meaning | Fill rule on competition day |
|-------|---------|------------------------------|
| `[HEADLINE 1]` | National hard news | Reveal: `[TOPIC], [RESULT STATE]!` — 8–14 words |
| `[HEADLINE 2]` | Local hard news | Same reveal shape |
| `[HEADLINE 3]` | Sports | **Tease** — no score, no winner |
| `[HEADLINE 4]` | Showbiz | **Tease** — no outcome |
| `[NASYONAL NA BALITA]` | National body | 3 sentences; action-first lead; `Ayon sa…` in second breath; hedge `umano`/`diumano`; advisory before sign-off |
| `[LOKAL NA BALITA]` | Local body | Same compression |
| `[SPORTS NA BALITA]` | Sports body | News register + energy; local/Filipino angle |
| `[SHOWBIZ NA BALITA]` | Showbiz body | Tone shift; facts clean |
| `[INFOMERCIAL-SCENE]` | Dramatized scene | Hook + problem; dignifying; 2–4 characters |
| `[AWIT-THEME]` | Opening theme slot | Placeholder only — **no lyrics** |
| `[INFOMERCIAL-AWIT]` | Infomercial song slot | Placeholder only — **no lyrics** |
| `[AWIT-CLOSE]` | Closing reprise slot | Placeholder only — **no lyrics** |
| `[INFOMERCIAL-FACT]` | One sourced statistic | Never invent; needs source |
| `[INFOMERCIAL-SOLUSYON]` | Named entity / solution | Named, not vague |
| `[INFOMERCIAL-CTA]` | Call to action | Verb + object |
| `[INFOMERCIAL-PAALALA]` | Closing PSA line | Then the already-written station tag |
| `[SFX-KWENTO]` | Optional in-story SFX | Only if the day's story needs it; not pre-chosen bells/whistles from old stories |

Keep the previous placeholder spirit: hollow the **content**, not the **architecture**.

### 7b. AWIT — placeholder only, no generated song

**Never write song lyrics.** Melody is hard to source, so invented words are unusable.

Keep the three slots in the rundown as **empty placeholders** (opening after ID, infomercial break, close):

```
**AWIT:** [AWIT-THEME]

**AWIT:** [INFOMERCIAL-AWIT]

**AWIT:** [AWIT-CLOSE]
```

- Do **not** fill those lines with lyrics, chorus, or “sample” verses.
- Do **not** copy the old Tagahabi songs (`HALINA’T MAGLAKBAY…`, teacher PSA song, closing fragment) or any National jingle.
- Carry identity with spoken slogan, unison money lines, stingers, and category beds. The AWIT lines are holes for a track the team already has or will pick later.

Production notes: `AWIT: PLACEHOLDER ONLY (no generated lyrics)`.

In toss lines, reprise the same headline token, then the named reporter, then the question.

Example shape (write real names and a real question; keep the token):

`[HEADLINE 1]. TYRAH INARES, ANO ANG BUONG DETALYE?`

After the body placeholder, a thank-you receipt from the receiving anchor, then the next toss.

---

## 8. Subagents (optional, only if useful)

Use subagents **only** for independent depth. You still choose what to read, resolve conflicts, and make the final file edits. Do **not** spawn subagents for small line edits. Do **not** re-run the 18-script study.

Useful cases:

- **Concept system design** — 2–3 original systems compared privately; pick one; label as proposal. The main agent still writes the files.
- **Originality quarantine check** — against benchmark §21 and C5 travel overlap
- **Structure critique** — against benchmark §26, adapted for a skeleton (news-writing score N/A where bodies are placeholders)

If you spawn any, synthesize their output. Do not paste competing drafts into the repo. Do not leave the user with three half-concepts.

---

## 9. Files you may write

Create `division-scripts/` first if it is missing.

| File | When |
|------|------|
| `division-scripts/DIVISION-SCRIPT-[CONCEPT].md` | **Always** — the structure. `[CONCEPT]` is a short slug from the chosen/locked program title or metaphor. |
| `division-scripts/DIVISION-SCRIPT-[CONCEPT]-2.md` | Same slug already exists and you are not overwriting |
| `division-scripts/DIVISION-CONCEPT-[CONCEPT].md` | Proposal companion when no lock exists; never overwrite an approved lock |

Never write `DIVISION-SCRIPT.md` at repo root. Never name a new draft `ORIGINAL-SCRIPT.md`. Do not fill `ORIGINAL-SCRIPT-PLACEHOLDER.md`. Do not touch `ORIGINAL-SCRIPT.md`.

---

## 10. Output file shape

`division-scripts/DIVISION-SCRIPT-[CONCEPT].md` must contain, in this order:

1. **Production notes (not for air)** — short:
   - status: STRUCTURE / SKELETON
   - station ID: **LOCKED** — DZRM 67.5 (`D-Z-R-M`, `SAIS-SYETE-PUNTO-SINGKO`)
   - concept status: LOCKED vs PROPOSAL (program / slogan / metaphor only)
   - identity in one block (callsign, frequency, program, slogan exact form, sonic logo, audience)
   - AWIT: placeholder only (no generated lyrics) — `[AWIT-THEME]`, `[INFOMERCIAL-AWIT]`, `[AWIT-CLOSE]`
   - placeholder legend (the table above)
   - bed map (4–5 beds) and sonic-logo cue name
   - target rundown table with timing bands
   - role map
   - explicit list of what is historical vs new vs quarantined-and-avoided
2. **The on-air script** in house format, fully written except for the tokens in §7.

Do not include a long research essay. Do not quote National lines “for inspiration.”

---

## 11. Stop / anti-drift checklist (run before finishing)

- [ ] `AGENTS.md` was read first
- [ ] Station ID is **DZRM 67.5** (`D-Z-R-M`, `SAIS-SYETE-PUNTO-SINGKO`) — not a new callsign
- [ ] Program / slogan / metaphor is locked **or** clearly labeled proposal — never presented as already approved
- [ ] You invented and committed to a concept without asking the user to pick (unless they already named one)
- [ ] Output is `division-scripts/DIVISION-SCRIPT-[CONCEPT].md` with a real concept slug — not `DIVISION-SCRIPT.md` at root
- [ ] Not a reskin of aarangkada / jeepney / horn / PEPRENO
- [ ] Nothing from benchmark §21; no 91.26; no Patrol; no C5 travel lexicon
- [ ] Previous news stories absent; National news pool absent
- [ ] Placeholders consistent; every competition-day slot uses the §7 tokens
- [ ] Headlines 3–4 exist as tokens with reveal-vs-tease instructions in the notes
- [ ] Named-question toss + thank-you around each report placeholder
- [ ] Infomercial has written bumpers + CTA-shaped holes; no shaming beat
- [ ] AWIT slots present as empty placeholders only — no generated lyrics
- [ ] Close answers the open; slogan form is identical everywhere
- [ ] House format; no copied markdown glitches; Tagapagbalita 3 credited, silent
- [ ] New file written; `ORIGINAL-SCRIPT.md` untouched
- [ ] Chat reply tells the user the output path, the concept in one sentence, proposal vs lock, and how to fill tokens on the day — without reprinting the entire script unless they ask

If arguments request a filled news script, **refuse that part** and still produce the structure, unless the user also supplied a fact sheet and explicitly asked to fill — even then, this command's default is placeholders.

Begin. Stay on track.
)
