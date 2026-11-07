# Logopraktika · "Od gesta do glasa"

Jednostranični sajt za logopedski kabinet Logopraktika (mr Sara Ilić, Bileća).
Bez build koraka: `index.html` + folder `slike/`. GSAP, ScrollTrigger i Lenis se učitavaju sa CDN-a.

## Objava na GitHub Pages
1. Napravite novi **public** repozitorijum.
2. Otpremite **sadržaj** foldera (ne sam folder): `index.html`, `README.md`, `.nojekyll`, `slike/`.
   Ako web upload preskoči skriveni `.nojekyll`, napravite ga ručno: *Add file → Create new file*, ime `.nojekyll`, prazan.
3. *Settings → Pages → Deploy from a branch → main / (root) → Save*.
4. Za 1-2 minuta sajt je na `https://<korisnik>.github.io/<repo>/`.

Sve putanje su relativne, imena fajlova su mala slova bez razmaka, nema velikih fajlova.

## Prije objave dopuniti (u index.html potražite `[POTVRDI` i `[foto`)
- kako izgleda prvi dolazak (koliko traje, šta ponijeti)
- e-mail, radno vrijeme, tačna lokacija za mapu
- trajanje i cijene tretmana
- recenzija roditelja (sa dozvolom)
- JIB (potvrditi)
- domen: odkomentarišite `<link rel="canonical">` i upišite pravi domen; tada i `og:image` prebacite na punu adresu
