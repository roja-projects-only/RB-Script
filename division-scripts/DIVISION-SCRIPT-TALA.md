# DIVISION-SCRIPT-TALA — Tala ng Balita (STRUCTURE)

## A. Production Notes (hindi para sa ere)

**Status:** STRUCTURE / SKELETON — kompetisyon-day na nilalaman (balita, infomercial, orasan) ang mga placeholder. Huwag punan mula sa National news pool (Ormoc ATM scam, WPS cyanide, Middle East oil, Alcantara, Oscars 2026) o mula sa lumang kwento (Geronimo, KVSHS, DepEd grading, Kris Aquino). Walang kasalukuyang fact sheet — gumawa ng isa bago punan ang anumang balita.

**Concept status:** PROPOSAL — hindi pa LOCKED. Tingnan ang `DIVISION-CONCEPT-TALA.md`; ilalapat ng user ang pag-apruba.

**Concept chosen:** Tala ng Balita — follow/remain star system — dahil maiksi ang slogan, operator-simple ang isang chime, at iba ang payoff nito sa sibling BATINGAW (kampana) at DALUYONG (alon).

**Identity (fixed forms — walang variant drift):**

| Elemento | Exact form |
|---|---|
| Callsign | `D-Z-R-M` (**LOCKED**) |
| Frequency | 67.5 — binibigkas na `SAIS-SYETE-PUNTO-SINGKO` (**LOCKED**) |
| Program | `TALA NG BALITA` |
| Slogan | `SUNDAN ANG TALA.` — schedule: open (split) → return (Anchor 2) → close (unison) |
| Sonic logo | `TUNOG NG TALA` — isang mataas, maikli, maliwanag na chime (glockenspiel/celesta; HINDI kampana); open, return, at close LANG |
| Audience | `MGA TAGAPAKINIG` — pangkalahatan; walang demonym, walang hometown (utos ng user) |
| Break pair | `HUWAG MAWALA SA TALA…` / `NANDITO PA ANG TALA!` |
| Sign-off family | `[NAME], SUMUSUNOD SA BALITA.` / `…SA PALAKASAN.` / `…SA TSIKAHAN.` |
| Anchor roles | A1 `GABAY SA TALA NG BALITA`; A2 `KASAMA SA PAGSUNOD` |

**Placeholder legend (verbatim tokens — huwag palitan ng kasingkahulugan):**

| Token | Kahulugan | Panuntunan sa pagpuno |
|---|---|---|
| `[HEADLINE 1]` | National hard news | Reveal shape: `[TOPIC], [RESULT STATE]!` — 8–14 salita, isang hininga |
| `[HEADLINE 2]` | Local hard news | Same reveal shape |
| `[HEADLINE 3]` | Sports | **Tease** — walang iskor, walang panalo |
| `[HEADLINE 4]` | Showbiz | **Tease** — walang resulta/outcome |
| `[NASYONAL NA BALITA]` | National body | 3 pangungusap, action-first lead, `Ayon sa…` sa ikalawang hininga, hedge ng alegasyon (`umano`/`diumano`), advisory bago ang sign-off; verbalize numbers; gloss `X o Y`; ≤1 English token kada pangungusap |
| `[LOKAL NA BALITA]` | Local body | Same compression + advisory |
| `[SPORTS NA BALITA]` | Sports body | News register + energy; local/Filipino angle; agency response |
| `[SHOWBIZ NA BALITA]` | Showbiz body | Tone shift (tsikahan register); facts clean; walang name confusion |
| `[INFOMERCIAL-SCENE]` | Dramatized scene | Hook (tunog o tanong, ~5 s) + problema; dignifying; 2–4 karakter; **walang child-shaming beat; hindi game-show frame**; dito lang ang theatrical SFX ng araw |
| `[INFOMERCIAL-AWIT]` | Song | Opsyonal; empty line ready; kung wala, burahin ang AWIT line |
| `[INFOMERCIAL-FACT]` | Sourced statistic | Isang verified na numero + named source; never invent; glossed |
| `[INFOMERCIAL-SOLUSYON]` | Named entity | Named program/solusyon, hindi vague |
| `[INFOMERCIAL-CTA]` | Call to action | Verb + object + named entity |
| `[INFOMERCIAL-PAALALA]` | Closing PSA line | Isang linya; sinusundan ng nakasulat na station tag |
| `[SFX-KWENTO]` | Optional in-story SFX | Kung kakailanganin lang ng kuwento ng araw; hindi pre-chosen na kampana/pinto/pito |
| `[Q&A-TANONG]` | Status question (optional) | Isang Q&A lamang sa buong broadcast; tanong sa status ng kuwento, pre-answerable |
| `[Q&A-SAGOT]` | Answer | Dapat may pangalawang sourced fact; isulat ang magkabilang panig sa iisang pahina |

