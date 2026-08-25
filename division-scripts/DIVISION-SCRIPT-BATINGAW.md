# DIVISION-SCRIPT-BATINGAW — Batingaw ng Balita (STRUCTURE)

## A. Production Notes (hindi para sa ere)

**Status:** STRUCTURE / SKELETON — kompetisyon-day na nilalaman (balita, infomercial, orasan) ang mga placeholder. Huwag punan mula sa National news pool (Ormoc ATM scam, WPS cyanide, Middle East oil, Alcantara, Oscars 2026). Walang kasalukuyang fact sheet — gumawa ng isa bago punan ang anumang balita.

**Concept status:** PROPOSAL — hindi pa LOCKED. Tingnan ang `DIVISION-CONCEPT-BATINGAW.md`; ilalapat ng user ang pag-apruba.

**Identity (fixed forms — walang variant drift):**

| Elemento | Exact form |
|---|---|
| Callsign | `D-Z-R-M` (**LOCKED**) |
| Frequency | 67.5 — binibigkas na `SAIS-SYETE-PUNTO-SINGKO` (**LOCKED**) |
| Program | `BATINGAW NG BALITA` |
| Slogan | `SA BAWAT TUNOG, KATOTOHANAN.` — schedule: open (split) → return (Anchor 2) → close (unison) |
| Sonic logo | `TUNOG NG BATINGAW` — isang hampas ng kampana; open, return, at close LANG |
| Audience | `MGA TAGAPAKINIG` — pangkalahatan; walang demonym, walang hometown (utos ng user) |
| Break pair | `PAPAHINGA MUNA ANG KAMPANA…` / `NAGBATINGAW MULI!` |
| Sign-off family | `[NAME], NAGPATUNOG NG BALITA.` / `…NG PALAKASAN.` / `…NG TSIKAHAN.` |
| Anchor roles | A1 `TAGAPAGBATINGAW NG BALITA`; A2 `KABATINGAW` |

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
| 3 | BED NG TSIKAHAN | Upbeat, sparkle accent |
| 4 | BED NG PALAKASAN | Percussive, energetic |
| 5 | BED NG PAALALA | Soft acoustic (infomercial zone) |

- Stinger files: **S1 = STINGER NG ULO NG BALITA** (maikling drum hit — headline commas); **S2 = STINGER NG SEAM** (riser/swoosh — block boundaries). Sa script, nakasulat nang bahay bilang `**STINGER**`; ang operator ang nagmamapa: sa headlines = S1, sa mga seam/break = S2.
- `**TUNOG NG BATINGAW**` = isang hampas ng kampana (logo). Tatlong beses LANG: open, return, close.
- `**TUNOG NG ORASAN**` = isang beep — ang TANGING diegetic beep ng buong broadcast.
- **Ang infomercial zone ay ang pahinga ng kampana:** walang `TUNOG NG BATINGAW` sa loob ng PAALALA block (konseptong sinasadya).
- Beds duck under speech: `[UP AND UNDER]` sa bawat pagpasok ng bed.

**Target rundown (~5:00):**

| Oras | Block | Band |
|---|---|---|
| 0:00–0:12 | Batingaw + three-layer ID (slogan → callsign → program) | ID sa loob ng 20 s |
| 0:12–0:30 | Time check + beep, greeting, KBP line | |
| 0:30–0:50 | Paired intros (role-titled) + "kaya" hook | |
| 0:50–1:05 | Headline block: frame → 4 items + stinger → handoff | first news 55–70 s ✓ |
| 1:05–1:35 | National report (Tyrah) + optional Q&A | 3 sentences, 25–35 s |
| 1:35–2:05 | Local report (Carl) | 3 sentences, 25–35 s |
| 2:05–2:20 | Tease-then-promise break loop | break ≈ 2:05–2:45 band |
| 2:20–3:05 | Infomercial (~45 s) | 40–50 s band |
| 3:05–3:15 | Re-entry: bell + bumper + ID + slogan | identity first |
| 3:15–3:50 | Sports (Carl) | ~35 s |
| 3:50–4:25 | Showbiz (Tyrah) | ~35 s |
| 4:25–4:45 | Close: recap → IDs → ID split → unison slogan → callback → bell + fade | 15–25 s (median ~19 s) |

**Role map:** ANGKOR 1 = Rain Calites (lead; ID, headline 1, national toss, sports launch, close start); ANGKOR 2 = Celine Asoy (time check, greeting, headline 2 at 4, local toss, showbiz launch, break rest-line, close completion); TAGAPAGBALITA 1 = Tyrah Inares (national + showbiz); TAGAPAGBALITA 2 = Carl Adlawan (local + sports); TAGAPAGBALITA 3 = Khassy Rada (credited, walang linya — huwag isulat, huwag tanggalin); TECHNICAL = Rodger Pacumba Jr.; DIRECTOR = Gwyneth Ashley Damasen. (Cast argument: wala — default sa dating role map.)

