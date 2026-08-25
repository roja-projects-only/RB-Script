# DIVISION-SCRIPT-BATINGAW-2 — Batingaw ng Balita (STRUCTURE)

## A. Production Notes (hindi para sa ere)

**Status:** STRUCTURE / SKELETON — kompetisyon-day na nilalaman (balita, infomercial, orasan) ang mga placeholder. Huwag punan mula sa National news pool (Ormoc ATM scam, WPS cyanide, Middle East oil, Alcantara, Oscars 2026). Walang kasalukuyang fact sheet — gumawa ng isa bago punan ang anumang balita.

**Concept status:** PROPOSAL — hindi pa LOCKED. Ito ang binagong anyo ng BATINGAW. Tingnan ang `DIVISION-CONCEPT-BATINGAW-2.md`. Kung i-lock ng team ang BATINGAW, ang `-2` na ito ang dapat i-lock (hindi ang lumang `DIVISION-SCRIPT-BATINGAW.md`).

**Bakit `-2` (mga argumento ng user sa run na ito):**

- **"no montalbenos"** → inalis ang anumang town-specific na address: Pililla (lumang BATINGAW / DALUYONG) at Montalbeños (dating TALA). Audience = pangkalahatan: `SA BAWAT TAHANAN`. Walang bagong hometown na inimbento.
- **"make sure they rhyme well"** → bagong slogan, break tease, at close callback na may tugma. Tingnan ang rhyme map sa ibaba. Ang tugma ay nasa gilid lamang (bukas, break, malapit), alinsunod sa benchmark §17 rhythm-at-edges rule.

**Identity (fixed forms — walang variant drift):**

| Elemento | Exact form |
|---|---|
| Callsign | `D-Z-R-M` (**LOCKED**) |
| Frequency | 67.5 — binibigkas na `SAIS-SYETE-PUNTO-SINGKO` (**LOCKED**, house digit-by-digit style) |
| Program | `BATINGAW NG BALITA` |
| Slogan | `KAMPANA NG KATOTOHANAN, TUNOG SA BAWAT TAHANAN.` — schedule: open (split) → return (buo, A2) → close (split) |
| Sonic logo | `TUNOG NG BATINGAW` — isang hampas ng kampana; open, return, at close LANG |
| Audience | `SA BAWAT TAHANAN` — pangkalahatan; walang demonym saanman |
| Break pair | `PAPAHINGA MUNA ANG KAMPANA…` / `NAGBATINGAW MULI!` |
| Break tease (rhyming) | `MAY SUSUNOD PA TAYONG KAGANAPAN — KAYA MANATILI SA INYONG TAHANAN!` |
| Close callback | `PAPAHINGA NA ANG KAMPANA…` + `PERO SA BAWAT TAHANAN, TULOY ANG KATOTOHANAN.` — echo ng slogan (completion device, hindi slogan variant) |
| Sign-off family | `[NAME], NAGPATUNOG NG BALITA.` / `…NG PALAKASAN.` / `…NG TSISMISAN.` |
| Anchor roles | A1 `TAGAPAGBATINGAW NG BALITA`; A2 `KABATINGAW` |

**Rhyme map (tugma sa gilid lamang):**

- `KATOTOHANAN ~ TAHANAN` — slogan; tunay na tugma (parehong -HANAN).
- `KAGANAPAN ~ TAHANAN` — break tease; -an family (karaniwang Tagalog tugma).
- `PALAKASAN ~ TSISMISAN ~ KAGANAPAN ~ TAHANAN` — ang -an family ang signature ng buong sistema.
- `…TULOY ANG KATOTOHANAN` — huling linyang sinasabi; echo ng slogan.
- Rhyme ang pinakamataas na risk na device ng corpus (§17): huwag baligtarin ang grammar para lang tumugma; i-drill ang bawat rhymed line.

**Placeholder legend (verbatim tokens — huwag palitan ng kasingkahulugan):**

