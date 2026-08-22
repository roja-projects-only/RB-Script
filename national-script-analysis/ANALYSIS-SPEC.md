# Shared Analysis Specification (ANALYSIS-SPEC)

**Read this file before analyzing. Follow it exactly.**

This spec governs every per-script analysis, specialist report, and cross-comparison report produced in this directory. It exists so that independent agents produce consistent, self-contained, evidence-based documents that future AI agents can reuse without re-reading the source scripts.

---

## 0. Corpus Orientation

- Read `corpus-inventory.md` first for file types and exclusions.
- **PRIMARY source per entry:** `transcripts/Contestant-N/actual-script.md` (metadata + rundown table with timestamps + verbatim timed dialogue + SFX cues + fact sheet).
- **Supporting:** `full-transcript.md` (verbatim, with timing metadata — use for pacing evidence and resolving unclear lines), `formatted-script.md` (clean production formatting — use only for Script Readability evidence).
- **NEVER analyze `mic-check.md`** — it is pre-broadcast setup, not part of the official performance. If content from the mic-check phase appears inside `full-transcript.md`, skip it.
- **NEVER modify source transcripts.**

---

## 1. Evidence Discipline

Every claim must be labeled with one of these categories. Do not present inference as fact.

| Label | Meaning |
|---|---|
| **DIRECTLY OBSERVED** | Explicitly present in the script; quote short evidence lines (a phrase or sentence is fine). |
| **CROSS-SCRIPT PATTERN** | Observed repeatedly across multiple independent entries (name which ones). |
| **ANALYST INFERENCE** | Your interpretation of why something works, or a judgment call. Always flag it as such and give the reasoning. |

Rules:
- Quote short lines as evidence — never paraphrase away the evidence.
- When a line contains transcript corrections (e.g., `*[intended text]*`, `[possibly: …]`), note it and quote the intended reading.
- Distinguish **observed quality characteristics** from **official competition criteria**. No official criteria exist in the workspace; do not invent them. If you reference general knowledge about NSPC radio broadcasting judging, label it `ANALYST INFERENCE` (external knowledge).

---

## 2. Required Per-Script Analysis Structure (25 sections)

Each per-script analysis MUST contain all of the following sections, in order, with exactly these headings (numbered as below). Be specific and analytical — explain WHY, never just describe.

### 1. Script Identity
Station/program name, callsign/frequency, anchors, reporters, competition/event if known, approximate runtime, overall creative concept. Only document what the source supports; say "uncertain" where unclear.

### 2. High-Level Rundown
Reverse-engineer the actual sequence (e.g., Sonic opening → Station ID → Anchor greeting → Headlines → Local news → … → Closing). Use the script's real order; do not force a template.

### 3. Opening Analysis
First sound heard, first spoken line, how quickly branding appears, station ID placement, anchor introduction, concept reveal, energy, memorability, anticipation, seconds/lines spent before the first news. Explain WHY it works or fails.

### 4. Central Creative Concept
Central metaphor/theme, recurring vocabulary, recurring sounds, consistency across the broadcast, whether the theme extends beyond the intro (transitions, bumpers, closing), and whether it becomes distracting or gimmicky. Specific examples.

### 5. Station Branding
Callsign pronunciation, program title, tagline, station ID, sonic logo, catchphrases, repeated language, memorability. Explain how branding is reinforced without becoming annoying.

### 6. Anchor Roles
Who leads/reacts, who introduces stories, who performs transitions, balance of roles, interaction style, conversational lines, scripted spontaneity, questions, teasing, audience address, handoffs. Verdict: do the anchors sound like readers, hosts, partners, performers, or commentators — and why?

### 7. Anchor Chemistry
Interruptions, shared sentence continuation, short exchanges, call-and-response, humor, reactions, rhetorical questions, shared station IDs, simultaneous lines. What creates rhythm?

### 8. Headlines
Number of headlines, length, syntax, strong verbs, immediacy, curiosity, dramatic wording, ordering, topic variety, separators, stingers, tease-vs-reveal balance. Extract general headline-writing patterns; do NOT merely list the headlines.

### 9. News Story Construction
For every major report: lead, source attribution, key details, supporting info, context, quote/paraphrase style, ending/sign-off, sentence count, information density, uninterrupted speaking length. Derive the underlying pattern (e.g., LEAD → SOURCE → KEY DETAIL → CONTEXT → CONSEQUENCE → SIGN-OFF) from THIS script's actual evidence.

