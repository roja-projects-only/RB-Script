# PULSO — D-Z-R-M 67.5

## PRODUCTION NOTES (hindi para sa ere)

- **Status:** COMPLETE NEW SCRIPT — competition-day holes only (headlines, news bodies, infomercial content, clock numbers)
- **Station ID: LOCKED** — D-Z-R-M 67.5 (`D-Z-R-M`, `SAIS-SYETE-PUNTO-SINGKO`). Hindi ito pinapalitan.
- **Concept status: PROPOSAL** — program title (PULSO), slogan, at metaphor ay panukala hangga't hindi inaaprubahan ng team. Ang station ID lang ang LOCKED.
- **AWIT: PLACEHOLDER ONLY (no generated lyrics)** — `[AWIT-THEME]`, `[INFOMERCIAL-AWIT]`, `[AWIT-CLOSE]`. Huwag gumawa ng sariling awit. Mag-drop ng track na mayroon na o kukunin pa lang ng team. Ang identidad ay dala ng slogan, unison lines, heartbeat logo, stingers, at beds — hindi ng awit.
- **Audience address:** generic ("mga kababayan") — walang ipinapalagay na hometown o rehiyonal na audience sa kahilingan ng user.

### Identity block (fixed forms — huwag baguhin kahit isang salita)

| Slot | Fixed form |
|---|---|
| Callsign / frequency (LOCKED) | `D-Z-R-M` / `SAIS-SYETE-PUNTO-SINGKO` |
| Program title | `PULSO` |
| Slogan | `TUNAY ANG PINTIG, TUNAY ANG BALITA.` |
| Money line (unison, open at close) | `PULSOHAN NATIN ANG BALITA!` |
| Sonic logo | `TUNOG NG TIBOK NG PUSO` — 3 tibok sa open; 2 sa re-entry; mahina at humihina sa close. Gagamitin LANG sa mga posisyong ito. |
| Sign-off skeleton | `[PANGALAN], PULSO SA [BALITA / PALIGSAHAN / ALIWAN].` |

### Placeholder legend (gamitin ang tokens verbatim)

| Token | Ano | Paano punan |
|---|---|---|
| `[HEADLINE 1]` | National hard news | Reveal — `[TOPIC], [RESULT STATE]!` 8–14 salita, isang hininga, isang stinger bawat isa |
| `[HEADLINE 2]` | Local hard news | Same reveal form |
| `[HEADLINE 3]` | Sports | **Tease** — walang score/winner; pwede question form ("sino kaya…?") |
| `[HEADLINE 4]` | Showbiz | **Tease** — walang reveal |
| `[NASYONAL NA BALITA]` | National body | 3 pangungusap, 25–35 s; action-first lead; `Ayon sa…` sa ikalawang hininga; advisory bago ang sign-off; hedge ng `umano`/`diumano` |
| `[LOKAL NA BALITA]` | Local body | Same |
| `[SPORTS NA BALITA]` | Sports body | News register + energy; agency response; ≤35 s |
| `[SHOWBIZ NA BALITA]` | Showbiz body | Tone shift via lexicon; light |
| `[INFOMERCIAL-SCENE]` | Scene dialogue (KARAKTER 1–3) | 2–4 characters; dignifying; walang child-shaming; huwag i-clone ang game-show frame (C1/C18); theatrical SFX pinapayagan LANG dito |
| `[INFOMERCIAL-FACT]` | Statistic | May source; i-verify nang dalawang beses; huwag mag-imbento |
| `[INFOMERCIAL-SOLUSYON]` | Named solution | May pangalan ang entity/program |
| `[INFOMERCIAL-CTA]` | Call to action | Verb + object (hal. "I-report ang…", "Sama-samang suportahan ang…") |
| `[INFOMERCIAL-PAALALA]` | PSA line | Ang mensahe mismo; ang station tag ay nakasulat na kasunod |
| `[AWIT-THEME]` / `[INFOMERCIAL-AWIT]` / `[AWIT-CLOSE]` | Song slots | **Empty placeholders — no lyrics** |
| `[SAGOT SA TANONG]` | Q&A answer | 1 pangungusap, isusulat kasama ng body sa araw ng kontes (optional) |
| `___` | Clock numbers | Oras sa araw ng kontes |

