# DIVISION-SCRIPT-DALUYONG — Daluyong ng Balita (STRUCTURE)

## A. Production Notes (hindi para sa ere)

**Status:** STRUCTURE / SKELETON — kompetisyon-day na nilalaman (balita, infomercial, orasan) ang mga placeholder. Huwag punan mula sa National news pool (Ormoc ATM scam, WPS cyanide, Middle East oil, Alcantara, Oscars 2026). **Walang kasalukuyang fact sheet** — gumawa ng isa (internally consistent na mga numero at pangalan) bago punan ang anumang balita o istatistika.

**Concept status:** PROPOSAL — hindi pa LOCKED. Sibling proposal: `DIVISION-CONCEPT-BATINGAW.md` (kampana) ang naunang panukala; pipili ang team ng ISA. Huwag paghaluin ang kampana at ang alon. Tingnan ang `DIVISION-CONCEPT-DALUYONG.md`; ilalapat ng user/team ang pag-apruba.

**Identity (fixed forms — walang variant drift):**

| Elemento | Exact form |
|---|---|
| Callsign | **D-Z-R-M** (**LOCKED**) |
| Frequency | 67.5 — binibigkas na `SAIS-SYETE-PUNTO-SINGKO` (**LOCKED**) |
| Program | **DALUYONG NG BALITA** |
| Slogan | **TULOY ANG AGOS, TULOY ANG KATOTOHANAN.** — schedule: open (split: A1 `TULOY ANG AGOS,` / A2 `TULOY ANG KATOTOHANAN!`) → return (A2, buo) → close (unison, buo) |
| Sonic logo | **TUNOG NG ALON** — isang wave-wash sample (~2–3 s); open, return, at close LANG (3×) |
| Audience | `MGA TAGAPAKINIG` — pangkalahatan; walang demonym, walang hometown (utos ng user) |
| Break pair | `PAHAWAK MUNA ANG DALUYONG…` / `MULING TULOY ANG DALUYONG!` |
| Sign-off family | `[NAME], AGOS NG [BALITA / PALAKASAN / TSIKAHAN].` (isang-word category swap) |
| Anchor roles | A1 `GABAY SA AGOS NG BALITA`; A2 `KASABAY SA AGOS` |

**Placeholder legend (verbatim tokens — huwag palitan ng kasingkahulugan):**

| Token | Kahulugan | Panuntunan sa pagpuno |
|---|---|---|
| `[HEADLINE 1]` | National hard news | **Reveal** shape: `[TOPIC], [RESULT STATE]!` — 8–14 salita, isang hininga |
| `[HEADLINE 2]` | Local hard news | Same reveal shape |
| `[HEADLINE 3]` | Sports | **Tease** — question-form na may `kaya`; WALANG iskor, walang panalo, walang pangalan ng mananalo |
| `[HEADLINE 4]` | Showbiz | **Tease** — walang outcome/resulta |
| `[NASYONAL NA BALITA]` | National body | 3 pangungusap; action-first lead; `Ayon sa…` sa ikalawang hininga; hedge ng alegasyon (`umano`/`diumano`); public advisory bago ang sign-off; verbalize numbers; gloss `X o Y`; ≤1 English token kada pangungusap. **Walang metaphor sa katawan ng balita — konsepto ay nasa frame lines lamang.** |
| `[LOKAL NA BALITA]` | Local body | Same compression + advisory |
| `[SPORTS NA BALITA]` | Sports body | News register + energy; local/Filipino angle; agency response |
| `[SHOWBIZ NA BALITA]` | Showbiz body | Tone shift (tsikahan register); facts clean; walang name confusion |
| `[INFOMERCIAL-SCENE]` | Dramatized scene | Hook (tunog o tanong, ~5 s) + problema; dignifying; 2–4 karakter; **walang child-shaming beat; HINDI game-show frame**; dito lang ang theatrical SFX ng araw |
| `[INFOMERCIAL-AWIT]` | Song | Opsyonal; empty line ready; kung wala, burahin ang AWIT line |
| `[INFOMERCIAL-FACT]` | Sourced statistic | Isang verified na numero + named source; glossed; never invent |
| `[INFOMERCIAL-SOLUSYON]` | Named entity | Named program/solusyon, hindi vague |
| `[INFOMERCIAL-CTA]` | Call to action | Verb + object + named entity |
| `[INFOMERCIAL-PAALALA]` | Closing PSA line | Isang linya; sinusundan ng nakasulat na station tag |
| `[SFX-KWENTO]` | Optional in-story SFX | Kung kakailanganin lang ng kuwento ng araw; hindi pre-chosen na kampana/pinto/pito |
| `[Q&A-TANONG]` / `[Q&A-SAGOT]` | Status Q&A (optional) | **Isang Q&A LAMANG sa buong broadcast** (sa local report); tanong sa status ng kuwento, pre-answerable; ang sagot ay may pangalawang sourced fact; isulat ang magkabilang panig sa iisang pahina |