**Bed map (5 beds max — isang operator):**

| Bed | Label sa script | Kalidad |
|---|---|---|
| 1 | MUSIKANG PAMBUNGAD / PAGWAWAKAS | Warm newsroom; open + close (bookend) |
| 2 | BED NG BALITA | Steady, seryoso |
| 3 | BED NG PALAKASAN | Percussive, energetic |
| 4 | BED NG TSIKAHAN | Upbeat, sparkle accent sa bed mismo |
| 5 | BED NG PAALALA | Soft acoustic (infomercial zone) |

- Stinger files: **S1 = STINGER NG ULO NG BALITA** (maikling drum hit — headline commas); **S2 = STINGER NG SEAM** (riser/swoosh — block boundaries). Sa script, nakasulat nang bahay bilang `**STINGER**`; ang operator ang nagmamapa: sa headlines = S1, sa mga seam/break = S2.
- `**TUNOG NG TALA**` = isang mataas na chime (logo). Tatlong beses LANG: open, return, close. File: `tala-chime.wav` — huwag bell, huwag wave, huwag busina.
- `**TUNOG NG ORASAN**` = isang beep — ang TANGING diegetic beep ng buong broadcast.
- Beds duck under speech: `[UP AND UNDER]` sa bawat pagpasok ng bed.
- Theatrical SFX: infomercial zone lamang. Walang music-only gap.

**Target rundown (~5:00):**

| Oras | Block | Band |
|---|---|---|
| 0:00–0:12 | Chime + three-layer ID (slogan → callsign → program) | ID sa loob ng 20 s |
| 0:12–0:32 | Time check + beep, Luzon/Ilokano greeting, KBP line | |
| 0:32–0:50 | Paired intros + "kaya / sisilay" hook | first ~45 s: concept revealed |
| 0:50–1:08 | Headline block: frame → 4 items + stinger → handoff | first news 55–70 s ✓ |
| 1:08–1:40 | National report (Tyrah) + optional Q&A | 3 sentences, 25–35 s |
| 1:40–2:10 | Local report (Carl) | 3 sentences, 25–35 s |
| 2:10–2:22 | Tease-then-promise break loop | break ≈ 2:05–2:45 band |
| 2:22–3:08 | Infomercial (~45 s) | 40–50 s band |
| 3:08–3:20 | Re-entry: chime + bumper + ID + slogan | identity first |
| 3:20–3:55 | Sports (Carl) | ~35 s |
| 3:55–4:30 | Showbiz (Tyrah) | ~35 s |
| 4:30–4:50 | Close: recap → IDs → ID split → unison slogan → sisilay/nanatili → chime + fade | 15–25 s (median ~19 s) |

**Role map:** ANGKOR 1 = Rain Calites (lead; ID, headline 1 at 3, national toss, sports launch, close start); ANGKOR 2 = Celine Asoy (time check, Luzon greeting, headline 2 at 4, local toss, showbiz launch, break hold-line, close completion); TAGAPAGBALITA 1 = Tyrah Inares (national + showbiz); TAGAPAGBALITA 2 = Carl Adlawan (local + sports); TAGAPAGBALITA 3 = Khassy Rada (credited, walang linya — huwag isulat, huwag tanggalin); TECHNICAL / TAGAPAGSULAT = Rodger Pacumba Jr.; DIRECTOR = Gwyneth Ashley Damasen.

**Historical vs new vs quarantined:**