| Token | Kahulugan | Panuntunan sa pagpuno |
|---|---|---|
| `[HEADLINE 1]` | National hard news | Reveal shape: `[TOPIC], [RESULT STATE]!` — 8–14 salita, isang hininga |
| `[HEADLINE 2]` | Local hard news | Same reveal shape |
| `[HEADLINE 3]` | Sports | **Tease** — walang iskor, walang panalo |
| `[HEADLINE 4]` | Showbiz | **Tease** — walang resulta/outcome |
| `[NASYONAL NA BALITA]` | National body | 3 pangungusap, action-first lead, `Ayon sa…` sa ikalawang hininga, hedge ng alegasyon (`umano`/`diumano`), advisory bago ang sign-off; verbalize numbers; gloss `X o Y`; ≤1 English token kada pangungusap |
| `[LOKAL NA BALITA]` | Local body | Same compression + advisory. **Walang hometown assumption** — anumang lugar sa Pilipinas |
| `[SPORTS NA BALITA]` | Sports body | News register + energy; local/Filipino angle; 3 pangungusap |
| `[SHOWBIZ NA BALITA]` | Showbiz body | Tone shift (tsismisan register); facts clean; walang name confusion |
| `[INFOMERCIAL-SCENE]` | Dramatized scene | Hook (tunog o tanong, ~5 s) + problema; dignifying; 2–4 karakter; **walang child-shaming beat; hindi game-show frame**; dito lang ang theatrical SFX ng araw |
| `[INFOMERCIAL-AWIT]` | Song | Opsyonal; kung walang awit, burahin ang AWIT line |
| `[INFOMERCIAL-FACT]` | Sourced statistic | Isang verified na numero + named source; never invent; glossed |
| `[INFOMERCIAL-SOLUSYON]` | Named entity | Named program/solusyon, hindi vague |
| `[INFOMERCIAL-CTA]` | Call to action | Verb + object + named entity |
| `[INFOMERCIAL-PAALALA]` | Closing PSA line | Isang linya; sinusundan ng nakasulat na station tag |
| `[SFX-KWENTO]` | Optional in-story SFX | Kung kakailanganin lang ng kuwento ng araw; hindi pre-chosen. **Diegetic lamang** (tunog sa loob ng kuwento — telepono, TV sa palengke), HINDI theatrical; ang theatrical ay nasa `[INFOMERCIAL-SCENE]` lamang |
| `[Q&A-TANONG]` | Status question (optional) | Isang Q&A lamang sa buong broadcast; tanong sa status ng kuwento, pre-answerable |
| `[Q&A-SAGOT]` | Answer | Dapat may pangalawang sourced fact; isulat ang magkabilang panig sa iisang pahina |

**Bed map (5 beds max — isang operator):**

| Bed | Label sa script | Kalidad |
|---|---|---|
| 1 | MUSIKANG PAMBUNGAD / PAGWAWAKAS | Warm newsroom; open + close (bookend) |
| 2 | BED NG BALITA | Steady, seryoso |
| 3 | BED NG PALAKASAN | Percussive, energetic |
| 4 | BED NG TSISMISAN | Upbeat, sparkle accent |
| 5 | BED NG PAALALA | Soft acoustic (infomercial zone) |

- Stinger files: **S1 = STINGER NG ULO NG BALITA** (maikling impact — headline commas); **S2 = STINGER NG SEAM** (riser/swoosh — mga hangganan). Sa script ay nakasulat nang bahay bilang `**STINGER**`; ang operator ang nagmamapa: headlines = S1, seams/break = S2.
- `**TUNOG NG BATINGAW**` = isang hampas ng kampana (ang logo). Tatlong beses LANG: open, return, close.
- `**TUNOG NG ORASAN**` = isang beep — ang TANGING diegetic beep ng buong broadcast.
- **Ang infomercial zone ay ang pahinga ng kampana:** walang `TUNOG NG BATINGAW` sa loob ng PAALALA block (sinasadya — echo ng break pair).
- Beds duck under speech: `[UP AND UNDER]` sa bawat pagpasok/pagpalit ng bed. Walang music-only gaps.

**Target rundown (~5:00):**

| Oras | Block | Band / Note |
|---|---|---|
| 0:00–0:10 | Batingaw + three-layer ID (slogan → callsign → program) | ID sa loob ng 20 s ✓ |
| 0:10–0:28 | Time check + beep, greeting, KBP line | |
| 0:28–0:48 | Paired intros (role-titled) + "kaya" hook | |
| 0:48–1:03 | Headline block: frame → 4 items + per-item stinger → handoff | |
| 1:03–1:33 | National report (Tyrah) + optional Q&A | 3 pangungusap, 25–35 s; first news 55–70 s ✓ |
| 1:33–2:03 | Local report (Carl) | 3 pangungusap, 25–35 s |
| 2:03–2:18 | Break loop: tease (rhyming) → bumper → promise + identity | break position nasa corpus band (2:05–2:45) ✓ |
| 2:18–3:03 | Infomercial (~45 s) | 40–50 s band |
| 3:03–3:13 | Re-entry: bell → `NAGBATINGAW MULI!` → slogan → ID | identity first |
| 3:13–3:48 | Sports (Carl) | ~35 s |
| 3:48–4:23 | Showbiz (Tyrah) | ~35 s |
| 4:23–4:48 | Close: recap → IDs → ID split → slogan → callback → bell + fade | 15–25 s (median ~19 s) ✓ |

Ang mga band ay target; ang natural na slack (reporter ad-libs, stinger tails, bed transitions) ang nagdadala sa ~5:00.