**Bed map (5 beds — isang operator):**

| Bed | Label sa script | Kalidad |
|---|---|---|
| 1 | MUSIKANG PAMBUNGAD / PAGWAWAKAS | Warm newsroom; open + close (bookend) |
| 2 | BED NG BALITA | Steady, seryoso |
| 3 | BED NG PAALALA | Soft acoustic (infomercial zone) |
| 4 | BED NG PALAKASAN | Percussive, energetic |
| 5 | BED NG TSIKAHAN | Upbeat, sparkle accent |

- Stinger files: **S1 = STINGER NG ULO NG BALITA** (maikling drum hit — headline commas at ID beats); **S2 = STINGER NG SEAM** (riser/swoosh — block boundaries). Sa script, nakasulat nang bahay bilang `**STINGER**`; ang operator ang nagmamapa: headlines/ID = S1, seams/break = S2.
- `**TUNOG NG ALON**` = isang wave-wash (logo). Tatlong beses LANG: open, return, close.
- `**TUNOG NG ORASAN**` = isang beep — ang TANGING diegetic beep ng buong broadcast.
- **Ang infomercial zone ay ang pahinga ng alon:** walang `TUNOG NG ALON` sa loob ng PAALALA block (sinadyang konsepto — "PAHAWAK" ang daluyong).
- Beds duck under speech: `[UP AND UNDER]` sa bawat pagpasok ng bed. Walang music-only gap — walang bed na walang dialogue.

**Target rundown (~5:00):**

| Oras | Block | Band |
|---|---|---|
| 0:00–0:12 | Alon + three-layer ID (slogan → callsign+freq → program) | ID sa loob ng 20 s ✓ |
| 0:12–0:30 | Time check + isang beep, greeting, KBP line | |
| 0:30–0:50 | Paired intros + "kaya" hook + headline frame | |
| 0:50–1:05 | Headline block: frame → 4 items + stinger → handoff | first news 55–70 s ✓ |
| 1:05–1:35 | National report (Tyrah) + receipt | 3 sentences, 25–35 s |
| 1:35–2:05 | Local report (Carl) + optional Q&A + receipt | 3 sentences, 25–35 s |
| 2:05–2:20 | Tease-then-promise break loop | break band ≈ 2:05–2:45 |
| 2:20–3:05 | Infomercial (~45 s) | 40–50 s band ✓ |
| 3:05–3:15 | Re-entry: alon + bumper + ID + slogan | identity first |
| 3:15–3:50 | Sports (Carl) | ~35 s |
| 3:50–4:25 | Showbiz (Tyrah) | ~35 s |
| 4:25–4:48 | Close: recap → IDs → ID split → unison slogan → callback → alon + fade | 15–25 s (median ~19 s) ✓ |

**Role map:** ANGKOR 1 = Rain Calites (lead; slogan layer 1, ID, greeting, headline 1 at 3, national toss, reaction token, break tease, sports launch, close start at callback land); ANGKOR 2 = Celine Asoy (time check, greeting, KBP follow-through, slogan layer 2, headline 2 at 4, local toss + Q&A, break promise, return slogan, showbiz launch, close completion); TAGAPAGBALITA 1 = Tyrah Inares (national + showbiz); TAGAPAGBALITA 2 = Carl Adlawan (local + sports); TAGAPAGBALITA 3 = Khassy Rada (credited, walang linya — huwag isulat, huwag tanggalin); TECHNICAL + TAGAPAGSULAT NG ISKRIP = Rodger Pacumba Jr.; DIRECTOR = Gwyneth Ashley Damasen.

**Historical vs new vs quarantined:**

