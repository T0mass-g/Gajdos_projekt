# Style-guide – Akadémia Kód

## Zadanie
Podľa `text.txt` vytvor vlastné `index.html` a `assets/css/style.css`. 

Musíš použiť:
- [ ] sémantické HTML (`header`, `nav`, `main`, `section`, `article`, `footer`)
- [ ] CSS premenné v `:root`
- [ ] Google Fonts cez `@import` (nadpisy: Space Grotesk, text: DM Sans)
- [ ] **flexbox** aj **grid**
- [ ] mobile first: základ je pre mobil, ďalej len `@media (min-width: ...)`
- [ ] BEM názvy tried (napr. `hlavicka__logo`)
- [ ] `:hover` na odkazoch a tlačidlách

## Farby

#d9c9ee
#40364a
#fff9f5 
#dcebe1 
#f2d3c3 

## Fonty

- Nadpisy a logo: **Space Grotesk**
- Text: **DM Sans**

## Breakpointy
| Zariadenie | Šírka | Rozloženie |
|---|---|---|
| Mobil | do 699px (základ) | všetko pod sebou |
| Tablet | od 700px | kurzy 2 stĺpce, štatistiky 3 vedľa seba, hlavička v 2 riadkoch |
| Desktop | od 1000px | kurzy v 4-stĺpcovom gride, prvý kurz cez 2 stĺpce (`span 2`), kroky vedľa seba |

## Odsadenia
- Bočné odsadenie sekcií: `5%` (na desktope môže byť viac, napr. `8%` alebo `10%`)
- Vertikálne odsadenie sekcií: `3rem` až `5rem`
