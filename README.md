# Manhattan hotellari — xarita

Midtown (Times Square atrofi) va Downtown'dagi 8 ta hotel xaritada belgilangan.

Jonli sayt (GitHub Pages yoqilgandan keyin): https://hayotus.github.io/hotels/

## Hotellar

Midtown:
- Pod Times Square — 400 W 42nd St — 4.3 ★
- Aliz Hotel Times Square — 310 W 40th St — 4.0 ★
- InterContinental New York Times Square — 300 W 44th St — 4.5 ★
- Element Times Square West — 311 W 39th St — 4.2 ★
- Hilton New York Times Square — 234 W 42nd St — 4.5 ★

Downtown:
- Conrad New York Downtown — 102 N End Ave — 4.7 ★
- Moxy NYC Downtown — 26 Ann Street — reyting ma'lumoti yo'q
- The Wall Street Hotel — 1 Platt St — 9.6 (Expedia)

Xarita Leaflet + OpenStreetMap asosida, bitta `index.html` fayl.

## TOP-5 Tochka (Uber haydovchisi uchun)

Saytda ikkita rejim bor: **Hotellar (8)** va **TOP-5 Tochka** — NYC Open Data
(758 ta hotel binosi) + OSRM mashina yo'li hisob-kitobi asosida. Qizil metkadagi
son — shu tochka turgan joydan **mashinada 0,3 mil** ichida nechta hotel binosi
borligi. Metkani bossangiz ro'yxat chiqadi: har bir hotel yonida xona soni va
tochka'dan necha mil uzoqligi yozilgan. Moviy nuqtalar — 0,3 mil ichidagi hotellar.

| Tochka | 0,3 mil ichida | Jami xona |
|---|---|---|
| 1. W 39th St & 8th Ave | 14 ta | ~2 905 |
| 2. W 37th St & 6th Ave | 9 ta | ~1 585 |
| 3. W 46th St & Broadway | 10 ta | ~1 992 |
| 4. 6th Ave & W 28th St | 14 ta | ~2 755 |
| 5. W 48th St & 8th Ave | 10 ta | ~6 830 |

Jami 57 ta hotel binosi (53 ta noyob manzil, 51 ta ro'yxat qatori — bir binoda
2 ta lot bo'lgan hotellar birlashtirilgan), jami ~16 067 xona. Xona sonlari
hotel va bron qilish saytlaridan olingan (2026-10). Eslatmalar: Cambria
(30 W 46th St) yopilgan; ARIYA (34 W 38th St) qurilmoqda; Hotel Stanford
(43 W 32nd St) yopilgan bo'lishi mumkin; 5 ta lot'da hozir hotel yo'q
(618 8th Ave, 117 W 39th St, 27 W 38th St, 126 W 46th St, 1226 Broadway). Bir tomonlama ko'chalar tufayli
mashina masofasi to'g'ri chiziqdan uzun: masalan, Aliz (310 W 40th St) Tochka 1
dan to'g'ri chiziqda 120 m, lekin mashinada 0,54 mil — shuning uchun 0,3 mil
ro'yxatiga kirmagan.

## Ma'lumotlar (`data/`)

NYC Open Data — "Hotels Properties Citywide" (view `tjus-cn27`):
Manhattan'dagi 758 ta noyob hotel binosi (BBL bo'yicha tozalangan) va
ko'cha kesimidagi sanash. Batafsil: `data/README.md`.
