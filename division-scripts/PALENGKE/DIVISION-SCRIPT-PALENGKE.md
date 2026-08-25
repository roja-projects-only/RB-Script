# DIVISION-SCRIPT-PALENGKE

## TALA NG PRODUKSIYON — hindi para sa ere

**Status:** COMPLETE NEW SCRIPT — may mga butas para sa araw ng kompetisyon (news at advocacy content lamang ang placeholder).

- **Station ID: LOCKED** — D-Z-R-M 67.5 (`D-Z-R-M`, `SAIS-SYETE-PUNTO-SINGKO`). Hindi ito pinapalitan.
- **Concept: PROPOSAL** — ang program title, slogan, at metaphor ay panukala hangga't hindi nila-lock ang team (tingnan ang `DIVISION-CONCEPT-PALENGKE.md`).
- **AWIT: PLACEHOLDER ONLY (no generated lyrics)** — ang mga slot na `[AWIT-THEME]`, `[INFOMERCIAL-AWIT]`, `[AWIT-CLOSE]` ay mga butas para sa track na mayroon o pipiliin ng team. Huwag punan ng lyrics.

### Identity block (fixed forms — walang variant drift)

| | |
|---|---|
| Callsign (LOCKED) | **D-Z-R-M** |
| Frequency (LOCKED) | **67.5** → `SAIS-SYETE-PUNTO-SINGKO` |
| Program (PROPOSAL) | **PALENGKE NG BALITA** |
| Slogan (PROPOSAL) | **TAMANG TIMBANG, SARIWANG BALITA.** (open: split · return: A2, buo · close: LAHAT) |
| Sonic logo | **TUNOG NG PALENGKE** — bed na 2–3 s: bulong ng tao, tawag ng tindero, tok-tok ng kahoy (fallback: tok-tok lamang). File label: `palengke-logo.wav`. Open, return, close LANG — tahimik sa infomercial zone. |
| Audience | **MGA TAGAPAKINIG** — pangkalahatan; walang demonym, walang hometown (utos ng user) |
| Break pair | `SASARHAN MUNA NATIN ANG MGA PANINDA…` / `MULING BUKAS ANG PALENGKE NG BALITA!` |
| Break frame | **LIBRENG TIKIM** — ang infomercial ay isang libreng tikim sa loob ng palengke |
| Category words | **LARO** (sports) · **TANGHALAN** (showbiz) |
| Sign-off family | `[NAME], MAY PANINDA SA BALITA.` / `…SA LARO.` / `…SA TANGHALAN.` |
| Anchor roles | A1 `TAGATIMBANG NG BALITA`; A2 `KATINDA` |
| Station tag (PAALALA) | `ISANG PAAALALA MULA SA PALENGKE NG D-Z-R-M.` |
| Diegetic realism | **Walang beep sa buong show.** Ang isang diegetic na tunog ay ang tok-tok sa loob ng `TUNOG NG PALENGKE` (ang tunog ng palengke mismo). |

**Drill items (bago ang bawat ensayo):** `SAIS-SYETE-PUNTO-SINGKO` (3×), `TANGHALAN`, `LARO`, at ang close callback na `PERO BUKAS, MULING BUBUKAS ANG D-Z-R-M` — ang BUKAS/BUBUKAS alliteration ay ang pinaka-garbled-class na linya sa corpus.

### Placeholder legend