- **Historical (hindi dinala):** Tagahabi ng Balita, weaving brand, aarangkada/makina/busina/horn, `PEPRENO MUNA` / `MULING AARANGKADA`, `HATID ANG KAMALAYAN`, Ilokano greeting, lumang jingle, mga lumang kwento (Geronimo, KVSHS, DepEd grading, Kris Aquino), lumang headline/toss lines. **(Ang LOCKED na D-Z-R-M 67.5 ang dala.)**
- **New (proposal):** DZRM 67.5 (LOCKED), Daluyong ng Balita, slogan, alon logo, break pair, sign-off family, gabay/kasabay sa agos (neutral audience).
- **Quarantined at iniiwasan (verify sa bawat pass):** anumang "…Patrol"/"91.26"; C5 travel lexicon (kabiyahero, ruta, travel buddy, red light, busina-as-logo, biyahe/sakay/bangka — huwag magdagdag ng journey words sa water frame); C8 "Offline!"/"Tama muna pag-scroll"; C17 "Tatak-"; C9 "Kasama Ka"; C13 "Heto na!"/"LABAN, PILIPINAS!"; C18 "Walang preno, tuloy-tuloy"; C1 "Pilipinas… balitaan na!"/"Mabuhay ka!"/"Pahulaan"; C6 "Eksklusibo!"/"Padayon"; C10 "nagmamasid sa… napapanahon"; C15 theme/personas; C14 "Pilipinas, bayan, balita na!"; lahat ng exact lines sa benchmark §21; ang lahat ng linya ng sibling BATINGAW proposal (hindi mix ng dalawang konsepto).

**Delivery flags (rehearsal items — 3× pronunciation drill bago bawat ensayo):** ang frequency string `SAIS-SYETE-PUNTO-SINGKO`; `DALUYONG`; `PAHAWAK MUNA ANG DALUYONG`; ang slogan (split at unison); lahat ng sign-off (`AGOS NG…`); ang close callback. Ang sign-off at transition lines ang pinaka-garbled na recurring lines ng corpus — i-drill tulad ng opening. Tease-promise contract: ang teaser bago ang break ay dapat i-honor pagkatapos (sports → sports, showbiz → showbiz).

**Concept choice (isang pangungusap):** *DALUYONG NG BALITA* — ang himpilan bilang agos ng balita na may alon bilang tunog-tatak; pinili dahil may isang murang sonic asset at buong-loop ang sistema (PAHAWAK sa break → MULING TULOY → PAHAWAK NA… PERO TULOY PA RIN sa close) nang hindi sumasagasaan sa C5 travel family o sa sibling BATINGAW. (Audience: neutral — `MGA TAGAPAKINIG`.)

---

## B. On-Air Script

**HIMPILAN NG RADYO**
**D-Z-R-M 67.5**
**DALUYONG NG BALITA**
**ANGKOR 1:** Rain Calites
**ANGKOR 2:** Celine Asoy
**TAGAPAGBALITA 1:** Tyrah Inares
**TAGAPAGBALITA 2:** Carl Adlawan
**TAGAPAGBALITA 3:** Khassy Rada
**TECHNICAL:** Rodger Pacumba Jr.
**TAGAPAGSULAT NG ISKRIP:** Rodger Pacumba Jr.
**DIRECTOR:** Gwyneth Ashley Damasen

**TUNOG NG ALON** (ISANG WAVE-WASH — ANG SONIC LOGO)

**ANGKOR 1:** TULOY ANG AGOS,

**ANGKOR 2:** TULOY ANG KATOTOHANAN!

**STINGER**

**ANGKOR 1:** D-Z-R-M, SAIS-SYETE-PUNTO-SINGKO.

**STINGER**

**ANGKOR 1 AT 2:** DALUYONG NG BALITA!

**PAGPASOK AT PAGBABA NG MUSIKANG PAMBUNGAD [UP AND UNDER]…**

**TUNOG NG ORASAN** (ISANG BEEP)

**ANGKOR 2:** ANG ORAS NATIN NGAYON AY ___ MINUTO MAKALIPAS ANG ___ NG HAPON.

**ANGKOR 1:** MAGANDANG HAPON, LUZON!

**ANGKOR 2:** AT MAGANDANG HAPON, MGA TAGAPAKINIG!

**ANGKOR 1:** ANG HIMPILANG ITO AY KASAPI NG K-B-P, KAPISANAN NG MGA BRODKASTER NG PILIPINAS.

**STINGER**

**ANGKOR 1:** AKO ANG INYONG GABAY SA AGOS NG BALITA, RAIN CALITES.

**STINGER**

**ANGKOR 2:** AT AKO ANG INYONG KASABAY SA AGOS, CELINE ASOY.

**STINGER**

**ANGKOR 1:** ANO KAYA ANG DADALHIN NG AGOS NGAYONG HAPON?

**ANGKOR 1:** SA DALUYONG NG MGA BALITA!

**STINGER… PAGPALIT NG BED NG BALITA…**

**ANGKOR 1:** [HEADLINE 1]

**STINGER**

**ANGKOR 2:** [HEADLINE 2]

**STINGER**

**ANGKOR 1:** NAKU, DAPAT ITONG BANTAYAN NANG MABUTI!

**STINGER**

**ANGKOR 1:** [HEADLINE 3]

**STINGER**

**ANGKOR 2:** [HEADLINE 4]

**STINGER**

**ANGKOR 1:** SIMULAN NA NATIN SA UNANG BALITA!

