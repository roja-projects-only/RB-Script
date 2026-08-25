# DIVISION-SCRIPT-HIMIG — Himig ng Balita (COMPLETE NEW SCRIPT)

## A. Production Notes (hindi para sa ere)

**Status:** COMPLETE NEW SCRIPT — kompetisyon-day na nilalaman (balita, infomercial, orasan, optional Q&A) ang mga placeholder. Huwag punan mula sa National news pool (Ormoc ATM scam, WPS cyanide, Middle East oil, Alcantara, Oscars 2026) o mula sa lumang kwento (Geronimo, KVSHS, DepEd grading, Kris Aquino). **Walang kasalukuyang fact sheet — gumawa ng isa bago punan ang anumang balita** (benchmark §14: iwasan ang cross-entry contradictions ng corpus).

**Concept status:** PROPOSAL — hindi pa LOCKED. Tingnan ang `DIVISION-CONCEPT-HIMIG.md`. Kapag nag-lock: i-update ang status na ito at i-archive ang ibang proposal files.

**Identity (fixed forms — walang variant drift):**

| Elemento | Exact form |
|---|---|
| Callsign | `D-Z-R-M` (**LOCKED**) |
| Frequency | 67.5 — binibigkas na `SAIS-SYETE-PUNTO-SINGKO` (**LOCKED**) |
| Program | `HIMIG NG BALITA` |
| Slogan | `MAKINIG SA HIMIG NG BAYAN!` — schedule: open (split) → return (A2) → close (LAHAT) |
| Sonic logo | `TUNOG NG HIMIG` — isang 3-note motif (do-mi-sol; recorder/whistle/xylophone; HINDI chime, HINDI kampana); open, return, at close LANG |
| Audience | `MGA TAGAPAKINIG` — pangkalahatan; walang demonym, walang hometown (utos ng user) |
| Break pair | `SANDALI TAYONG MAGPAPALIT NG HIMIG…` / `MULING NARIRINIG ANG HIMIG NG BALITA!` |
| Sign-off family | `[NAME], NAGTUGTUG NG BALITA.` / `…NG PALARO.` / `…NG *SHOWBIZ*.` |
| Anchor roles | A1 `TAGA-TUGTOG NG HIMIG NG BALITA`; A2 `KASALIW SA HIMIG` |

**AWIT decisions (PLACEHOLDER-ONLY — walang isinusulat na lyrics):**

| Slot | Desisyon | Dahilan |
|---|---|---|
| Opening theme | **PLACEHOLDER** (`[AWIT-THEME]`) | Utos ng user: walang isinusulat na lyrics; slot para sa track na mayroon o kukunin ng team. |
| Infomercial jingle | **PLACEHOLDER** (`[INFOMERCIAL-AWIT]`) | Competition-day advocacy topic; kung jingle-shaped ang PSA ng araw, mag-drop ng track doon; kung hindi, burahin ang linya. |
| Closing reprise | **PLACEHOLDER** (`[AWIT-CLOSE]`) | Slot para sa track ng team; hindi isinusulat bilang lyrics. |

**Placeholder legend (verbatim tokens — huwag palitan ng kasingkahulugan):**