### 10. Anchor-to-Reporter Handoffs
Direct intro, question format, conversational setup, headline repetition, reporter name placement, teaser language, stinger placement. Which techniques feel strongest and why.

### 11. Reporter Sign-Offs
Name, station/program identity, segment-specific branding, rhyme, tagline, whether sign-offs differ by category. Identify recurring formulas.

### 12. Transition System
Document every major transition (intro→headlines, headlines→story, story→story, news→break, break→infomercial, infomercial→program, news→sports, sports→showbiz, showbiz→closing): spoken transition, SFX, stinger, music change, pause, bumper. How does the script avoid feeling like disconnected reports?

### 13. Sound Design
Catalog meaningful audio cues (stingers, news beds, genre beds, notification sounds, clocks, bells, horns, environmental sounds, dialogue-integrated SFX, fades, hard stops, music changes, sonic logos). For each important sound state its FUNCTION: branding, transition, emphasis, pacing, realism, comedy, attention reset, category identification. Do not just inventory.

### 14. Music Bed Strategy
How many beds, when they change, whether categories get different beds, beds under dialogue, fade-in/out, musically driven transitions. How music supports pacing.

### 15. Infomercial / Advocacy Segment
Entry bumper, concept, characters, hook, problem/conflict, humor/emotion, factual content, call to action, slogan, duration, sound design, return to broadcast. Why does it feel integrated (or not)?

### 16. Sports Segment
Transition, music, language, pace, headline style, energy, reporter personality, sign-off, differences from hard-news delivery.

### 17. Showbiz Segment
Tone shift, vocabulary, conversational quality, humor, reporter personality, music/SFX, transition, sign-off. How does the genre change happen without losing station identity?

### 18. Closing
Summary/recap, anchor identification, station ID, call to follow/listen again, final slogan, final SFX, jingle, simultaneous lines, emotional finish. What gives the broadcast a sense of completion?

### 19. Language
Filipino/English/Taglish mix, slang, formal terminology, conversational vocabulary, idioms, metaphors, sentence length, rhythm. Where does language become formal vs playful?

### 20. Script Readability
Formatting practice: speaker labeling, SFX placement, music cues, capitalization, line breaks, cue clarity, role clarity. (Use `formatted-script.md` and the format of `actual-script.md`.) Useful practices, separate from content.

### 21. Pacing
Number of major segments, duration distribution, long vs short speech blocks, frequency of stingers, frequency of speaker changes, attention resets per minute. How does the script maintain momentum? (Use rundown timestamps when available.)

### 22. Information Density
How much factual info fits per report, line compression, removal of unnecessary background, lead concision, balance of information vs personality.

### 23. Memorable Techniques
Most effective techniques in THIS script: what it is, where it appears, why it works, and whether the PRINCIPLE could be adapted safely.

### 24. Weaknesses
Be critical: awkward lines, unclear transitions, excessive gimmicks, repetitive phrases, weak stories, pacing problems, unnatural dialogue, overlong sections, confusing sound design.

### 25. Reusable Lessons
End with three subsections:

- **## KEEP AS A PRINCIPLE** — general techniques worth learning.
- **## ADAPT CAREFULLY** — good ideas that could become derivative if copied too closely.
- **## DO NOT COPY** — unique program titles, slogans, signature lines, specific metaphors, jingles, station identities, proprietary creative concepts.

We are studying technique, not stealing another team's identity.

---

## 3. Required Specialist Report Structures

Specialists read ALL relevant entries (primarily each `actual-script.md`; use `full-transcript.md` for pacing/timing verification; `formatted-script.md` for readability evidence) and produce their designated report. Follow the same evidence discipline. Use the structures below.

### A — Structure & Rundown → `specialists/structure-and-rundown.md`
Segment ordering, story counts, infomercial placement, sports/showbiz placement, opening length, closing length, overall architecture. Identify: universal structure, flexible elements, optional elements, notable exceptions.

### B — Openings & Branding → `specialists/openings-and-branding.md`
Compare first 30 seconds, station IDs, sonic logos, slogans, program names, concept introduction, anchor intros. Identify strongest openings and derive principles for a memorable opening.

### C — Anchor Dynamics → `specialists/anchor-dynamics.md`
Chemistry, conversational exchange, call-and-response, sentence splitting, audience engagement, transitions, teasing, questions, personality. Document recurring dialogue patterns.

