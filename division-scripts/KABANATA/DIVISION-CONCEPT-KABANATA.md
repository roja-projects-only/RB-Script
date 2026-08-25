# DIVISION-CONCEPT-KABANATA — Konseptong Panukala (PROPOSAL)

**Status:** PROPOSAL — hindi pa LOCKED. Hindi ito approved brand hangga't hindi sinasabi ng user/team na i-lock ito. Ang callsign at frequency lamang ang naka-lock (tingnan sa ibaba).

**Relasyon sa mga kapatid na proposal:** Pitong panukala na ang nasa `division-scripts/` — `BATINGAW`, `BATINGAW-2`, `DALUYONG`, `TALA`, `HIMIG`, `PALENGKE`, at itong `KABANATA`. Pipili ang team ng **ISA**; huwag paghaluin ang mga tunog-tatak (kampana, alon, tala, himig, palengke, pahina). Ang run na ito ay hindi nag-overwrite ng kahit ano.

**Mahalagang pagkakaiba sa anim na kapatid:** sa kasalukuyang run, **lahat ng kapatid** ay bumabalot ng bagong programa sa paligid ng **naka-lock na himpilan: D-Z-R-M 67.5** (`SAIS-SYETE-PUNTO-SINGKO`) — una rito ang `PALENGKE` at itong `KABANATA`; ang mga dating imbentong callsign (D-Z-M-T 88.3, D-W-A-L 98.7, D-Z-P-L 96.7, D-W-H-M 95.1) ay pinalitan na.

**Pagkakaiba sa audience:** ayon sa utos ng user (**"do not assume it's montalbenos"**), walang demonym ang run na ito — `MGA KABABAYAN` lamang, tulad ng neutral na address ng `BATINGAW-2` ngunit ibang salita (wala ang "SA BAWAT TAHANAN"). Walang hometown na inimbento.

---

## 1. Ang konsepto sa isang pangungusap

Ang himpilan ay ang **aklat ng balita** ng bayan: bawat araw ay may bagong kabanata, at ang mga tagapakinig ay nagbabasa kasama natin — `KABANATA NG BALITA`, `D-Z-R-M` 67.5, sa slogan na **"BAWAT ARAW, MAY BAGONG KABANATA."**

## 2. Bakit ito (desisyon sa run na ito)

Pinili mula sa 3 kandidatong itinuring: **KABANATA** (aklat ng balita), *Batis* (agos ng balita), *Panulat* (sulat ng balita). KABANATA ang nanalo dahil:

- **Originality (corpus-verified):** walang book/pahina/kabanata identity sa 18 National scripts (walang ganito sa quarantine list ng benchmark §21, sa `reusable-techniques.md`, o sa per-script DO NOT COPY sections). Walang collision sa C5 travel family, C8 digital, C17 Tatak-, sa lumang aarangkada/weaving ng team, o sa anim na kapatid (kampana, alon, tala, himig, palengke).
- **Ibang break architecture kaysa sa mga kapatid:** BATINGAW/DALUYONG = rest-the-logo ("papahinga ang kampana" / "pahawak ang daluyong"); TALA = hold ("huwag mawala sa tala"); HIMIG = tune-change ("magpapalit ng himig"); PALENGKE = sarado-bukas ng pamilihan. Ang KABANATA = **ISANG PAHINA NG PAALALA** — hindi tumitigil ang aklat sa break; lumilipat lang tayo ng pahina. Ang infomercial ay **naka-loob sa konsepto** (pahina sa loob ng aklat), katulad ng red-light stop ni C5 at LIBRENG TIKIM ng PALENGKE — ngunit ibang device (page-turn, hindi market cycle).
- **Dalawang murang sonic asset, bihirang gamitin:** **TUNOG NG PAGBUKAS NG PAHINA** (open) at **TUNOG NG PAGLIKOM NG AKLAT** (close) — 2 beses lang sa buong programa. Libre o madaling i-record (paglikot ng pahina, paghampas ng librong sumasara); kaya ng isang student operator. HINDI kampana (BATINGAW), HINDI chime (TALA), HINDI alon (DALUYONG), HINDI motif (HIMIG), HINDI palengke (PALENGKE), HINDI busina (luma/C5).
- **Close answers open:** open = slogan split (`BAWAT ARAW,` / `MAY BAGONG KABANATA.`) + bumukas ang pahina; close = parehong slogan (LAHAT, buo) + **`HANGANG SA SUSUNOD NA KABANATA.`** + nagsara ang aklat. Isang libro, isang loop.
- **Hook na atin, hindi generic truth-sticker:** ang balita ay **nakasulat** — record ng katotohanan na hindi nakakalimutan, hindi pwedeng burahin. Ang `PAGBASA` ay imbitasyon (sama-sama tayong nagbabasa), hindi plain "katotohanan/serbisyo" (genre default).
- **Speakability:** `KABANATA` (3 pantig), `PAHINA` (3), `BASA` (2); slogan na 5 salita sa 2+2 beats; `GABAY SA PAGBASA` / `KASAMA SA PAGBASA` ay parallelismo (tulad ng C16 chain, sariling salita) — walang forced rhyme.
- **Category words na libre:** **ISPORTS** (sports) at **ALIWAN** (showbiz) — hindi ginamit ng mga kapatid (LARO/TANGHALAN, PALARO/SHOWBIZ, PALAKASAN/TSIKAHAN ang kanilang mga kinuha) at hindi bahagi ng quarantine list.