| Token | Kahulugan | Panuntunan sa pagpuno |
|---|---|---|
| `[HEADLINE 1]` | National hard news | Reveal shape: `[TOPIC], [RESULT STATE]!` — 8–14 salita, isang hininga |
| `[HEADLINE 2]` | Local hard news | Same reveal shape |
| `[HEADLINE 3]` | Sports | **Tease** — walang iskor, walang panalo; pwede question-form na may "kaya" |
| `[HEADLINE 4]` | Showbiz | **Tease** — walang resulta/outcome |
| `[NASYONAL NA BALITA]` | National body | 3 pangungusap, action-first lead, `Ayon sa…` sa ikalawang hininga, hedge ng alegasyon (`umano`/`diumano`), advisory bago ang sign-off; verbalize numbers; gloss `X o Y`; ≤1 English token kada pangungusap |
| `[LOKAL NA BALITA]` | Local body | Same compression + advisory; local/Filipino angle |
| `[SPORTS NA BALITA]` | Sports body | News register + energy (ang enerhiya ay nasa bed, hindi sa hype) |
| `[SHOWBIZ NA BALITA]` | Showbiz body | Tone shift; facts clean; walang name confusion |
| `[INFOMERCIAL-SCENE]` | Dramatized scene | Hook (tunog o tanong, ~5 s) + problema; dignifying; 2–4 karakter; **walang child-shaming beat; hindi game-show frame**; dito lang ang theatrical SFX ng araw |
| `[INFOMERCIAL-FACT]` | Sourced statistic | Isang verified na numero + named source; never invent; glossed |
| `[INFOMERCIAL-SOLUSYON]` | Named entity | Named program/solusyon, hindi vague |
| `[INFOMERCIAL-CTA]` | Call to action | Verb + object + named entity |
| `[INFOMERCIAL-PAALALA]` | Closing PSA line | Isang linya; sinusundan ng nakasulat na station tag |
| `[INFOMERCIAL-AWIT]` | Song | PLACEHOLDER — kung walang awit, burahin ang AWIT line |
| `[Q&A-TANONG]` | Status question (optional) | Isang Q&A lamang sa buong broadcast; tanong sa status ng kuwento, pre-answerable |
| `[Q&A-SAGOT]` | Answer | Dapat may pangalawang sourced fact; isulat ang magkabilang panig sa iisang pahina |
| `[SFX-KWENTO]` | Optional in-story SFX | Kung kakailanganin lang ng kuwento ng araw; hindi pre-chosen. **Diegetic lamang** (tunog sa loob ng kuwento), HINDI theatrical — ang theatrical ay nasa `[INFOMERCIAL-SCENE]` lamang. **Isisingit sa loob ng `[NASYONAL NA BALITA]` o `[LOKAL NA BALITA]` kapag pupunan; kung walang angkop na tunog, huwag isingit** |

**Bed map (5 beds max — isang operator):**

| Bed | Label sa script | Kalidad |
|---|---|---|
| 1 | MUSIKANG PAMBUNGAD / PAGWAWAKAS | Warm, melodic; open + close (bookend) |
| 2 | BED NG BALITA | Steady, seryoso |
| 3 | BED NG PALARO | Percussive, energetic |
| 4 | BED NG *SHOWBIZ* | Bright, upbeat (glam accent) |
| 5 | BED NG PAALALA | Soft acoustic (infomercial zone) |

- Stinger files: **S1 = HAMPAS NG HIMIG** (maikling accent hit na echo ng huling nota ng motif — headline commas at ID moments); **S2 = PAGLIPAT NG HIMIG** (riser/swoosh — mga hangganan ng block, break in/out). Sa script ay nakasulat nang bahay bilang `**STINGER**`; ang operator ang nagmamapa: headlines/ID = S1, seams/break = S2.
- `**TUNOG NG HIMIG**` = ang 3-note motif (ang logo). Tatlong beses LANG: open, return, close. File: `himig-motibo.wav` — huwag chime, huwag kampana, huwag busina.
- `**TUNOG NG ISANG BEEP**` = isang beep — ang TANGING diegetic beep ng buong broadcast.
- **Ang infomercial zone ay ang PALIT ng himig:** walang `TUNOG NG HIMIG` sa loob ng PAALALA block (sinasadya — ang break ay nagpapalit ng himig, hindi humihinto; ang logo ay nasa edges lang).
- Beds duck under speech: `[UP AND UNDER]` sa bawat pagpasok/pagpalit ng bed. Walang music-only gaps.

**Target rundown (~5:00):**

| Oras | Block | Band / Note |
|---|---|---|
| 0:00–0:11 | Motif + three-layer ID (slogan split → callsign → program) | ID sa loob ng 20 s ✓; konsepto nasa unang ~10 s ✓ |
| 0:11–0:21 | AWIT (opening theme, PLACEHOLDER — `[AWIT-THEME]`) | slot para sa track ng team |
| 0:21–0:37 | Time check + beep, Luzon/Ilokano greeting, KBP line | |
| 0:37–0:50 | Paired intros (role-titled) + "kaya" hook | |
| 0:50–1:05 | Headline block: frame → 4 items + per-item stinger + reaction → handoff | |
| 1:05–1:40 | National report (Tyrah) + optional Q&A | 3 pangungusap, 25–35 s; first news 55–70 s ✓ |
| 1:40–2:14 | Local report (Carl) | 3 pangungusap, 25–35 s |
| 2:14–2:26 | Break loop: tease → bumper (PALIT) → promise | break ≈ 2:05–2:45 band ✓ |
| 2:26–3:12 | Infomercial (~45 s) | 40–50 s band; ≈48% ng broadcast ✓ |
| 3:12–3:24 | Re-entry: motif → `MULING NARIRINIG…` → slogan → ID | identity first |
| 3:24–3:59 | Sports (Carl) | ~35 s |
| 3:59–4:34 | Showbiz (Tyrah) | ~35 s |
| 4:34–4:54 | Close: recap → IDs → ID split → unison slogan → callback → AWIT (`[AWIT-CLOSE]`) → motif + fade | 15–25 s (median ~19 s) ✓ |