**ANGKOR 1:** [HEADLINE 1]. TYRAH INARES, ANO ANG BUONG DETALYE?

**TAGAPAGBALITA 1:** [NASYONAL NA BALITA]. TYRAH INARES, AGOS NG BALITA.

**ANGKOR 1:** MARAMING SALAMAT, TYRAH!

**ANGKOR 2:** SAMANTALA, [HEADLINE 2]. CARL ADLAWAN, ANO ANG NANGYAYARI NGAYON?

**TAGAPAGBALITA 2:** [LOKAL NA BALITA]. CARL ADLAWAN, AGOS NG BALITA.

**ANGKOR 2:** (OPTIONAL — ISANG Q&A LAMANG SA BUONG BROADCAST) CARL, [Q&A-TANONG]?

**TAGAPAGBALITA 2:** [Q&A-SAGOT].

**ANGKOR 2:** MARAMING SALAMAT, CARL!

**STINGER… PAGBABA AT PAGHINTO NG MUSIKA…**

**ANGKOR 1:** PAGKATAPOS NG PAALALA, SASABAY TAYO SA PALAKASAN AT SA TSIKAHAN!

**BUMPER:** PAHAWAK MUNA ANG DALUYONG… PARA SA ISANG MAIKLING PAALALA!

**ANGKOR 2:** MAGBABALIK TAYO SA TUNOG NG D-Z-R-M!

**STINGER… PAGPASOK NG BED NG PAALALA [UP AND UNDER]…**

**KARAKTER 1:** [INFOMERCIAL-SCENE]

**NARRATOR:** [INFOMERCIAL-FACT]

**NARRATOR:** [INFOMERCIAL-SOLUSYON]

**NARRATOR:** [INFOMERCIAL-CTA]

**AWIT:** [INFOMERCIAL-AWIT] (OPTIONAL — KUNG WALA, BURAHIN ANG LINYA)

**PAALALA:** [INFOMERCIAL-PAALALA] PAALALA MULA SA D-Z-R-M, DALUYONG NG BALITA.

**STINGER… PAGHINTO NG MUSIKA…**

**TUNOG NG ALON** (ISANG WAVE-WASH)

**ANGKOR 1:** MULING TULOY ANG DALUYONG!

**ANGKOR 2:** TULOY ANG AGOS, TULOY ANG KATOTOHANAN!

**ANGKOR 1:** D-Z-R-M, SAIS-SYETE-PUNTO-SINGKO,

**ANGKOR 1 AT 2:** DALUYONG NG BALITA!

**PAGPASOK NG BED NG PALAKASAN [UP AND UNDER]…**

**ANGKOR 1:** PARA SA BALITANG PALAKASAN!

**ANGKOR 1:** [HEADLINE 3]. CARL ADLAWAN, ANONG NANGYAYARI SA PALAKASAN?

**TAGAPAGBALITA 2:** [SPORTS NA BALITA]. CARL ADLAWAN, AGOS NG PALAKASAN.

**ANGKOR 1:** MARAMING SALAMAT, CARL!

**PAGPALIT NG BED NG TSIKAHAN [UP AND UNDER]…**

**ANGKOR 2:** PARA SA BALITANG TSIKAHAN!

**ANGKOR 2:** [HEADLINE 4]. TYRAH INARES, ANO ANG BAGO SA TSIKAHAN?

**TAGAPAGBALITA 1:** [SHOWBIZ NA BALITA]. TYRAH INARES, AGOS NG TSIKAHAN.

**ANGKOR 2:** MARAMING SALAMAT, TYRAH!

**STINGER… PAGPALIT NG MUSIKANG PAMBUNGAD [UP AND UNDER]…**

**ANGKOR 1:** MGA TAGAPAKINIG, IYAN ANG MGA BALITANG DUMALOY SA ATIN NGAYONG HAPON.

**ANGKOR 1:** AKO SI RAIN CALITES.

**ANGKOR 2:** AT AKO SI CELINE ASOY.

**ANGKOR 1:** ITO ANG,

**STINGER**

**ANGKOR 1:** D-Z-R-M,

**ANGKOR 2:** SAIS-SYETE-PUNTO-SINGKO,

**ANGKOR 1 AT 2:** DALUYONG NG BALITA!

**ANGKOR 1 AT 2:** TULOY ANG AGOS, TULOY ANG KATOTOHANAN!

**ANGKOR 2:** PAHAWAK NA ANG DALUYONG NGAYONG HAPON…

**ANGKOR 1:** PERO TULOY PA RIN ANG AGOS NG KATOTOHANAN.

**TUNOG NG ALON… PAGBABA AT PAGHINTO NG MUSIKA…**