Toss shape: `[HEADLINE]. [PANGALAN NG REPORTER], ANO ANG BUONG DETALYE?` → body → sign-off → `SALAMAT, [PANGALAN].`
Gloss technique para sa English tokens sa bodies: "cyanide o nakalalasong kemikal" — isang English token kada pangungusap sa news body.

### Bed map (5 beds — 1 operator)

| Bed | Pangalan | Saan |
|---|---|---|
| B1 | PAMBUNGAD / PANAPOS | Open (after AWIT) at close (reprise — sonic bookend) |
| B2 | BALITA | National at local reports |
| B3 | PAALALA | Infomercial zone |
| B4 | PALIGSAHAN | Sports (pinakamabilis, percussive) |
| B5 | ALIWAN | Showbiz (light, glamorous) |

**UP AND UNDER (≥16/18 sa corpus):** bawat bed entry = swell in → duck under speech → hold → swell out. Hindi kailanman papatayin ang bed habang may dialogue; walang music-only gaps (walang segment na walang boses sa taas ng bed).

### SFX inventory

- Sonic logo (heartbeat): 3 gamit total — open, re-entry, close. Hindi lalagpas.
- Isang diegetic beep: time check LANG. (At most one per show.)
- Stingers: boundary-only — 1 per headline, 1 per segment change, 1 sa break-in, 1 sa return, 1 sa close. Walang stinger sa loob ng reporter blocks.
- Cue labels ay self-describing: `[STINGER-BALITA]`, `[STINGER-PALIGSAHAN]`, `[STINGER-ALIWAN]` — hindi hulaan ng operator.
- Close: crescendo (pagt aas ng B1) → fade to silence.

### Target rundown (~5:00)

| Oras | Segment | Speaker |
|---|---|---|
| 0:00–0:10 | Heartbeat logo → slogan → split ID → unison title | A1, A2, LAHAT |
| 0:10–0:18 | `AWIT: [AWIT-THEME]` (empty slot; bed B1 kung walang track) | — |
| 0:18–0:35 | Time check + beep, greeting, KBP line | A2, A1 |
| 0:35–0:48 | Paired intros | A1, A2 |
| 0:48–1:05 | Headlines ×4 (stingered, alternating) | A1, A2 |
| 1:05–1:55 | National report + Q&A | TP1 (Tyrah), A2 |
| 1:55–2:30 | Local report | TP2 (Carl), A1 |
| 2:30–2:40 | Tease + bumper | A1, A2, BUMPER |
| 2:40–3:25 | Infomercial (45 s) | KARAKTER 1–3, PAALALA |
| 3:25–3:35 | Re-entry (heartbeat + identity) | A2 |
| 3:35–4:10 | Sports | A1, TP2 (Carl) |
| 4:10–4:40 | Showbiz | A2, TP1 (Tyrah) |
| 4:40–5:00 | Close: recap → IDs → unison → slogan → fade | A1, A2, LAHAT |

First news at ~1:05 (target 55–70 s). Advocacy ~45 s. Soft block ~35 s bawat isa. Close ~20 s.

### Role map

| Role | On-air name | Segment |
|---|---|---|
| ANGKOR 1 | Rain Calites | H1, H3; toss national + sports; half ng close |
| ANGKOR 2 | Celine Asoy | H2, H4; toss local + showbiz; Q&A; closing slogan |
| TAGAPAGBALITA 1 | Tyrah Inares | National, Showbiz |
| TAGAPAGBALITA 2 | Carl Adlawan | Local, Sports |
| TAGAPAGBALITA 3 | Khassy Rada | **Credited, silent** — huwag isulat sa ere, huwag i-drop nang walang pahintulot |
| TECHNICAL | Rodger Pacumba Jr. | Operator |
| TAGAPAGSULAT NG ISKRIP | Rodger Pacumba Jr. | — |
| DIRECTOR | Gwyneth Ashley Damasen | — |

### Dissimilarity note (ano ang sadyang HINDI dinala mula sa lumang script)

