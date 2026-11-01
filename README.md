# Kostkownik

Algorytmy i metody do kostek Rubika: wybierasz kostkę, potem metodę, potem zestaw (OLL, PLL, F2L, CMLL, CLL, EG…). Działa offline jako aplikacja na iPadzie i iPhonie (PWA).

## Pliki

| Plik | Do czego |
|---|---|
| `index.html` | cała aplikacja (dane i obrazki w środku) |
| `manifest.webmanifest` | nazwa, ikona, tryb pełnoekranowy |
| `sw.js` | service worker – zapamiętuje aplikację, żeby działała bez internetu |
| `icon-*.png`, `icon.svg` | ikony |

## Wrzucenie na GitHub Pages

1. Załóż konto na github.com (jeśli nie masz).
2. Kliknij **New repository**, nazwij je `kostkownik`, zostaw **Public**, kliknij **Create repository**.
3. Kliknij **uploading an existing file** i przeciągnij wszystkie pliki z tego folderu (bez folderu nadrzędnego). Kliknij **Commit changes**.
4. Wejdź w **Settings → Pages**. W **Source** wybierz **Deploy from a branch**, branch `main`, folder `/ (root)`, **Save**.
5. Po 1–2 minutach aplikacja będzie pod adresem `https://TWOJA-NAZWA.github.io/kostkownik/`.

## Instalacja na iPadzie / iPhonie

1. Otwórz ten adres w **Safari** (musi być Safari).
2. **Udostępnij** → **Do ekranu początkowego** → **Dodaj**.
3. Otwórz raz z ikony przy włączonym internecie – od tej chwili działa też offline.

## Aktualizacja

Podmień `index.html` w repozytorium (Add file → Upload files). Aplikacja pobierze nową wersję przy następnym uruchomieniu z internetem. Postęp nauki (Nowe / Uczę się / Umiem) zostaje, bo jest zapisany na urządzeniu.

## Źródła algorytmów

SpeedCubeDB, CubeDB, SpeedCube Australia, Sarah's Cubing oraz linki z speedcubing.com/CubingAlgs.html. Zestawy 3x3, 2x2 i parity na dużych kostkach są sprawdzone symulatorem.
