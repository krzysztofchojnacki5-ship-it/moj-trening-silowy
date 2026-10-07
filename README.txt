MÓJ TRENING SIŁOWY — PAKIET PWA v6
===================================

Ta paczka jest przygotowana do podmiany plików aplikacji na GitHub Pages.

CO ROBISZ:
1. Rozpakuj ten ZIP.
2. Otwórz folder MojTrening.
3. Zaznacz WSZYSTKIE pliki z folderu.
4. W swoim repozytorium GitHub usuń/podmień stare pliki aplikacji tymi z paczki.
5. Zapisz zmiany / Commit changes.
6. Odczekaj chwilę na GitHub Pages.
7. Otwórz aplikację ponownie w Chrome na telefonie.

NIE MUSISZ RĘCZNIE EDYTOWAĆ:
- index.html
- manifest.json
- sw.js

W tej wersji poprawiono:
- obsługę instalacji PWA,
- przycisk instalacji na stronie Start,
- przycisk instalacji w Narzędziach,
- komunikat awaryjny, gdy przeglądarka nie udostępnia automatycznego okna instalacji,
- manifest PWA (id, scope, ikony, tryb standalone),
- aktualizację Service Workera (v6),
- wykrywanie, czy aplikacja jest już zainstalowana.

WAŻNE:
Strona internetowa nie może bez zgody Androida samodzielnie utworzyć ikony na ekranie.
Jeżeli dana przeglądarka nie udostępni automatycznego okna instalacji, aplikacja pokaże
instrukcję użycia menu przeglądarki: ⋮ -> Dodaj do ekranu głównego / Zainstaluj aplikację.

Po podmianie NIE otwieraj pliku index.html bezpośrednio z telefonu. Otwórz aplikację
przez jej adres HTTPS na GitHub Pages.