| Token | Kahulugan | Paano punan |
|---|---|---|
| `[HEADLINE 1]` | National | **Reveal**: `[PAKSA], [RESULTADONG ESTADO]!` — 8–14 salita |
| `[HEADLINE 2]` | Local | **Reveal**: parehong anyo |
| `[HEADLINE 3]` | Sports | **Tease lang** — walang iskor o panalo; maaaring question-form na may `kaya` |
| `[HEADLINE 4]` | Showbiz | **Tease lang** — walang resulta; question-form na may `kaya` |
| `[NASYONAL NA BALITA]` | National body | 3 pangungusap; action-first lead; `Ayon sa…` sa ikalawang hininga; `umano`/`diumano` sa alegasyon; public advisory bago ang sign-off |
| `[LOKAL NA BALITA]` | Local body | Pareho; nahahati sa dalawang bahagi para sa mid-report Q&A (unang bahagi = ulat; ikalawang bahagi = sagot sa tanong ng angkor) |
| `[SPORTS NA BALITA]` | Sports body | News register + energy; may lokal/Pinoy angle; advisory bago ang sign-off |
| `[SHOWBIZ NA BALITA]` | Showbiz body | Tone shift (mas magaan ang salita); malinis na pangalan |
| `[INFOMERCIAL-SCENE]` | Eksena | May dignidad; 2–4 na karakter; **walang child-shaming** (ang sistema ang kontrabida, hindi ang bata); day-specific SFX dito lamang |
| `[INFOMERCIAL-FACT]` | Estadistika | May source; huwag mag-imbento; i-verify ng dalawang beses |
| `[INFOMERCIAL-SOLUSYON]` | Pinangalanang solusyon | Named entity (programa/ahensya/batas) |
| `[INFOMERCIAL-CTA]` | Call to action | Verb + object + named entity |
| `[INFOMERCIAL-PAALALA]` | PSA line | Isang pangungusap; sinusundan ng nakasulat na station tag |
| `[AWIT-THEME]` | Opening theme slot | **Placeholder only — no lyrics** |
| `[INFOMERCIAL-AWIT]` | Infomercial song slot | **Placeholder only — no lyrics** |
| `[AWIT-CLOSE]` | Closing reprise slot | **Placeholder only — no lyrics** |
| `[SFX-KWENTO]` | In-story SFX (optional) | Kung kailangan lang ng kuwento ng araw; diegetic (tunog sa loob ng kuwento), HINDI theatrical; ang theatrical ay nasa `[INFOMERCIAL-SCENE]` lamang |
| `___ MINUTO MAKALIPAS ANG ___ NG HAPON` | Orasan | Blangkong oras — punan sa araw ng kompetisyon |

**Stinger labels (self-describing — alam ng TD kung aling file):** `STINGER: SLOGAN` · `STINGER: HIMPILAN` · `STINGER: ULO NG BALITA` · `STINGER: PALIT` · `STINGER: PAGBALIK` · `STINGER: PAMAMAALAM`. Isang file bawat label; boundary-only (wala sa loob ng ulat). Ang bare **STINGER** (walang label) ay ang generic boundary accent — isang file lamang (maikling percussive hit); ang mga labeled na STINGER ay specific na files.

### Bed map (5 beds — kaya ng isang student operator)

| Bed | Pwesto | Karakter |
|---|---|---|
| **PAMBUNGAD NA BED** | open (ID, greeting, headlines) at close (bookend) | bukas at mainit; swell-and-fade sa close |
| **BALITA BED** | dalawang hard-news reports | mabilis, neutral news |
| **TIKIM BED** | infomercial zone (LIBRENG TIKIM) | magaan, mainit — HINDI ang logo |
| **LARO BED** | sports | pinakamabilis, percussive |
| **TANGHALAN BED** | showbiz | sparkling, playful |

Lahat ng pagpasok ng bed ay `…PAGPASOK… PAGBABA…` (UP AND UNDER) — bumababa ang musika sa ilalim ng pananalita. Walang music-only gap na higit sa 5 s.

### Target rundown (≈5:00 — drill sa stopwatch)

| Oras | Segment | Nagsasalita | Bed | Cues |
|---|---|---|---|---|
| 0:00–0:12 | Sonic logo + open hook + slogan (split) | A1 / A2 | PAMBUNGAD | `TUNOG NG PALENGKE`, `STINGER: SLOGAN` |
| 0:10–0:22 | ID: callsign + freq + program | A1 / A2 / A1 AT 2 | PAMBUNGAD | `STINGER: HIMPILAN` |
| 0:22–0:32 | AWIT slot + time check | (musika) / A2 | PAMBUNGAD | `AWIT: [AWIT-THEME]`, stinger |
| 0:32–0:50 | Greeting + KBP + paired intros | A1 / A2 | PAMBUNGAD | `STINGER: HIMPILAN` |
| 0:50–1:10 | Headlines (frame + 4 items + handoff) | A1 / A2 | PAMBUNGAD → BALITA | 4× `STINGER: ULO NG BALITA` |
| 1:10–1:45 | National news (toss → report → receipt) | A1, T1 | BALITA | `STINGER: PALIT` |
| 1:45–2:25 | Local news + **one Q&A** | A2, T2 | BALITA | `STINGER: PALIT` |
| 2:25–2:38 | Tease + promise + break-in bumper | A1 / A2 | BALITA → TIKIM | `STINGER: PALIT` |
| 2:38–3:30 | Infomercial (LIBRENG TIKIM) + AWIT + PAALALA | K1–K4 | TIKIM | hook `TIKIM! LIBRENG TIKIM!`, `AWIT: [INFOMERCIAL-AWIT]`, `STINGER: PAGBALIK` |
| 3:30–3:40 | Re-entry (identity + slogan) | BUMPER / A2 | PAMBUNGAD (logo echo) | `TUNOG NG PALENGKE`, `STINGER: PAGBALIK` |
| 3:40–4:12 | Sports (launch → toss → report → receipt) | A1, T2 | LARO | `STINGER: PALIT` |
| 4:12–4:44 | Showbiz (launch → toss → report → receipt) | A2, T1 | TANGHALAN | `STINGER: PALIT` |
| 4:44–5:00 | Close: recap → IDs → unison → callback → fade | A1 / A2 / A1 AT 2 / LAHAT | PAMBUNGAD | `STINGER: PAMAMAALAM`, `TUNOG NG PALENGKE`, `AWIT: [AWIT-CLOSE]` |

