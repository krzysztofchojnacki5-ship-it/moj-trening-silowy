MÓJ TRENING SIŁOWY — PWA v3

CO NOWE:
- dodawanie własnych ćwiczeń do Treningu A lub B,
- własna ikonka/emoji ćwiczenia,
- usuwanie własnych ćwiczeń,
- zapis własnych ćwiczeń w pamięci przeglądarki,
- wszystkie funkcje z v2: kalendarz, 4 serie, historia, statystyki, timer, eksport/import, PWA.

URUCHOMIENIE NA KOMPUTERZE:
1. Rozpakuj ZIP.
2. Otwórz folder w Visual Studio Code.
3. Otwórz index.html przez Live Server.
4. W Narzędzia -> Własne ćwiczenia możesz dodać ćwiczenia.

DARMOWE WRZUCENIE DO INTERNETU — GITHUB PAGES:
1. Wejdź na https://github.com i załóż darmowe konto.
2. Kliknij + -> New repository.
3. Nazwij repozytorium np. moj-trening-silowy.
4. Ustaw Public.
5. Create repository.
6. Kliknij "uploading an existing file" albo Add file -> Upload files.
7. Wgraj ZAWARTOŚĆ folderu MojTrening (index.html, manifest.json, sw.js, avatar.jpg, icon-192.png, icon-512.png).
8. Kliknij Commit changes.
9. Wejdź w Settings -> Pages.
10. W "Build and deployment" wybierz Source: Deploy from a branch.
11. Branch: main, folder: / (root).
12. Save.
13. Po chwili GitHub pokaże adres strony. Będzie mniej więcej:
   https://TWOJ_LOGIN.github.io/moj-trening-silowy/

WAŻNE:
- GitHub Pages działa po HTTPS, więc PWA i Service Worker mogą działać.
- Na telefonie otwierasz adres w Chrome.
- Chrome -> menu ⋮ -> "Dodaj do ekranu głównego" / "Zainstaluj aplikację".
- Dane treningowe są lokalne dla danego urządzenia/przeglądarki. Dlatego przed zmianą telefonu używaj Narzędzia -> Eksport danych, a na nowym urządzeniu Import danych.
- Jeśli zmienisz kod później, ponownie wrzuć zmienione pliki na GitHub. Service Worker może potrzebować chwili na odświeżenie.

UWAGA:
GitHub Pages hostuje pliki za darmo, ale nie jest bazą danych. Nie zapisujemy danych treningowych na serwerze — zapis odbywa się lokalnie na urządzeniu.