### D — Headline Techniques → `specialists/headline-techniques.md`
Reverse-engineer syntax, word count, verbs, urgency, punctuation, topic order, teaser strategy, stinger timing. Create reusable headline formulas WITHOUT copying actual lines.

### E — News Writing → `specialists/news-writing.md`
All hard-news reports: common structures for local/national/breaking/issue stories; leads, attribution, detail ordering, compression, reporter endings, factual density. Produce reusable news-writing frameworks.

### F — Transitions & Bumpers → `specialists/transitions-and-bumpers.md`
Catalog transition logic: transitions, commercial breaks, teaser lines, return bumpers, story changes, category changes. Focus on FUNCTION, not copied wording.

### G — Sound Design → `specialists/sound-design.md`
SFX frequency, stingers, music, fades, sonic logos, category sounds, transitions, use of silence. How do National scripts use sound without overcrowding dialogue?

### H — Infomercials → `specialists/infomercial-analysis.md`
Advocacy/commercial segments: concept, characters, narrative, hook, pacing, sound, facts, call to action, slogan, length. Derive common frameworks.

### I — Sports & Showbiz → `specialists/sports-and-showbiz.md`
How scripts deliberately alter tone for softer categories: vocabulary, energy, sound, humor, transitions, reporter identity, sign-offs.

### J — Language & Delivery → `specialists/language-and-delivery.md`
Filipino/English/Taglish, formal vs conversational, sentence length, alliteration, rhyme, punchlines, repetition, verbal rhythm, pronunciation-friendly writing. Focus on writing intended to be SPOKEN.

### K — Pacing & Timing → `specialists/pacing-and-timing.md`
Estimate seconds per segment, lines per segment, speaker-switch frequency, stinger spacing, reporter block duration, advocacy time, sports/showbiz time, closing duration. Find common pacing patterns. Mark estimates as estimates; do not fabricate precision.

### L — Originality & Concept → `specialists/originality-and-concept.md`
Central themes, metaphors, sonic concepts, branding systems, consistency, gimmick risk, uniqueness. What separates a complete concept from an intro gimmick?

### M — Competition Quality → `specialists/competition-quality.md`
Think like an experienced radio-broadcasting competition evaluator. Distinguish **Observed quality characteristics** (from the scripts) from **Official competition criteria** (state explicitly that none are present in the workspace). Cover: preparation, polish, originality, clarity, cohesion, timing, technical sophistication, script economy, delivery support, memorability.

---

## 4. Required Cross-Comparison Report Structures

Cross-comparison agents read the per-script analyses and specialist reports (and spot-check source scripts when verifying a claim). Produce:

### Cross-Comparison 1 → `cross-comparison/recurring-patterns.md`
Techniques appearing across MULTIPLE entries. For each: pattern, number of scripts where observed, examples by script, likely purpose, strength of evidence. Classify each as **NEAR-UNIVERSAL** / **COMMON** / **OPTIONAL** / **TEAM-SPECIFIC**. This classification is critical — it prevents assuming one National formula.

### Cross-Comparison 2 → `cross-comparison/differences-between-teams.md`
Areas where successful scripts differ (conversational vs formal anchors, heavy vs subtle concept, many SFX vs restrained, comedy-heavy vs serious, long vs short headlines). Prevents the false assumption of a single correct formula.

### Cross-Comparison 3 → `cross-comparison/reusable-techniques.md`
Translate observations into general principles. For each technique include: **Technique** / **Why It Works** / **Evidence Across Scripts** / **How We Could Apply It** / **What Would Become Copying** / **Division-Level Practicality** (rate EASY / MODERATE / DIFFICULT).

---

## 5. Output Rules (all agents)

1. You own exactly ONE output file (your assigned path). Create it with the `write` tool. Do not write anywhere else. Do not modify source transcripts or other analyses.
2. Documents must be **self-contained**: another AI reading only your file must fully understand the findings.
3. Be **specific** — short quoted evidence lines, real numbers where available, concrete examples.
4. Be **analytical** — state function and reason, not just presence.
5. Be **critical** — document weaknesses, not only strengths.
6. Use the evidence labels from Section 1 throughout.
7. Write in clear English; quoted source lines remain in their original Filipino/Taglish.
8. If a section has no evidence in the assigned entry (e.g., no infomercial), say so explicitly instead of inventing content.