### Role map

| Role | Pangalan | Sa ere |
|---|---|---|
| ANGKOR 1 | Rain Calites | `TAGATIMBANG NG BALITA` |
| ANGKOR 2 | Kate Ashley Asoy (Celine Asoy) | `KATINDA` |
| TAGAPAGBALITA 1 | Tyrah Dichos (Tyrah Inares) | National + showbiz |
| TAGAPAGBALITA 2 | Carl Evans Adlawan (Carl Adlawan) | Local + sports |
| TAGAPAGBALITA 3 | Rheannes Kassandra Rada (Khassy Rada) | **Credited, silent** — huwag isulat sa ere, huwag tanggalin |
| TECHNICAL | Rodger Pacumba Jr. | — |
| TAGAPAGSULAT NG ISKRIP | Rodger Pacumba Jr. | — |
| DIRECTOR | Gwyneth Ashley Damasen | — |

`LAHAT:` = apat na boses (ANGKOR 1–2 + TAGAPAGBALITA 1–2). Si Khassy Rada ay credited, silent.

### Dissimilarity note — kung ano ang sadyang HINDI dinala

**Mula sa lumang script (`ORIGINAL-SCRIPT.md`):** retired ang *Tagahabi ng Balita*, weaving brand, aarangkada/makina/busina, `PEPRENO`/`MULING AARANGKADA`/`AARANGKADA NA`, lahat ng lumang jingle, ang `ITO ANG…` cadence, `SA ULO NG MGA NAGBABAGANG BALITA`, `I-CHIKA MO NA`, `CHISMIS NA WALANG KAPARES`, `BALITAANG PALABAN`, `MONTALBEÑOS, IYAN ANG MGA BALITANG HATID NG UMAARANGKADANG ISTASYON`, `KAAGAPAY…`/`KATUWANG…`, TUNOG NG ORASAN at mga in-story SFX ng lumang kuwento, Ilokano greeting, lumang kwento (Geronimo, KVSHS, DepEd grading, Kris Aquino), child-shaming beat. **Pinanatili:** ang LOCKED na D-Z-R-M 67.5, house format (labels, ALL CAPS, cue style), cast, neutral na audience (`MGA TAGAPAKINIG`), standard na KBP line, at ang slot functions ng National spine (open → headlines → 2 hard news → infomercial → sports → showbiz → close).

**Mula sa mga kapatid na proposal (TALA, DALUYONG, BATINGAW, BATINGAW-2, HIMIG):** walang kampana/alon/tala/himig; walang prop callsigns (D-Z-M-T, D-W-A-L, D-Z-P-L, D-W-H-M) — ang LOCKED na D-Z-R-M 67.5 ang ginamit; walang break verbs na `papahinga`/`pahawak`/`huwag mawala`/`magpapalit` (ang atin: `sasarhan`/`muling bukas`); walang category words na `palakasan`/`tsikahan`/`tsismisan`/`palaro`/`showbiz` (ang atin: `LARO`/`TANGHALAN`); walang kanilang slogan/rhyme family.

**Mula sa National corpus (§21):** wala — walang "Patrol"/"91.26", walang C5 travel, C8 offline, C17 Tatak-, C13 Heto na, C15 Tindahan ni Nena, o anumang exact line mula sa quarantine list.

**AWIT:** ang tatlong slots ay **placeholder-only** — `[AWIT-THEME]`, `[INFOMERCIAL-AWIT]`, `[AWIT-CLOSE]`. Walang lyrics na bubuuin; ang identity ay dala ng spoken slogan, unison lines, logo, at beds.

---