Ang mga band ay target; ang natural na slack (reporter ad-libs, stinger tails, bed transitions) ang nagdadala sa ~5:00. Stopwatch rehearsal (benchmark §18).

**Role map:** ANGKOR 1 = Rain Calites (motif cue call, slogan 1a, callsign, AWIT lead, greeting line 1, KBP line, headline 1 at 3, reaction token, handoff, national toss + Q&A + receipt, break tease, re-entry `MULING NARIRINIG…`, sports launch + toss + receipt, close recap, self-ID, ID split 1a, callback line 2); ANGKOR 2 = Celine Asoy (slogan 1b, time check, greeting line 2, headline 2 at 4, local toss + receipt, break bumper, re-entry slogan, showbiz launch + toss + receipt, self-ID, ID split 1b, unison slogan, callback line 1); TAGAPAGBALITA 1 = Tyrah Inares (national + showbiz); TAGAPAGBALITA 2 = Carl Adlawan (local + sports); TAGAPAGBALITA 3 = Khassy Rada (credited, walang linya — huwag isulat, huwag tanggalin); TECHNICAL / TAGAPAGSULAT NG ISKRIP = Rodger Pacumba Jr.; DIRECTOR = Gwyneth Ashley Damasen. `LAHAT` = ANGKOR 1–2 + TAGAPAGBALITA 1–2 (apat na boses).

**Dissimilarity note (kung ano ang sadyang HINDI kinuha mula sa lumang script):**

- **Retired:** Tagahabi ng Balita, weaving brand, aarangkada/makina/busina/horn, `PEPRENO MUNA` / `MULING AARANGKADA` / `AARANGKADA NA`, lumang jingle (theme, teacher PSA song, close), `ITO ANG…` opening cadence, `SA ULO NG MGA NAGBABAGANG BALITA`, `I-CHIKA MO NA`, `CHISMIS NA WALANG KAPARES`, `BALITAANG PALABAN` / `PAMPALAKASANG BALITA`, `MONTALBEÑOS, IYAN ANG MGA BALITANG…` close line, `KAAGAPAY…`/`KATUWANG…` intro lines, lumang kwento, child-shaming beat ng teacher PSA, Tagapagbalita 3 broken emphasis glitch. **(Ang LOCKED na D-Z-R-M 67.5 ang dala.)**
- **Hindi rin kinuha sa mga kapatid na proposal:** kampana/`NAGPATUNOG`/rhyme family (BATINGAW-2), alon/`PAHAWAK`/`SUMABAY`/`DUMALOY` (DALUYONG), tala/`SUNDAN`/`SISILAY`/`GABAY` (TALA), `SA BAWAT TAHANAN` address, `MAGBABALIK TAYO` promise, `TSIKAHAN`/`TSISMISAN` showbiz words, `PALAKASAN` sports word, rest-the-logo break architecture.
- **Dinala bilang craft (hindi identity):** house format (bold ALL-CAPS labels, italic English terms, ellipsis cue combos), role map, KBP line, time-check slot, Luzon/Ilokano greeting function (conscious keep per AGENTS.md §9 — ang Ilokano phrase ay stock greeting, hindi namin likha), digit-by-digit frequency style, National spine (open → headlines → 2 hard news → infomercial → re-entry → sports → showbiz → close).
- **Quarantined at iniiwasan (verify sa bawat pass):** anumang "…Patrol"/"91.26"; C5 travel lexicon; C8 "Offline!"/"Tama muna pag-scroll"; C17 "Tatak-"; C9 "Kasama Ka"; C13 "Heto na!"/"LABAN, PILIPINAS!"; C18 "Walang preno, tuloy-tuloy"; C10 "nagmamasid sa… napapanahon"; C16 mapanuri-chain; C1 "Pilipinas… balitaan na!"/"Mabuhay ka!"; lahat ng exact lines sa benchmark §21. Iwasan din: `tuloy`, `bawat`, `tahanan`, `katotohanan`, `magbabalik`, `chika`/`tsismis`, journey words, water words.