- **Historical (hindi dinala ang identity; dinala ang craft):** house format, role map, KBP line, time-check slot, Luzon/Ilokano greeting. Hindi dinala: Tagahabi, aarangkada/makina/busina/horn, `PEPRENO`/`MULING AARANGKADA`, weaving, lumang jingle, lumang kwento, child-shaming beat ng teacher PSA. **(Ang LOCKED na D-Z-R-M 67.5 ang dala.)**
- **New (proposal):** DZRM 67.5 (LOCKED), Tala ng Balita, `SUNDAN ANG TALA.`, star-chime logo, break pair, `SUMUSUNOD SA…` sign-off family, gabay/kasama roles.
- **Quarantined at iniiwasan:** anumang "…Patrol"/"91.26"; C5 travel lexicon; C8 Offline/digital; C17 Tatak-; C13 Heto na; C1/C18 game-show infomercial; exact lines sa benchmark §21; sibling BATINGAW at DALUYONG lines, kampana, at alon.

**Delivery flags (rehearsal items):** `D-Z-R-M`; `SAIS-SYETE-PUNTO-SINGKO`; unison `SUNDAN ANG TALA.`; `TALA NG BALITA`; lahat ng sign-off (`SUMUSUNOD SA…` — pinaka-garbled recurring line ng corpus); split `SISILAY ANG TALA` / `AT NANATILI.`; Ilokano `NAIMBAG NGA ADLAW`. Tatlong-minsang pronunciation drill bago ang bawat ensayo.

---

## B. On-Air Script

**HIMPILAN NG RADYO**
**D-Z-R-M 67.5**
**TALA NG BALITA**
**ANGKOR 1:** Rain Calites
**ANGKOR 2:** Kate Ashley Asoy (Celine Asoy)
**TAGAPAGBALITA 1:** Tyrah Dichos (Tyrah Inares)
**TAGAPAGBALITA 2:** Carl Evans Adlawan (Carl Adlawan)
**TAGAPAGBALITA 3:** Rheannes Kassandra Rada (Khassy Rada)
**TECHNICAL:** Rodger Pacumba Jr.
**TAGAPAGSULAT NG ISKRIP:** Rodger Pacumba Jr.
**DIRECTOR:** Gwyneth Ashley Damasen

**TUNOG NG TALA** (ISANG MATAAS NA CHIME — HINDI KAMPANA)

**ANGKOR 1:** SUNDAN

**ANGKOR 2:** ANG TALA!

**STINGER**

**ANGKOR 1:** D-Z-R-M, SAIS-SYETE-PUNTO-SINGKO.

**STINGER**

**ANGKOR 1 AT 2:** TALA NG BALITA!

**PAGPASOK AT PAGBABA NG MUSIKANG PAMBUNGAD [UP AND UNDER]…**

**TUNOG NG ORASAN** (ISANG BEEP)

**ANGKOR 2:** ANG ORAS NATIN NGAYON AY ___ MINUTO MAKALIPAS ANG ___ NG HAPON.

**ANGKOR 1:** PARA SA MGA TAGA-LUZON,

**ANGKOR 2:** NAIMBAG NGA ADLAW!

**ANGKOR 2:** MAGANDANG HAPON, MGA TAGAPAKINIG!

**ANGKOR 1:** ANG HIMPILANG ITO AY KASAPI NG K-B-P, KAPISANAN NG MGA BRODKASTER NG PILIPINAS.

**STINGER**

**ANGKOR 1:** AKO ANG INYONG GABAY SA TALA NG BALITA, RAIN CALITES.

**STINGER**

**ANGKOR 2:** AT AKO ANG INYONG KASAMA SA PAGSUNOD, CELINE ASOY.

**STINGER**

**ANGKOR 2:** ANONG MGA BALITA KAYA ANG SISILAY NGAYONG HAPON?

**ANGKOR 1:** ITO ANG UNANG SILAY!

**STINGER… PAGPALIT NG BED NG BALITA [UP AND UNDER]…**

**ANGKOR 1:** [HEADLINE 1]

**STINGER**

**ANGKOR 2:** [HEADLINE 2]

**STINGER**

**ANGKOR 1:** MALAPIT SA ATIN IYAN.

**STINGER**

**ANGKOR 1:** [HEADLINE 3]

**STINGER**

**ANGKOR 2:** [HEADLINE 4]

**STINGER**

**ANGKOR 1:** SUNDAN NATIN ANG UNANG BALITA!

**ANGKOR 1:** [HEADLINE 1]. TYRAH INARES, ANO ANG BUONG DETALYE?