**Historical vs new vs quarantined:**

- **Historical (hindi dinala):** Tagahabi ng Balita, aarangkada/makina/busina/horn, `PEPRENO MUNA` / `MULING AARANGKADA`, weaving brand (retired — walang "keep weaving" argument), mga lumang linya at kwento (Geronimo, KVSHS, DepEd grading, Kris Aquino), lumang greeting/Jingle. Ang lumang school-bell SFX sa loob ng kwento — hindi dinala (konsepto na ngayon ang kampana sa gilid, hindi sa kwento). **(Ang LOCKED na D-Z-R-M 67.5 ang dala.)**
- **New (proposal):** DZRM 67.5 (LOCKED), Batingaw ng Balita, slogan, bell logo, break pair, sign-off family, tagapagbatingaw/kabatingaw (neutral audience).
- **Quarantined at iniiwasan (verify sa bawat pass):** anumang "…Patrol"/"91.26", C5 travel lexicon (kabiyahero, ruta, travel buddy, red light, horn-as-logo), C8 "Offline!"/digital frame, C17 "Tatak-", C13 "Heto na!", C1/C18 game-show infomercial frame, at ang lahat ng exact lines sa benchmark §21.

**Delivery flags (rehearsal items):** ang frequency string `SAIS-SYETE-PUNTO-SINGKO`; `TAGAPAGBATINGAW`; `KABATINGAW`; lahat ng unison lines; lahat ng sign-offs (pinaka-garbled recurring line ng corpus — i-drill). Tatlong-minsang pronunciation drill bago ang bawat ensayo.

---

## B. On-Air Script

**HIMPILAN NG RADYO**
**D-Z-R-M 67.5**
**BATINGAW NG BALITA**
**ANGKOR 1:** Rain Calites
**ANGKOR 2:** Celine Asoy
**TAGAPAGBALITA 1:** Tyrah Inares
**TAGAPAGBALITA 2:** Carl Adlawan
**TAGAPAGBALITA 3:** Khassy Rada
**TECHNICAL:** Rodger Pacumba Jr.
**TAGAPAGSULAT NG ISKRIP:** Rodger Pacumba Jr.
**DIRECTOR:** Gwyneth Ashley Damasen

**TUNOG NG BATINGAW** (ISANG HAMPAS NG KAMPANA)

**ANGKOR 1:** SA BAWAT TUNOG,

**ANGKOR 2:** KATOTOHANAN!

**STINGER**

**ANGKOR 1:** D-Z-R-M, SAIS-SYETE-PUNTO-SINGKO.

**STINGER**

**ANGKOR 1 AT 2:** BATINGAW NG BALITA!

**PAGPASOK AT PAGBABA NG MUSIKANG PAMBUNGAD [UP AND UNDER]…**

**TUNOG NG ORASAN** (ISANG BEEP)

**ANGKOR 2:** ANG ORAS NATIN NGAYON AY ___ MINUTO MAKALIPAS ANG ___ NG HAPON.

**ANGKOR 1:** MAGANDANG HAPON, LUZON!

**ANGKOR 2:** AT MAGANDANG HAPON, MGA TAGAPAKINIG!

**ANGKOR 1:** ANG HIMPILANG ITO AY KASAPI NG K-B-P, KAPISANAN NG MGA BRODKASTER NG PILIPINAS.

**STINGER… PAGHINTO NG MUSIKA…**

**ANGKOR 1:** AKO ANG INYONG TAGAPAGBATINGAW NG BALITA, RAIN CALITES.

**STINGER**

**ANGKOR 2:** AT AKO NAMAN ANG INYONG KABATINGAW, CELINE ASOY.

**STINGER… PAGTULOY NG MUSIKA…**

**ANGKOR 2:** ANO KAYA ANG MGA KAGANAPAN NGAYONG HAPON?

**ANGKOR 1:** SA ULO NG MGA BALITA!

**STINGER… PAGPALIT NG BED NG BALITA…**

**ANGKOR 1:** [HEADLINE 1]

**STINGER**

**ANGKOR 2:** [HEADLINE 2]

**STINGER**

**ANGKOR 1:** ABA, MAINIT NA BALITA 'YAN!

**STINGER**

**ANGKOR 1:** [HEADLINE 3]

**STINGER**

**ANGKOR 2:** [HEADLINE 4]

**STINGER**

**ANGKOR 1:** SIMULAN NA NATIN SA UNANG BALITA!

