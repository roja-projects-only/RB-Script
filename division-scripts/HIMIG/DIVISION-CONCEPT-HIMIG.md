# DIVISION-CONCEPT-HIMIG — Konseptong Panukala (PROPOSAL)

**Status:** PROPOSAL — hindi pa LOCKED. Hindi ito approved brand hangga't hindi sinasabi ng user/team na i-lock ito.

**Relasyon sa mga kapatid na proposal:** Limang panukala na ang nasa `division-scripts/` — `DIVISION-CONCEPT-BATINGAW.md`, `DIVISION-CONCEPT-DALUYONG.md`, `DIVISION-CONCEPT-TALA.md`, `DIVISION-CONCEPT-BATINGAW-2.md`, at itong `HIMIG`. Pipili ang team ng **ISA**; huwag paghaluin ang mga tunog-tatak (kampana, alon, tala, kampana-2, himig). Ang run na ito ay hindi nag-overwrite ng kahit ano.

---

## 1. Ang konsepto sa isang pangungusap

Ang himpilan ay **ang himig ng bayan**: isang maikling musikal na motibo ang nag-aanyaya sa lahat na makinig — `HIMIG NG BALITA`, `D-Z-R-M` 67.5, sa slogan na **"MAKINIG SA HIMIG NG BAYAN!"**

## 2. Bakit ito (desisyon sa run na ito)

Pinili mula sa 3 kandidatong itinuring: **HIMIG** (melodiya ng bayan), *Tambol* (tambol ng balita), *Bintana* (bintana ng bayan). HIMIG ang nanalo dahil:

- **Originality (corpus-verified):** walang music/melody identity sa 18 National scripts (ang sung theme ni C15 ay *cautionary tale* sa execution, hindi isang music system); walang "himig" sa lumang script (Tagahabi/weaving/vehicle), walang "himig" sa kahit isang kapatid na proposal (TALA=chime, DALUYONG=alon, BATINGAW-2=kampana). Walang collision sa C5 travel family, C8 digital, C17 Tatak-, o sa aarangkada ng team.
- **Ibang break architecture kaysa sa mga kapatid:** BATINGAW at DALUYONG ay **rest-the-logo** ("papahinga ang kampana" / "pahawak ang daluyong"); TALA ay **hold** ("huwag mawala sa tala"). Ang HIMIG ay **tune-change**: ang break ay literal na pagpapalit ng himig ("SANDALI TAYONG MAGPAPALIT NG HIMIG…"), ang return ay pagbabalik ng himig ("MULING NARIRINIG ANG HIMIG NG BALITA!") — tatlong magkakaibang arkitektura sa folder, at ang sa atin ay hindi kopya ng alinman.
- **Isang murang sonic asset:** isang **3-note motif** (do-mi-sol; recorder/whistle/xylophone — kaya ng isang student operator, hindi custom music). HINDI kampana (BATINGAW), HINDI solong chime (TALA), HINDI wave (DALUYONG), HINDI busina (luma/C5).
- **AWIT ay natural na kasya:** konseptong musikal, ngunit ang **AWIT ay PLACEHOLDER-ONLY** (utos ng user) — ang `[AWIT-THEME]` at `[AWIT-CLOSE]` ay mga slot para sa track na ihuhulog ng team, hindi isinusulat na lyrics. (Nananatili ang C15 caution: kung magkakaroon man ng sung material, maikli, plain words, walang forced rhyme.)
- **Audience:** neutral — `MGA TAGAPAKINIG`; walang demonym, walang hometown (utos ng user). Musika ay unibersal na imahe ng bayan — hindi nag-aangkin ng anumang landmark o historical fact.
- **Hook na atin, hindi generic truth-sticker:** "MAKINIG SA HIMIG NG BAYAN!" ay imbitasyon + larawan — hindi plain "katotohanan/serbisyo" (genre default).
- **Speakability:** `HIMIG` (2 pantig); slogan na 5 salita; `MAKINIG` at `TUGTUG` ay araw-araw na Tagalog; ang frequency `SAIS-SYETE-PUNTO-SINGKO` ay naka-lock (house digit-style).

## 3. Identity block (fixed forms — walang variant drift)