**Role map:** ANGKOR 1 = Rain Calites (ID layer 1a, callsign, greeting line 2, KBP line, headline 1 at 3, reaction, handoff, national toss + Q&A + receipt, break promise, re-entry `NAGBATINGAW MULI!`, sports launch + toss + receipt, close recap, self-ID, `ITO ANG…`, slogan 1a, callback line 2); ANGKOR 2 = Celine Asoy (slogan 1b, time check, greeting line 1, headline 2 at 4, local toss + receipt, break tease, re-entry slogan, showbiz launch + toss + receipt, self-ID, callsign, slogan 1b, callback line 1); TAGAPAGBALITA 1 = Tyrah Inares (national + showbiz); TAGAPAGBALITA 2 = Carl Adlawan (local + sports); TAGAPAGBALITA 3 = Khassy Rada (credited, walang linya — huwag isulat, huwag tanggalin); TECHNICAL / TAGAPAGSULAT NG ISKRIP = Rodger Pacumba Jr.; DIRECTOR = Gwyneth Ashley Damasen.

**Historical vs new vs quarantined:**

- **Historical (hindi dinala):** Tagahabi ng Balita, aarangkada/makina/busina/horn, `PEPRENO MUNA` / `MULING AARANGKADA`, weaving brand, lumang jingle at lines, lumang kwento (Geronimo, KVSHS, DepEd grading, Kris Aquino), Ilokano greeting line, child-shaming beat ng teacher PSA. **(Ang LOCKED na D-Z-R-M 67.5 ang dala.)**
- **Dinala bilang craft:** house format, role map, KBP line, time-check slot, digit-by-digit frequency style.
- **Mula sa nakaraang BATINGAW (dinala, binago):** Batingaw ng Balita, kampana logo, break pair, sign-off family, tagapagbatingaw/kabatingaw. **Binago:** slogan (lumang `SA BAWAT TUNOG, KATOTOHANAN` → rhyming form), callsign (dating prop callsign → LOCKED na D-Z-R-M 67.5), bigkas ng frequency (house digit style), at inalis ang Pililla address.
- **Retired sa run na ito:** anumang town address (Pililla, Montalbeños) — walang demonym; `SA BAWAT TAHANAN` ang audience.
- **Quarantined at iniiwasan (verify sa bawat pass):** anumang "…Patrol"/"91.26"; C5 travel lexicon (kabiyahero, ruta, travel buddy, red light, horn-as-logo); C8 "Offline!"/"Tama muna pag-scroll"; C17 "Tatak-"; C9 "Kasama Ka"; C13 "Heto na!"/"LABAN, PILIPINAS!"; C18 "Walang preno, tuloy-tuloy"; C10 "nagmamasid sa… napapanahon"; C16 mapanuri-chain; C1/C18 game-show infomercial; at lahat ng exact lines sa benchmark §21. Ang kampana ay LOGO SA GILID — hindi in-story SFX (ang C2 school-bell ay theatrical, ibang function).
- Ang `X MUNA` na hugis ng break ay ang unibersal na pause/resume architecture ng corpus — malayo ang wording sa lumang `PEPRENO MUNA`; huwag i-drift pabalik sa vehicle family. Ang close callback ay gumagamit ng `TULOY` — malinis at ibang linya sa C18 na `tuloy-tuloy`; huwag isulat ang `tuloy-tuloy` kahit saan.

**Delivery flags (rehearsal items):** frequency string `SAIS-SYETE-PUNTO-SINGKO`; `TAGAPAGBATINGAW`; `KABATINGAW`; lahat ng rhymed lines (slogan halves, break tease, close callback); lahat ng sign-offs (pinaka-garbled recurring line ng corpus — i-drill); break promise line (`MANATILI SA TUNOG NG D-Z-R-M`); lahat ng unison lines (`LAHAT` = apat na boses; i-drill ang sabay). Tatlong-minsang pronunciation drill bago ang bawat ensayo.

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

**ANGKOR 1:** KAMPANA NG KATOTOHANAN,

**ANGKOR 2:** TUNOG SA BAWAT TAHANAN!

**STINGER**

**ANGKOR 1:** D-Z-R-M, SAIS-SYETE-PUNTO-SINGKO.

**LAHAT:** BATINGAW NG BALITA!

**PAGPASOK AT PAGBABA NG MUSIKANG PAMBUNGAD [UP AND UNDER]…**

**TUNOG NG ORASAN** (ISANG BEEP)

**ANGKOR 2:** ANG ORAS NATIN NGAYON AY ___ MINUTO MAKALIPAS ANG ___ NG HAPON.

**ANGKOR 2:** MAGANDANG HAPON, MGA TAGAPAKINIG!

**ANGKOR 1:** AT MAGANDANG HAPON SA BAWAT TAHANAN!

