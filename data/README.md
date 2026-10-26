# NYC hotel ma'lumotlari — data/

Manba: **NYC Open Data — "Hotels Properties Citywide"**
- API: https://data.cityofnewyork.us/api/v3/views/tjus-cn27/query.json
- Dataset sahifasi: https://data.cityofnewyork.us/view/tjus-cn27
- Tavsif: "Listing of hotels within the five boroughs" (besh borough'dagi hotellar ro'yxati).

## Fayllar

- **nyc-hotel-buildings.json** (758 ta bino, ~112 KB) — Manhattan'dagi noyob hotel binolar.
  Har bir yozuv: `bbl` (soliq lot ID), `num` (uy raqami), `street` (ko'cha),
  `zip`, `class` (bino klassi, masalan H1/H2/H3/RH), `lat`, `lng`, `nta` (mahalla).
- **nyc-hotel-streets.json** (256 ta ko'cha, ~17 KB) — ko'cha kesimida sanash:
  har bir ko'chada nechta hotel binosi borligi va uy raqamlari ro'yxati.

## Tozalash usuli

Xom fayl 11 MB, 19 830 qator edi — har bir bino 2021–2027 soliq yillari bo'yicha
7 martagacha takrorlangan. BBL (borough-block-lot) bo'yicha takrorlar olib tashlandi:
Manhattan'da **758 ta noyob hotel binosi** qoldi (shaharda jami 1 341 ta).

## Eslatmalar (muhim)

- Sonlar **bino** (soliq loti) soni — brend emas. Bir bino = bitta kutish nuqtasi.
- Burchakdagi hotel faqat bitta ko'cha nomiga yozilgan (masalan, Conrad loti
  "102 North End Avenue", Wall Street Hotel loti "4 Platt Street" deb yozilgan).
  Shuning uchun ko'cha kesimidagi sonlar — minimal aniq sonlar.
- Broadway 50 ta — butun Manhattan bo'ylab (Times Square oralig'i 1500–1700: 6 ta).
- Bino klasslari: H1–H9, HB, HH, HR, HS va RH — hammasi hotel klasslari
  (masalan, Pod Times Square — RH klassida).