**Delivery flags (rehearsal items):** `D-Z-R-M`; `SAIS-SYETE-PUNTO-SINGKO`; `HIMIG NG BALITA`; `MAKINIG SA HIMIG NG BAYAN!`; `NAGTUGTUG NG…` (lahat ng sign-offs — pinaka-garbled na recurring line ng corpus); `I-TUGTUG MO SA AMIN…`; `TAGA-TUGTOG` / `KASALIW`; `MULING NARIRINIG…`; `NAIMBAG NGA ADLAW`; lahat ng unison lines. (AWIT ay placeholder-only — walang sung lines na isinusulat.) Tatlong-minsang pronunciation drill bago ang bawat ensayo.

---

## B. On-Air Script

**HIMPILAN NG RADYO**
**D-Z-R-M 67.5**
**HIMIG NG BALITA**
**ANGKOR 1:** Rain Calites
**ANGKOR 2:** Celine Asoy
**TAGAPAGBALITA 1:** Tyrah Inares
**TAGAPAGBALITA 2:** Carl Adlawan
**TAGAPAGBALITA 3:** Khassy Rada
**TECHNICAL:** Rodger Pacumba Jr.
**TAGAPAGSULAT NG ISKRIP:** Rodger Pacumba Jr.
**DIRECTOR:** Gwyneth Ashley Damasen

**TUNOG NG HIMIG** (TATLONG NOTA — DO-MI-SOL; HINDI CHIME, HINDI KAMPANA)

**ANGKOR 1:** MAKINIG.

**ANGKOR 2:** SA HIMIG NG BAYAN!

**STINGER**

**ANGKOR 1:** D-Z-R-M, SAIS-SYETE-PUNTO-SINGKO.

**LAHAT:** HIMIG NG BALITA!

**AWIT:** [AWIT-THEME]

**PAGPASOK AT PAGBABA NG MUSIKANG PAMBUNGAD [UP AND UNDER]…**

**TUNOG NG ISANG BEEP** (ANG TANGING DIEGETIC BEEP NG BUONG BROADCAST)

**ANGKOR 2:** TINGNAN NATIN ANG ORAS: \_\_\_ MINUTO MAKALIPAS ANG \_\_\_ NG HAPON.

**ANGKOR 1:** MAGANDANG HAPON, MGA TAGA-LUZON!

**ANGKOR 2:** NAIMBAG NGA ADLAW, MGA TAGAPAKINIG!

**ANGKOR 1:** ANG HIMPILANG ITO AY KASAPI NG K-B-P, KAPISANAN NG MGA BRODKASTER NG PILIPINAS.

**STINGER**

**ANGKOR 1:** AKO ANG INYONG TAGA-TUGTOG NG HIMIG NG BALITA, RAIN CALITES.

**ANGKOR 2:** AT AKO ANG INYONG KASALIW SA HIMIG, CELINE ASOY.

**ANGKOR 2:** ANONG MGA HIMIG KAYA ANG TUTUGTOG SA ATIN NGAYONG HAPON?

**ANGKOR 1:** MAKINIG TAYO!

**STINGER… PAGPALIT NG BED NG BALITA [UP AND UNDER]…**

**ANGKOR 1:** [HEADLINE 1]

**STINGER**

**ANGKOR 2:** NAKU, SERYOSO IYAN!

**ANGKOR 2:** [HEADLINE 2]

**STINGER**

**ANGKOR 1:** [HEADLINE 3]

**STINGER**

**ANGKOR 2:** [HEADLINE 4]

**STINGER**

**ANGKOR 1:** TUGTUGIN NATIN ANG UNANG BALITA!

**ANGKOR 1:** [HEADLINE 1]. TYRAH INARES, ANO ANG BUONG DETALYE?

**TAGAPAGBALITA 1:** [NASYONAL NA BALITA]. TYRAH INARES, NAGTUGTUG NG BALITA.

**ANGKOR 1:** TYRAH, [Q&A-TANONG]? (ISANG Q&A LAMANG SA BUONG BROADCAST — KUNG WALA, LUMIPAT SA LOKAL NA TOSS)