| | |
|---|---|
| Callsign | **D-Z-R-M** (**LOCKED** — hindi inimbento) |
| Frequency | **67.5** → `SAIS-SYETE-PUNTO-SINGKO` (**LOCKED**) |
| Program | **HIMIG NG BALITA** |
| Slogan | **MAKINIG SA HIMIG NG BAYAN!** (schedule: open split / return A2 / close LAHAT) |
| Sonic logo | **TUNOG NG HIMIG** (3-note motif; open, return, close LANG) |
| Audience | **MGA TAGAPAKINIG** (pangkalahatan; walang demonym) |
| Break pair | `SANDALI TAYONG MAGPAPALIT NG HIMIG…` / `MULING NARIRINIG ANG HIMIG NG BALITA!` |
| Sign-off family | `[NAME], NAGTUGTUG NG BALITA.` / `…NG PALARO.` / `…NG *SHOWBIZ*.` |
| Anchor roles | A1 `TAGA-TUGTOG NG HIMIG NG BALITA`; A2 `KASALIW SA HIMIG` |
| AWIT | THEME: PLACEHOLDER; INFOMERCIAL: PLACEHOLDER; CLOSE: PLACEHOLDER (tingnan §6) |

## 4. Vocabularies at kung saan sila lumalabas (payoff map)

| Device | Position |
|---|---|
| `TUNOG NG HIMIG` (motif — 3 nota) | open, return, close (3× lang; tahimik sa infomercial zone) |
| `MAKINIG SA HIMIG NG BAYAN!` (slogan) | open (split), return (A2), close (LAHAT) |
| `HIMIG NG BALITA` (program title) | ID layers, AWIT, PAALALA tag, return ID, close ID |
| `TAGA-TUGTOG NG HIMIG NG BALITA` / `KASALIW SA HIMIG` | paired intros |
| `NAGTUGTUG NG [BALITA/PALARO/SHOWBIZ]` (sign-off family) | lahat ng 4 na report sign-off |
| `I-TUGTUG MO SA AMIN ANG HIMIG NG [PALARO/SHOWBIZ]` | sports/showbiz toss |
| `TUGTUGIN NATIN ANG UNANG BALITA!` | headline handoff |
| `MAY HIHINTONG BAGONG HIMIG…` / `SANDALI TAYONG MAGPAPALIT NG HIMIG…` / `MANATILI SA HIMIG NG D-Z-R-M` | break tease / bumper / promise |
| `MULING NARIRINIG ANG HIMIG NG BALITA!` | re-entry |
| `IYON ANG MGA HIMIG NG ARAW NA ITO.` / `NATAPOS NA ANG HIMIG NGAYONG HAPON… PERO BUKAS, MAY BAGO TAYONG HIMIG.` | recap + close callback (sumasagot sa open) |
| `[AWIT-THEME]` / `[AWIT-CLOSE]` (placeholder slots) | sung bookend ng konsepto — ihuhulog ng team ang track |

Bayad ang konsepto ng 2+ beses sa bawat uri; ang logo ay bihirang gamitin (scarcity discipline). Ang konsepto ay **container** — hindi pumapasok sa katawan ng balita (`[NASYONAL NA BALITA]` at iba pa ay plain news prose).

**Ang break ay PALIT ng himig, hindi pahinga:** walang `TUNOG NG HIMIG` sa loob ng PAALALA block (ang motif ay open/return/close lang), ngunit ang *bumper* mismo ay nagpapalit ng musika — hindi tumitigil ang tunog ng himpilan, nagbabago ang himig. Ito ang tatak ng HIMIG: `MAGPAPALIT`, hindi `PAPAHINGA` at hindi `MUNA`.

## 5. Hindi dinala (historical) at quarantine