# PALENGKE NG BALITA — ISKRIP SA ERE

**HIMPILAN NG RADYO**
**D-Z-R-M 67.5**
**PALENGKE NG BALITA**
**ANGKOR 1:** Rain Calites
**ANGKOR 2:** Kate Ashley Asoy (Celine Asoy)
**TAGAPAGBALITA 1:** Tyrah Dichos (Tyrah Inares)
**TAGAPAGBALITA 2:** Carl Evans Adlawan (Carl Adlawan)
**TAGAPAGBALITA 3:** Rheannes Kassandra Rada (Khassy Rada)
**TECHNICAL:** Rodger Pacumba Jr.
**TAGAPAGSULAT NG ISKRIP:** Rodger Pacumba Jr.
**DIRECTOR:** Gwyneth Ashley Damasen

**TUNOG NG PALENGKE…**

**ANGKOR 1:** BUKAS NA ANG PALENGKE NG BALITA!

**STINGER: SLOGAN**

**ANGKOR 1:** TAMANG TIMBANG,

**ANGKOR 2:** SARIWANG BALITA!

**STINGER: HIMPILAN**

**ANGKOR 1:** D-Z-R-M,

**ANGKOR 2:** SAIS-SYETE-PUNTO-SINGKO,

**ANGKOR 1 AT 2:** PALENGKE NG BALITA!

**AWIT:** [AWIT-THEME]

**STINGER… PAGBABA NG MUSIKA…**

**ANGKOR 2:** ANG ORAS NGAYON: \_\_\_ MINUTO MAKALIPAS ANG \_\_\_ NG HAPON. AT SARIWA PA RIN ANG ATING MGA PANINDA.

**PAGPASOK AT PAGBABA NG PAMBUNGAD NA MUSIKA…**

**ANGKOR 1:** MGA TAGAPAKINIG, MAGANDANG HAPON PO SA INYONG LAHAT!

**ANGKOR 2:** MALIGAYANG PAGDATING SA PALENGKE NG BALITA!

**STINGER… PAGHINTO NG MUSIKA…**

**ANGKOR 1:** ANG HIMPILANG ITO AY KASAPI NG K-B-P, KAPISANAN NG MGA BRODKASTER NG PILIPINAS.

**STINGER… PAGTULOY NG MUSIKA…**

**ANGKOR 1:** AKO ANG INYONG TAGATIMBANG NG BALITA, RAIN CALITES.

**STINGER**

**ANGKOR 2:** AT AKO ANG INYONG KATINDA SA PALENGKE NG BALITA, CELINE ASOY.

**STINGER: ULO NG BALITA**

**ANGKOR 1:** NARITO NA ANG MGA SARIWANG PANINDA NGAYONG HAPON!

**ANGKOR 1:** [HEADLINE 1]

**STINGER**

**ANGKOR 2:** [HEADLINE 2]

**STINGER**

**ANGKOR 1:** MAINIT NA PANINDA 'YAN!

**STINGER**

**ANGKOR 1:** [HEADLINE 3]

**STINGER**

**ANGKOR 2:** [HEADLINE 4]

**STINGER**

**ANGKOR 1:** SIMULAN NATIN SA UNANG PANINDA!

**STINGER: PALIT… PAGPALIT NG MUSIKA…**

**ANGKOR 1:** [HEADLINE 1]. TYRAH INARES, ANO ANG BUONG DETALYE?

**STINGER**

**TAGAPAGBALITA 1:** [NASYONAL NA BALITA]

**STINGER**

**TAGAPAGBALITA 1:** TYRAH INARES, MAY PANINDA SA BALITA.

**STINGER**

**ANGKOR 1:** SALAMAT, TYRAH INARES.

**ANGKOR 2:** SAMANTALA, PARA SA LOKAL NA PANINDA — [HEADLINE 2]. CARL ADLAWAN, ANO ANG BUONG DETALYE?

**STINGER**

**TAGAPAGBALITA 2:** [LOKAL NA BALITA] *(unang bahagi)*

**STINGER**

**ANGKOR 2:** AT CARL, ANO ANG DAPAT GAWIN NG MGA TAGAPAKINIG?

**STINGER**

**TAGAPAGBALITA 2:** [LOKAL NA BALITA] *(ikalawang bahagi — sagot sa tanong ng angkor)*

**STINGER**

**TAGAPAGBALITA 2:** CARL ADLAWAN, MAY PANINDA SA BALITA.

**STINGER**

**ANGKOR 2:** SALAMAT, CARL ADLAWAN.