**TAGAPAGBALITA 1:** [Q&A-SAGOT].

**ANGKOR 1:** MARAMING SALAMAT, TYRAH!

**ANGKOR 2:** SAMANTALA, [HEADLINE 2]. CARL ADLAWAN, ANO ANG PINAKABAGONG DETALYE?

**TAGAPAGBALITA 2:** [LOKAL NA BALITA]. CARL ADLAWAN, NAGTUGTUG NG BALITA.

**ANGKOR 2:** MARAMING SALAMAT, CARL!

**STINGER… PAGBABA AT PAGHINTO NG MUSIKA…**

**ANGKOR 1:** MAY HIHINTONG BAGONG HIMIG PAGKATAPOS NG PAALALA — ANG PALARO AT ANG *SHOWBIZ*!

**BUMPER:** SANDALI TAYONG MAGPAPALIT NG HIMIG… MAY MAIKLING PAALALA PARA SA INYO!

**ANGKOR 1:** MANATILI SA HIMIG NG D-Z-R-M, HIMIG NG BALITA!

**STINGER… PAGPASOK NG BED NG PAALALA [UP AND UNDER]…**

**KARAKTER 1:** [INFOMERCIAL-SCENE]

**KARAKTER 2:**

**KARAKTER 3:**

**NARRATOR:** [INFOMERCIAL-FACT]

**NARRATOR:** [INFOMERCIAL-SOLUSYON]

**NARRATOR:** [INFOMERCIAL-CTA]

**AWIT:** [INFOMERCIAL-AWIT] (PLACEHOLDER — KUNG WALANG AWIT SA ADVOCACY NG ARAW, BURAHIN ANG LINYA)

**PAALALA:** [INFOMERCIAL-PAALALA] PAALALA MULA SA D-Z-R-M, HIMIG NG BALITA.

**PAGHINTO NG MUSIKA…**

**TUNOG NG HIMIG** (TATLONG NOTA)

**ANGKOR 1:** MULING NARIRINIG ANG HIMIG NG BALITA!

**ANGKOR 2:** MAKINIG SA HIMIG NG BAYAN!

**ANGKOR 1:** D-Z-R-M, SAIS-SYETE-PUNTO-SINGKO,

**LAHAT:** HIMIG NG BALITA!

**PAGPASOK NG BED NG PALARO [UP AND UNDER]…**

**ANGKOR 1:** PARA SA HIMIG NG PALARO!

**ANGKOR 1:** [HEADLINE 3]. CARL ADLAWAN, I-TUGTUG MO SA AMIN ANG HIMIG NG PALARO!

**TAGAPAGBALITA 2:** [SPORTS NA BALITA]. CARL ADLAWAN, NAGTUGTUG NG PALARO.

**ANGKOR 1:** MARAMING SALAMAT, CARL!

**PAGPALIT NG BED NG *SHOWBIZ* [UP AND UNDER]…**

**ANGKOR 2:** PARA NAMAN SA HIMIG NG *SHOWBIZ*!

**ANGKOR 2:** [HEADLINE 4]. TYRAH INARES, I-TUGTUG MO SA AMIN ANG HIMIG NG *SHOWBIZ*!

**TAGAPAGBALITA 1:** [SHOWBIZ NA BALITA]. TYRAH INARES, NAGTUGTUG NG *SHOWBIZ*.

**ANGKOR 2:** MARAMING SALAMAT, TYRAH!

**PAGPALIT NG MUSIKANG PAMBUNGAD [UP AND UNDER]…**

**ANGKOR 1:** MGA TAGAPAKINIG, NAPAKINGGAN NATIN ANG HIMIG NG BALITA NGAYONG HAPON.

**ANGKOR 1:** AKO SI RAIN CALITES.

**ANGKOR 2:** AT AKO SI CELINE ASOY.

**ANGKOR 1:** D-Z-R-M, SAIS-SYETE-PUNTO-SINGKO,

**ANGKOR 2:** HIMIG NG BALITA!

**LAHAT:** MAKINIG SA HIMIG NG BAYAN!

**ANGKOR 2:** NATAPOS NA ANG HIMIG NGAYONG HAPON…

**ANGKOR 1:** PERO BUKAS, MAY BAGO TAYONG HIMIG.

**AWIT:** [AWIT-CLOSE]

**TUNOG NG HIMIG… PAGBABA AT PAGHINTO NG MUSIKA…**