Hindi dinala mula sa `ORIGINAL-SCRIPT.md`: program title na *Tagahabi ng Balita* at weaving vocabulary; lahat ng vehicle overlay (aarangkada, biyahe, busina, makina ng sasakyan); `PEPRENO MUNA` / `MULING AARANGKADA`; ang opener cadence na "ITO ANG… → stuttered ID → unison title → busina → AARANGKADA NA"; ang `HALINA'T MAGLAKBAY…` at `HANDOG PARA SA BAYAN…` na awit; ang `KAAGAPAY NA SUBOK SA PAGHABI…` / `TATAK NG LEHITIMONG SERBISYO…` na intros; `SA ULO NG MGA NAGBABAGANG BALITA`; `PARA SA UNANG BALITA…` / `MAGHAHATID NG BALITA` toss; `BALITAANG PALABAN` / `I-CHIKA MO NA` / `CHISMIS NA WALANG KAPARES`; `MUNTING PAALALA MULA SA`; ang `MONTALBEÑOS, IYAN ANG…` na close line; ang teacher-PSA na may child-shaming beat; ang Ilokano/Luzon greeting at ang lumang clock phrasing.

Distinct din sa mga kapatid na draft: hindi PALENGKE (market/timbang), HIMIG (awit), TALA (bituin), DALUYONG (alon), BATINGAW (kampana). Ang PULSO ang pangalawang draft na nasa tamang station (D-Z-R-M 67.5); sa kasalukuyang run, lahat ng kapatid na draft ay nasa LOCKED na station na rin (pinalitan na ang mga dating imbentong callsign).

---

## ANG ISKRIP

**HIMPILAN NG RADYO**
**D-Z-R-M 67.5**
**PULSO**

**ANGKOR 1:** Rain Calites
**ANGKOR 2:** Celine Asoy
**TAGAPAGBALITA 1:** Tyrah Inares
**TAGAPAGBALITA 2:** Carl Adlawan
**TAGAPAGBALITA 3:** Khassy Rada (credited, silent)
**TECHNICAL:** Rodger Pacumba Jr.
**TAGAPAGSULAT NG ISKRIP:** Rodger Pacumba Jr.
**DIRECTOR:** Gwyneth Ashley Damasen

---

**TUNOG NG TIBOK NG PUSO (TATLONG TIBOK)**

**ANGKOR 1:** TUNAY ANG PINTIG, TUNAY ANG BALITA.

**STINGER… PAGPASOK NG MUSIKA…**

**ANGKOR 1:** D-Z-R-M,
**ANGKOR 2:** SAIS-SYETE-PUNTO-SINGKO,
**LAHAT:** PULSO! PULSOHAN NATIN ANG BALITA!

**AWIT:** [AWIT-THEME]

**PAGPASOK AT PAGBABA NG PAMBUNGAD NA MUSIKA (BED 1: PAMBUNGAD)…**

**TUNOG NG BEEP…**

**ANGKOR 2:** MGA KABABAYAN, \_\_\_ NA NG HAPON — NAKAHANDA TAYONG PULSUHIN ANG BAWAT NAGAGANAP, DITO SA D-Z-R-M, SAIS-SYETE-PUNTO-SINGKO.

**ANGKOR 1:** MABUTING HAPON SA INYONG LAHAT, MGA KABABAYAN, SAAN MAN KAYO NAKIKINIG. BILANG KASAPI NG KAPISANAN NG MGA BRODKASTER NG PILIPINAS, ANG K-B-P, IPINAPANGAKO NAMIN: TUNAY ANG PINTIG, TUNAY ANG BALITA.

**ANGKOR 1:** AKO SI RAIN CALITES, ANG INYONG KASAMA SA PAGPULSO NG ARAW.

**ANGKOR 2:** AT AKO SI CELINE ASOY, KASABAY NINYO SA PINTIG NG BAWAT BALITA.

**STINGER… PAGPALIT NG MUSIKA…**

**ANGKOR 1:** HAWAKAN NATIN ANG PULSO NG MGA PANGUNAHING BALITA NGAYONG HAPON.

**STINGER**

**ANGKOR 1:** [HEADLINE 1]

**STINGER**

**ANGKOR 2:** [HEADLINE 2]

**STINGER**

**ANGKOR 1:** [HEADLINE 3]

**STINGER**

**ANGKOR 2:** [HEADLINE 4]

**STINGER… PAGPALIT NG BAGONG MUSIKA (BED 2: BALITA)…**

**ANGKOR 1:** [HEADLINE 1]. TYRAH INARES, ANO ANG BUONG DETALYE?

**TAGAPAGBALITA 1:** [NASYONAL NA BALITA]. TYRAH INARES, PULSO SA BALITA.