**STINGER… PAGBABA AT PAGHINTO NG MUSIKA…**

**ANGKOR 1:** MAY PANGHULING PANINDA PA TAYO NGAYONG HAPON — SA LARO, AT SA TANGHALAN!

**ANGKOR 2:** PERO BAGO IYON, MAY LIBRENG TIKIM ANG PALENGKE NG D-Z-R-M.

**BUMPER:** SASARHAN MUNA NATIN ANG MGA PANINDA — PARA SA ISANG LIBRENG TIKIM NA PAAALALA.

**PAGPASOK NG TIKIM BED…**

**KARAKTER 1:** TIKIM! LIBRENG TIKIM!

**KARAKTER 2:** [INFOMERCIAL-SCENE] *(unang eksena: ang problema — may dignidad, walang child-shaming)*

**PAGBAGO NG MUSIKA…**

**KARAKTER 3:** [INFOMERCIAL-SCENE] *(ikalawang eksena: ang tugon)*

**STINGER… PAGHINA AT PAGHINTO NG MUSIKA…**

**KARAKTER 1:** [INFOMERCIAL-FACT]

**KARAKTER 1:** [INFOMERCIAL-SOLUSYON]

**KARAKTER 1:** [INFOMERCIAL-CTA]

**AWIT:** [INFOMERCIAL-AWIT]

**STINGER**

**PAALALA:** [INFOMERCIAL-PAALALA] ISANG PAAALALA MULA SA PALENGKE NG D-Z-R-M.

**STINGER: PAGBALIK… PAGPASOK NG PAMBUNGAD NA MUSIKA…**

**BUMPER:** MULING BUKAS ANG PALENGKE NG BALITA — D-Z-R-M, SAIS-SYETE-PUNTO-SINGKO!

**TUNOG NG PALENGKE… PAGBABA…**

**ANGKOR 2:** TAMANG TIMBANG, SARIWANG BALITA.

**STINGER: PALIT… PAGPASOK NG LARO BED…**

**ANGKOR 1:** PARA SA BALITANG LARO!

**STINGER**

**ANGKOR 1:** [HEADLINE 3]. CARL ADLAWAN, ANO ANG BUONG DETALYE?

**STINGER**

**TAGAPAGBALITA 2:** [SPORTS NA BALITA]

**STINGER**

**TAGAPAGBALITA 2:** CARL ADLAWAN, MAY PANINDA SA LARO.

**STINGER**

**ANGKOR 1:** SALAMAT, CARL ADLAWAN.

**STINGER: PALIT… PAGPALIT NG MUSIKA… PAGPASOK NG TANGHALAN BED…**

**ANGKOR 2:** AT PARA SA HULING PANINDA — ANG TANGHALAN!

**STINGER**

**ANGKOR 2:** [HEADLINE 4]. TYRAH INARES, ANO ANG BUONG DETALYE?

**STINGER**

**TAGAPAGBALITA 1:** [SHOWBIZ NA BALITA]

**STINGER**

**TAGAPAGBALITA 1:** TYRAH INARES, MAY PANINDA SA TANGHALAN.

**STINGER**

**ANGKOR 2:** SALAMAT, TYRAH INARES.

**STINGER… PAGPALIT NG MUSIKA… PAGPASOK NG PAMBUNGAD NA MUSIKA…**

**ANGKOR 1:** MGA TAGAPAKINIG, IYAN PO ANG MGA PANINDANG INIHANDOG NG PALENGKE NG BALITA SA ARAW NA ITO.

**STINGER: PAMAMAALAM**

**ANGKOR 1:** AKO ANG INYONG TAGATIMBANG, RAIN CALITES.

**STINGER**

**ANGKOR 2:** AT AKO ANG INYONG KATINDA, CELINE ASOY.

**STINGER**

**ANGKOR 1:** D-Z-R-M.

**ANGKOR 2:** SAIS-SYETE-PUNTO-SINGKO.

**ANGKOR 1 AT 2:** PALENGKE NG BALITA!

**STINGER**

**LAHAT:** TAMANG TIMBANG, SARIWANG BALITA!

**STINGER…**

**ANGKOR 1:** SASARA NA ANG PALENGKE NGAYONG HAPON — PERO BUKAS, MULING BUBUKAS ANG D-Z-R-M PARA SA INYO.

**TUNOG NG PALENGKE… PAGBABA AT PAGHINTO NG MUSIKA…**

**AWIT:** [AWIT-CLOSE]

*(fade)*
