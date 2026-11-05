# VízStop – interaktív demó

Biztosítsd Be Magad! 2026, 3. feladat (víz- és energiatudatosság a klímaváltozás árnyékában), Optimum csapat.

Egyetlen statikus oldal (`index.html` + `assets/`), külső függőség és build nélkül. Minden adat a böngészőben marad.

## Mit mutat

- **Élő szimuláció** – ugyanaz a csőrepedés VízStop nélkül és VízStoppal, 8 óra fél perc alatt.
- **A lakó appja** – főcsap elzárás/visszanyitás, riasztások, díj (−4%), szerelő hívása.
- **A közös képviselő nézete** – 40 lakásos panel, szerelési nap, strang-átfolyásmérő riasztás, havi riport.
- **Kalkulátor** – a lakó és a biztosító oldala, csúszkákkal.
- **A biztosítónak** – próbaprogram, kumulált pénzáram, fázisok és kapuk.
- **Kommunikáció** – lépcsőházi plakát és főcsap-matrica.
- **Jelentkezés** – szerelési nap, a jelentkezések `localStorage`-ban.

## Futtatás helyben

Kattints duplán az `index.html`-re, vagy indíts egy statikus szervert a mappában:

```bash
python3 -m http.server 8000
```

Majd nyisd meg: http://localhost:8000

## Közzététel GitHub Pages-en

1. Új repository (pl. `vizstop-demo`), a `demo` mappa tartalmát (`index.html`, `assets/`, `README.md`) töltsd fel a gyökérbe.
2. Settings → Pages → Source: *Deploy from a branch*, Branch: `main`, folder: `/ (root)`.
3. Pár perc múlva él: `https://<felhasználó>.github.io/vizstop-demo/`

Minden hivatkozás relatív, ezért almappából is működik.

## Számok forrása

A feladatkiírás (105 l/fő/nap, WC ~30%), a csapat pénzügyi modellje (B1–B5: 6% gyakoriság, 54% kárcsökkenés, 150 e Ft átlagkár, 4% díjkedvezmény, 20 e Ft eszköz, NPV +22 M Ft, megtérülés a 7. évben), LeakBot/Hiscox, Mercury, a szervezők közös kérdőíve (N = 312).