**ANGKOR 1:** ANG HIMPILANG ITO AY KASAPI NG K-B-P, KAPISANAN NG MGA BRODKASTER NG PILIPINAS.

**STINGER… PAGHINTO NG MUSIKA…**

**ANGKOR 1:** AKO ANG INYONG TAGAPAGBATINGAW NG BALITA, RAIN CALITES.

**STINGER**

**ANGKOR 2:** AT AKO NAMAN ANG INYONG KABATINGAW, CELINE ASOY.

**STINGER… PAGTULOY NG MUSIKA…**

**ANGKOR 2:** ANO KAYA ANG MGA KAGANAPAN NGAYONG HAPON?

**ANGKOR 1:** SA ULO NG MGA BALITA!

**STINGER… PAGPALIT NG BED NG BALITA [UP AND UNDER]…**

**ANGKOR 1:** [HEADLINE 1]

**STINGER**

**ANGKOR 2:** [HEADLINE 2]

**STINGER**

**ANGKOR 1:** ABA, MAINIT NA BALITA 'YAN!

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

**ANGKOR 2:** MAY SUSUNOD PA TAYONG KAGANAPAN — KAYA MANATILI SA INYONG TAHANAN!

**BUMPER:** PAPAHINGA MUNA ANG KAMPANA… PARA SA ISANG MAIKLING PAALALA!

**ANGKOR 1:** MANATILI SA TUNOG NG D-Z-R-M, BATINGAW NG BALITA — MAGBABALIK TAYO!

**STINGER… PAGPASOK NG BED NG PAALALA [UP AND UNDER]…**

**KARAKTER 1:** [INFOMERCIAL-SCENE]

**NARRATOR:** [INFOMERCIAL-FACT]

**NARRATOR:** [INFOMERCIAL-SOLUSYON]

**NARRATOR:** [INFOMERCIAL-CTA]

**AWIT:** [INFOMERCIAL-AWIT] (OPTIONAL — KUNG WALA, BURAHIN ANG LINYA)

**PAALALA:** [INFOMERCIAL-PAALALA] PAALALA MULA SA D-Z-R-M, BATINGAW NG BALITA.

**TUNOG NG BATINGAW… PAGBABA NG MUSIKA…** (ISANG HAMPAS NG KAMPANA)

**ANGKOR 1:** NAGBATINGAW MULI!

**ANGKOR 2:** KAMPANA NG KATOTOHANAN, TUNOG SA BAWAT TAHANAN!

**ANGKOR 1:** D-Z-R-M, SAIS-SYETE-PUNTO-SINGKO,

**LAHAT:** BATINGAW NG BALITA!

**PAGPASOK NG BED NG PALAKASAN [UP AND UNDER]…**

**ANGKOR 1:** PARA SA BALITANG PALAKASAN!

**ANGKOR 1:** [HEADLINE 3]. CARL ADLAWAN, ANO ANG BAGO SA PALAKASAN?

**TAGAPAGBALITA 2:** [SPORTS NA BALITA]. CARL ADLAWAN, NAGPATUNOG NG PALAKASAN.

**ANGKOR 1:** MARAMING SALAMAT, CARL!

**PAGPALIT NG BED NG TSISMISAN [UP AND UNDER]…**

**ANGKOR 2:** PARA SA BALITANG TSISMISAN!

**ANGKOR 2:** [HEADLINE 4]. TYRAH INARES, ANONG MERON SA TSISMISAN?

**TAGAPAGBALITA 1:** [SHOWBIZ NA BALITA]. TYRAH INARES, NAGPATUNOG NG TSISMISAN.

**ANGKOR 2:** MARAMING SALAMAT, TYRAH!

**STINGER… PAGPALIT NG MUSIKANG PAMBUNGAD [UP AND UNDER]…**

**ANGKOR 1:** MGA TAGAPAKINIG, IYAN ANG MGA BALITANG TINUNOG NG BATINGAW NGAYONG HAPON.

**ANGKOR 1:** AKO SI RAIN CALITES.

**ANGKOR 2:** AT AKO SI CELINE ASOY.

**ANGKOR 1:** ITO ANG…

**ANGKOR 2:** D-Z-R-M, SAIS-SYETE-PUNTO-SINGKO,

**LAHAT:** BATINGAW NG BALITA!

**ANGKOR 1:** KAMPANA NG KATOTOHANAN,

**ANGKOR 2:** TUNOG SA BAWAT TAHANAN!

**ANGKOR 2:** PAPAHINGA NA ANG KAMPANA…

**ANGKOR 1:** PERO SA BAWAT TAHANAN, TULOY ANG KATOTOHANAN.

**TUNOG NG BATINGAW… PAGBABA AT PAGHINTO NG MUSIKA…**
