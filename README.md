# StudieStart

Leer woorden met spelletjes en je eigen lijsten. Werkt op laptop, telefoon en tablet, en ook zonder internet nadat je de app één keer hebt geopend.

## Gebruiken

Open de online versie of open `index.html` in je browser. Installeer de app via het menu van je browser ("App installeren" of "Zet op beginscherm").

## Online zetten met GitHub Pages

1. Ga naar je repository op GitHub, kies **Settings > Pages**.
2. Bij **Source** kies je **Deploy from a branch**, branch `main`, map `/ (root)`.
3. Klik op **Save**. Na een paar minuten staat de app op `https://<jouw-gebruikersnaam>.github.io/<repo-naam>/`.

Alle links in de app zijn relatief, dus de app werkt ook in een submap zoals hierboven.

## Bestanden

- `index.html`: de volledige app (HTML, CSS en JavaScript).
- `sw.js`: service worker voor offline gebruik.
- `manifest.webmanifest`: gegevens om de app te installeren.
- `icons/`: app-iconen.
- `LEESMIJ.txt`: uitleg voor de eindgebruiker.

## Let op

Lijsten en punten worden per apparaat opgeslagen in de browser. Gebruik de back-up-functie op het beginscherm om ze over te zetten.

Wijzig je bestanden die offline worden gecachet? Verhoog dan de versie in `sw.js` (de waarde van `V`, bijvoorbeeld van `studiestart-v4` naar `studiestart-v5`), zodat gebruikers de nieuwe versie krijgen.