**ANGKOR 2:** SALAMAT, TYRAH. ISANG TANONG BAGO KA UMALIS: SA IYONG PALAGAY, ANO KAYA ANG PINAKAMAHALAGANG DAPAT TANDAAN NG MGA KABABAYAN TUNGKOL DITO?

**TAGAPAGBALITA 1:** [SAGOT SA TANONG]

**STINGER**

**ANGKOR 2:** [HEADLINE 2]. CARL ADLAWAN, ANO ANG BUONG DETALYE?

**TAGAPAGBALITA 2:** [LOKAL NA BALITA]. CARL ADLAWAN, PULSO SA BALITA.

**ANGKOR 1:** SALAMAT, CARL.

**STINGER… PAGBABA NG MUSIKA…**

**ANGKOR 1:** AT BAGO NATIN PULSUHIN ANG PALIGSAHAN AT ALIWAN, MAY ISANG PAALALA TAYONG…

**ANGKOR 2:** …HAHATIDIN PARA SA INYONG LAHAT.

**BUMPER:** PULSO, D-Z-R-M, SAIS-SYETE-PUNTO-SINGKO — MAIKLING PAALALA MUNA, MULING MAGPUPULSO TAYO.

**PAGPASOK NG MUSIKA (BED 3: PAALALA)…**

**KARAKTER 1:** [INFOMERCIAL-SCENE]

**KARAKTER 2:** [INFOMERCIAL-SCENE]

**KARAKTER 3:** [INFOMERCIAL-SCENE]

**STINGER… PAGHINA AT PAGHINTO NG MUSIKA…**

**PAALALA:** [INFOMERCIAL-PAALALA]. [INFOMERCIAL-FACT]. [INFOMERCIAL-SOLUSYON]. [INFOMERCIAL-CTA]. PAALALA HATID NG PULSO, D-Z-R-M, SAIS-SYETE-PUNTO-SINGKO.

**AWIT:** [INFOMERCIAL-AWIT]

**STINGER**

**TUNOG NG TIBOK NG PUSO (DALAWANG TIBOK)**

**ANGKOR 2:** NARINIG NINYO BA ANG PINTIG? BABALIK TAYO SA D-Z-R-M, SAIS-SYETE-PUNTO-SINGKO — PULSO!

**STINGER… PAGPALIT NG BAGONG MUSIKA (BED 4: PALIGSAHAN)…**

**ANGKOR 1:** PARA SA PINTIG NG PALIGSAHAN — [HEADLINE 3]. CARL ADLAWAN, ANO ANG BUONG DETALYE?

**TAGAPAGBALITA 2:** [SPORTS NA BALITA]. CARL ADLAWAN, PULSO SA PALIGSAHAN.

**ANGKOR 2:** SALAMAT, CARL.

**STINGER… PAGPALIT NG BAGONG MUSIKA (BED 5: ALIWAN)…**

**ANGKOR 2:** AT NGAYON, PINTIG NG ALIWAN — [HEADLINE 4]. TYRAH INARES, ANO ANG BUONG DETALYE?

**TAGAPAGBALITA 1:** [SHOWBIZ NA BALITA]. TYRAH INARES, PULSO SA ALIWAN.

**ANGKOR 1:** SALAMAT, TYRAH. NAKU, HINDI MAPATID ANG PINTIG NG ALIWAN.

**STINGER… PAGPALIT NG PANAPOS NA MUSIKA (BED 1: PANAPOS)…**

**ANGKOR 1:** BAGO TAYO MAGPAALAM, MULING PULSUHIN NATIN ANG MGA BALITA NG ARAW: [HEADLINE 1]; [HEADLINE 2].

**STINGER**

**ANGKOR 1:** AKO SI RAIN CALITES, KASAMA NINYO SA PAGPULSO.

**ANGKOR 2:** AT AKO SI CELINE ASOY, KASABAY SA PINTIG NG BAWAT BALITA.

**STINGER**

**ANGKOR 1:** D-Z-R-M,
**ANGKOR 2:** SAIS-SYETE-PUNTO-SINGKO,
**LAHAT:** PULSO — PULSOHAN NATIN ANG BALITA!

**TUNOG NG TIBOK NG PUSO (MAHINA, HUMIHINA…)**

**ANGKOR 2:** TUNAY ANG PINTIG, TUNAY ANG BALITA.

**AWIT:** [AWIT-CLOSE]

**PAGTAAS NG MUSIKA… PAGBABA AT PAGHINTO…**