**TAGAPAGBALITA 1:** [NASYONAL NA BALITA]. TYRAH INARES, SUMUSUNOD SA BALITA.

**ANGKOR 1:** (OPTIONAL — ISANG Q&A LAMANG SA BUONG BROADCAST) TYRAH, [Q&A-TANONG]?

**TAGAPAGBALITA 1:** [Q&A-SAGOT].

**ANGKOR 1:** MARAMING SALAMAT, TYRAH!

**ANGKOR 2:** SAMANTALA, [HEADLINE 2]. CARL ADLAWAN, ANO ANG BUONG ULAT?

**TAGAPAGBALITA 2:** [LOKAL NA BALITA]. CARL ADLAWAN, SUMUSUNOD SA BALITA.

**ANGKOR 2:** MARAMING SALAMAT, CARL!

**STINGER… PAGBABA AT PAGHINTO NG MUSIKA…**

**ANGKOR 1:** PAGKATAPOS NG PAALALA, SISILAY ANG PALAKASAN AT ANG TSIKAHAN!

**BUMPER:** HUWAG MAWALA SA TALA… PARA SA ISANG MAIKLING PAALALA!

**ANGKOR 2:** MANATILI SA D-Z-R-M, MAGBABALIK TAYO!

**STINGER… PAGPASOK NG BED NG PAALALA [UP AND UNDER]…**

**KARAKTER 1:** [INFOMERCIAL-SCENE]

**KARAKTER 2:**

**KARAKTER 3:**

**NARRATOR:** [INFOMERCIAL-FACT]

**NARRATOR:** [INFOMERCIAL-SOLUSYON]

**NARRATOR:** [INFOMERCIAL-CTA]

**AWIT:** [INFOMERCIAL-AWIT]

**PAALALA:** [INFOMERCIAL-PAALALA] PAALALA MULA SA D-Z-R-M, TALA NG BALITA.

**STINGER… PAGHINTO NG MUSIKA…**

**TUNOG NG TALA** (ISANG MATAAS NA CHIME)

**ANGKOR 1:** NANDITO PA ANG TALA!

**ANGKOR 2:** SUNDAN ANG TALA.

**ANGKOR 1:** D-Z-R-M, SAIS-SYETE-PUNTO-SINGKO,

**ANGKOR 1 AT 2:** TALA NG BALITA!

**PAGPASOK NG BED NG PALAKASAN [UP AND UNDER]…**

**ANGKOR 1:** LUMIPAT TAYO SA PALAKASAN!

**ANGKOR 1:** [HEADLINE 3]. CARL ADLAWAN, ANO ANG PINAKABAGO SA PALAKASAN?

**TAGAPAGBALITA 2:** [SPORTS NA BALITA]. CARL ADLAWAN, SUMUSUNOD SA PALAKASAN.

**ANGKOR 1:** MARAMING SALAMAT, CARL!

**PAGPALIT NG BED NG TSIKAHAN [UP AND UNDER]…**

**ANGKOR 2:** AT NGAYON, SA TSIKAHAN!

**ANGKOR 2:** [HEADLINE 4]. TYRAH INARES, ANO ANG USAPAN SA TSIKAHAN?

**TAGAPAGBALITA 1:** [SHOWBIZ NA BALITA]. TYRAH INARES, SUMUSUNOD SA TSIKAHAN.

**ANGKOR 2:** MARAMING SALAMAT, TYRAH!

**STINGER… PAGPALIT NG MUSIKANG PAMBUNGAD [UP AND UNDER]…**

**ANGKOR 1:** MGA TAGAPAKINIG, IYAN ANG MGA BALITANG SINUNDAN NATIN NGAYONG HAPON.

**ANGKOR 1:** AKO SI RAIN CALITES.

**ANGKOR 2:** AT AKO SI CELINE ASOY.

**ANGKOR 1:** ITO ANG,

**STINGER**

**ANGKOR 1:** D-Z-R-M,

**ANGKOR 2:** SAIS-SYETE-PUNTO-SINGKO,

**ANGKOR 1 AT 2:** TALA NG BALITA!

**ANGKOR 1 AT 2:** SUNDAN ANG TALA.

**ANGKOR 2:** SISILAY ANG TALA…

**ANGKOR 1:** AT NANATILI.

**TUNOG NG TALA… PAGBABA AT PAGHINTO NG MUSIKA…**