**ANGKOR 1:** [HEADLINE 1]. TYRAH INARES, ANO ANG BUONG DETALYE?

**TAGAPAGBALITA 1:** [NASYONAL NA BALITA]. TYRAH INARES, NAGPATUNOG NG BALITA.

**ANGKOR 1:** (OPTIONAL — ISANG Q&A LAMANG SA BUONG BROADCAST) TYRAH, [Q&A-TANONG]?

**TAGAPAGBALITA 1:** [Q&A-SAGOT].

**ANGKOR 1:** MARAMING SALAMAT, TYRAH!

**ANGKOR 2:** SAMANTALA, [HEADLINE 2]. CARL ADLAWAN, ANO ANG PINAKAHULING KAGANAPAN?

**TAGAPAGBALITA 2:** [LOKAL NA BALITA]. CARL ADLAWAN, NAGPATUNOG NG BALITA.

**ANGKOR 2:** MARAMING SALAMAT, CARL!

**STINGER… PAGBABA AT PAGHINTO NG MUSIKA…**

**ANGKOR 1:** PAGKATAPOS NG PAALALA, TUTUNOG ANG PALAKASAN AT ANG TSIKAHAN!

**BUMPER:** PAPAHINGA MUNA ANG KAMPANA… PARA SA ISANG MAIKLING PAALALA!

**ANGKOR 1:** MANATILI SA TUNOG NG D-Z-R-M, MAGBABALIK TAYO!

**STINGER… PAGPASOK NG BED NG PAALALA [UP AND UNDER]…**

**KARAKTER 1:** [INFOMERCIAL-SCENE]

**NARRATOR:** [INFOMERCIAL-FACT]

**NARRATOR:** [INFOMERCIAL-SOLUSYON]

**NARRATOR:** [INFOMERCIAL-CTA]

**AWIT:** [INFOMERCIAL-AWIT] (OPTIONAL — KUNG WALA, BURAHIN ANG LINYA)

**PAALALA:** [INFOMERCIAL-PAALALA] PAALALA MULA SA D-Z-R-M, BATINGAW NG BALITA.

**STINGER… PAGHINTO NG MUSIKA…**

**TUNOG NG BATINGAW** (ISANG HAMPAS NG KAMPANA)

**ANGKOR 1:** NAGBATINGAW MULI!

**ANGKOR 2:** SA BAWAT TUNOG, KATOTOHANAN!

**ANGKOR 1:** D-Z-R-M, SAIS-SYETE-PUNTO-SINGKO,

**ANGKOR 1 AT 2:** BATINGAW NG BALITA!

**PAGPASOK NG BED NG PALAKASAN [UP AND UNDER]…**

**ANGKOR 1:** PARA SA BALITANG PALAKASAN!

**ANGKOR 1:** [HEADLINE 3]. CARL ADLAWAN, ANONG LATEST SA PALAKASAN?

**TAGAPAGBALITA 2:** [SPORTS NA BALITA]. CARL ADLAWAN, NAGPATUNOG NG PALAKASAN.

**ANGKOR 1:** MARAMING SALAMAT, CARL!

**PAGPALIT NG BED NG TSIKAHAN [UP AND UNDER]…**

**ANGKOR 2:** PARA SA BALITANG TSIKAHAN!

**ANGKOR 2:** [HEADLINE 4]. TYRAH INARES, ANONG MERON SA TSIKAHAN?

**TAGAPAGBALITA 1:** [SHOWBIZ NA BALITA]. TYRAH INARES, NAGPATUNOG NG TSIKAHAN.

**ANGKOR 2:** MARAMING SALAMAT, TYRAH!

**STINGER… PAGPALIT NG MUSIKANG PAMBUNGAD [UP AND UNDER]…**

**ANGKOR 1:** MGA TAGAPAKINIG, IYAN ANG MGA BALITANG TINUNOG NG BATINGAW NGAYONG HAPON.

**ANGKOR 1:** AKO SI RAIN CALITES.

**ANGKOR 2:** AT AKO SI CELINE ASOY.

**ANGKOR 1:** ITO ANG…

**ANGKOR 2:** D-Z-R-M, SAIS-SYETE-PUNTO-SINGKO,

**ANGKOR 1 AT 2:** BATINGAW NG BALITA!

**ANGKOR 1 AT 2:** SA BAWAT TUNOG, KATOTOHANAN!

**ANGKOR 2:** PAPAHINGA NA ANG KAMPANA…

**ANGKOR 1:** PERO TULOY ANG PAGTUNOG NG KATOTOHANAN.

**TUNOG NG BATINGAW… PAGBABA AT PAGHINTO NG MUSIKA…**