- **Retired:** Tagahabi ng Balita, weaving brand, aarangkada/makina/busina/horn, `PEPRENO`/`MULING AARANGKADA`, `AARANGKADA NA`, lumang jingle (`HALINA'T MAGLAKBAY…`, `HANDOG PARA SA BAYAN…`, teacher PSA song), `ITO ANG…` open cadence, `SA ULO NG MGA NAGBABAGANG BALITA`, `I-CHIKA MO NA`, `CHISMIS NA WALANG KAPARES`, `BALITAANG PALABAN`, `MONTALBEÑOS, IYAN ANG MGA BALITANG…`, `KAAGAPAY…`, `KATUWANG…`, lumang kwento (Geronimo, KVSHS, DepEd grading, Kris Aquino), child-shaming beat ng teacher PSA. **(Ang LOCKED na D-Z-R-M 67.5 ang dala.)**
- **Hindi kinuha mula sa mga kapatid:** kampana at `NAGPATUNOG`/`PAPAHINGA` (BATINGAW-2); alon/agos/daloy/`PAHAWAK`/`SUMABAY` (DALUYONG); tala/chime/`SUNDAN`/`SISILAY`/`GABAY` (TALA); rhyme family ng B-2 (`katotohanan`, `tahanan`, `kaganapan`, `tsismisan`), `SA BAWAT TAHANAN` address, at `MAGBABALIK TAYO` promise; `TSIKAHAN` (TALA) bilang showbiz word; frequency strings ng lahat.
- **Quarantined (never):** anumang "…Patrol"/"91.26"; C5 lexicon (`kabiyahero`, `ruta`, `travel buddy`, `red light`, horn-as-logo); C8 "Offline!"/"Tama muna pag-scroll"; C17 "Tatak-"; C9 "Kasama Ka"; C13 "Heto na!"/"LABAN, PILIPINAS!"; C18 "Walang preno, tuloy-tuloy"; C10 "nagmamasid sa… napapanahon"; C16 mapanuri-chain; C1 "Pilipinas… balitaan na!"/"Mabuhay ka!"; lahat ng exact lines sa benchmark §21; at ang lahat ng linya ng kapatid na proposal.
- **Salita na iwasan sa bawat pass:** `tuloy`/`tuloy-tuloy` (C18 adjacency; DALUYONG ay gumagamit ng `tuloy`), `bawat` at `tahanan` (B-2), `katotohanan` (siblings' family), `magbabalik` (corpus default + B-2 promise), `chika`/`tsismis`/`tsismisan`/`tsikahan` (corpus/luma/siblings), journey words (`sakay`, `biyahe`, `daan`), water words (`agos`, `daloy`, `alon`).
- **Huwag gamitin ang motif bilang hook ng infomercial.** Theatrical SFX ng araw ay nasa `[INFOMERCIAL-SCENE]` lamang.

## 6. AWIT decisions (PLACEHOLDER-ONLY — walang isinusulat na lyrics)

| Slot | Desisyon | Dahilan |
|---|---|---|
| Opening theme | **PLACEHOLDER** (`[AWIT-THEME]`) | Utos ng user: walang isinusulat na lyrics. Slot para sa track na mayroon o kukunin ng team. |
| Infomercial jingle | **PLACEHOLDER** (`[INFOMERCIAL-AWIT]`) | Ang paksa ng advocacy ay competition-day content; kung jingle-shaped ang advocacy ng araw, mag-drop ng track doon; kung hindi, burahin ang linya. |
| Closing reprise | **PLACEHOLDER** (`[AWIT-CLOSE]`) | Slot para sa track ng team; hindi isinusulat bilang lyrics. |

## 7. Mga kilalang risk at mitigasyon

1. **Motif vs chime/kampana** — ang `TUNOG NG HIMIG` ay isang **3-note musical figure** (do-mi-sol; recorder/whistle/xylophone), HINDI isang solong chime (TALA), HINDI kampana (BATINGAW). I-label ang file: `himig-motibo.wav`, hindi `chime.wav` o `bell.wav`.
2. **C15 sung-theme caution** — ang AWIT ay placeholder-only; kung mag-drop ang team ng track, panatilihin itong maikli at payak (ang garbled sung themes ng corpus ang babala).
3. **`MAKINIG` ay generic word** — ang **spoken** slogan ay ang buong fixed phrase `MAKINIG SA HIMIG NG BAYAN!`; isang anyo lang saanman (open, return, close). Huwag "makinig sa himig ng katotohanan". Ang chant na `MAKINIG, MAKINIG` ay hindi isinusulat kahit saan — ang AWIT ay placeholder-only.
4. **`TUGTUG` density** — tugtog/tugtugin/nagtugtog/i-tugtog ay tatlong function (intro, toss, sign-off) — sapat na; huwag magdagdag ng ikaapat na "tugtog" sa headlines o sa katawan ng balita.
5. **Frequency string** `SAIS-SYETE-PUNTO-SINGKO` — naka-lock, house digit-style; drill item (3× pronunciation drill bago ang bawat ensayo).
6. **Sibling proposals** — limang panukala sa folder; ang team ang pipili ng ISA. Ang run na ito ay hindi overwrite ng kahit ano.
7. **Unison lines** — `LAHAT` = apat na boses (ANGKOR 1–2 + TAGAPAGBALITA 1–2; si Khassy ay credited, silent). I-drill ang sabay.

## 8. Paano mag-lock

Kapag sinabi ng user/team na i-lock ang HIMIG: (1) i-update ang status ng file na ito sa **LOCKED**, (2) i-update ang concept status sa `DIVISION-SCRIPT-HIMIG.md` notes, (3) i-archive o i-delete ang ibang panukala kung hindi sila ang napili (iwan ang isang "live" na identity), (4) pagkatapos ay protektado na ang identity forms sa ilalim ng benchmark §25 preserve rules.
