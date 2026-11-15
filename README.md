# Címsorrend

Kiszállítási címsorrend-optimalizáló (PWA). A sorrendet a földrajzi folyosó–ág logika adja, nem a legrövidebb út.

## Közzététel GitHub Pages-en

1. Jelentkezz be a github.com oldalra, és hozz létre egy új tárolót (**New repository**). Név: `cimsorrend`, láthatóság: **Public**.
2. A tárolóban válaszd az **uploading an existing file** lehetőséget, és töltsd fel ezt a hat fájlt: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `README.md`. Majd **Commit changes**.
3. **Settings → Pages → Build and deployment**: Source: *Deploy from a branch*, Branch: `main`, mappa: `/ (root)`. **Save**.
4. Egy-két perc múlva az app itt érhető el: `https://FELHASZNÁLÓNEVED.github.io/cimsorrend/`
5. Nyisd meg Androidon a Chrome-ban, és a Beállításokban (jobb felső ikon) a **Telepítés** gombbal tedd a kezdőképernyőre.

## A TomTom-kulcs

A kulcs **nincs a kódban**. Az appban a Beállítások oldalon adod meg, és csak az eszközödön tárolódik. A TomTom fejlesztői felületén érdemes a kulcsot erre a címre korlátozni: `https://FELHASZNÁLÓNEVED.github.io/*`

## Frissítés

Új verziónál töltsd fel ugyanazokkal a nevekkel a fájlokat (a régi felülíródik). A telefon egy-két indítás alatt veszi át. Ha a régi marad, zárd be teljesen az appot, és nyisd meg újra.