## 3. Identity block (fixed forms — walang variant drift)

| | |
|---|---|
| Callsign | **D-Z-R-M** (**LOCKED** — hindi inimbento) |
| Frequency | **67.5** → `SAIS-SYETE-PUNTO-SINGKO` (**LOCKED**) |
| Program | **KABANATA NG BALITA** |
| Slogan | **BAWAT ARAW, MAY BAGONG KABANATA.** (schedule: open split / close LAHAT) |
| Sonic logo | **TUNOG NG PAGBUKAS NG PAHINA** (open) · **TUNOG NG PAGLIKOM NG AKLAT** (close) — 2× lang |
| Audience | **MGA KABABAYAN** (pangkalahatan; walang demonym — utos ng user) |
| Break pair | `SUSUNOD SA D-Z-R-M: ISANG PAHINA NG PAALALA.` / `MULI NATING BINUKSAN ANG KABANATA!` |
| Break frame | **ISANG PAHINA NG PAALALA** (ang infomercial ay pahina sa loob ng aklat) |
| Category words | **ISPORTS** (sports) · **ALIWAN** (showbiz) |
| Sign-off family | `[NAME], SA PAHINA NG [BALITA/ISPORTS/ALIWAN].` |
| Anchor roles | A1 `GABAY SA PAGBASA NG BALITA`; A2 `KASAMA SA PAGBASA` |
| Unison money lines | `KABANATA NG BALITA!` (open + close) · `BAWAT ARAW, MAY BAGONG KABANATA.` (close LAHAT) |
| Station tag (PAALALA) | `PAALALA PARA SA LAHAT — MULA SA D-Z-R-M.` |
| Close callback | `HANGANG SA SUSUNOD NA KABANATA.` |

## 4. Vocabularies at kung saan sila lumalabas (payoff map)

| Device | Pwesto |
|---|---|
| `TUNOG NG PAGBUKAS NG PAHINA` / `TUNOG NG PAGLIKOM NG AKLAT` (logo) | open / close — 2× lang; tahimik sa gitna |
| `BAWAT ARAW, MAY BAGONG KABANATA.` (slogan) | open (split A1/A2), close (LAHAT) |
| `KABANATA NG BALITA` (program title) | ID layers, re-entry ID, close ID |
| `PAHINA` (concept noun) | headline frame (`SA MGA PAHINANG BUKAS NGAYONG ARAW`), handoff (`SIMULAN NATIN SA UNANG PAHINA`), sign-off family (`SA PAHINA NG…`), break (`ISANG PAHINA NG PAALALA`), recap (`MGA PAHINANG BINUKSAN NATIN`) |
| `GABAY SA PAGBASA NG BALITA` / `KASAMA SA PAGBASA` (anchor roles) | paired intros + close IDs |
| `SA PAHINA NG [BALITA/ISPORTS/ALIWAN]` (sign-off family) | lahat ng 4 na report sign-off |
| `SUSUNOD SA D-Z-R-M: ISANG PAHINA NG PAALALA.` / `MULI NATING BINUKSAN ANG KABANATA!` | break pair (entry/return) |
| `HANGANG SA SUSUNOD NA KABANATA.` (callback) | huling linya — sumasagot ang close sa open |

Bayad ang konsepto ng 2+ beses sa bawat uri; ang logo ay bihirang gamitin (scarcity discipline). Ang konsepto ay **container** — hindi pumapasok sa katawan ng balita (`[NASYONAL NA BALITA]` at iba pa ay plain news prose; ang book verbs ay nasa gilid lamang: frame, toss, sign-off, bumper, close).

## 5. Hindi dinala (historical) at quarantine

- **Hindi dinala mula sa lumang script:** Tagahabi/aarangkada, busina, `PEPRENO`, `MULING AARANGKADA`, mga lumang jingle, ang cadence ng `ITO ANG…` opening, `MONTALBEÑOS` address, `CHISMIS NA WALANG KAPARES`, `I-CHIKA MO NA`, `BALITAANG PALABAN`, `KAAGAPAY NA SUBOK`, `TATAK NG LEHITIMONG SERBISYO`, `MUNTING PAALALA MULA SA D-Z-R-M`.
- **Hindi kinuha sa National:** benchmark §21 (walang Patrol family, walang 91.26, walang persona, walang C4 sweep/C5 horn/C15 theme/C8 Offline, walang eksaktong linya).
- **Hindi kinuha sa mga kapatid:** walang kampana/alon/tala/himig/palengke vocabulary, walang kanilang break pairs, walang kanilang sign-off families, walang kanilang audience address.

## 6. Kapag na-lock

Palitan ang status na ito ng **LOCKED** at i-update ang `DIVISION-SCRIPT-KABANATA.md` production notes nang naaayon. I-archive ang mga natalong proposal file kung nais ng team na mag-iwan ng isang "live" na identity sa folder.
