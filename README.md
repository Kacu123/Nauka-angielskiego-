# Fiszki: kolory i przedmioty szkolne (EN/PL)

Jeden plik `index.html`, bez zależności. Działa na iPhonie (Safari) i na komputerze.

- **Fiszki**: przód = obrazek + angielskie słowo + 🔊, tył = po polsku + definicje EN i PL (z odsłuchem).
- **Quiz**: słyszysz słowo i wybierasz odpowiedź (kolory jako kółka) albo wpisujesz je z pamięci.
- 20 kolorów + 54 przedmioty szkolne. Czytanie na głos przez wbudowany głos przeglądarki.

## Darmowy hosting
- **Netlify Drop**: wejdź na app.netlify.com/drop i przeciągnij plik `index.html`.
- **GitHub Pages**: Settings → Pages → Deploy from branch → `/ (root)`.
- iPhone: Safari → Udostępnij → „Dodaj do ekranu początkowego".

---

# Trening „1 z 10” (`1z10/`)

Prosta strona do ćwiczenia pytań z wiedzy ogólnej. Bez serwera i logowania, czysty HTML/JS.

- Podajesz nick, losuje się 10 pytań (z ~110, z kategorii: geografia, historia, nauka, kultura, sport, ogólne). Pytania nie powtarzają się, dopóki nie wykorzystasz całej puli.
- 4 odpowiedzi, opcjonalny limit 20 s, na końcu lista błędów do powtórki.
- Ranking (najlepszy wynik gracza, przy remisie szybszy czas) zapisuje się w przeglądarce.
- **Wspólny ranking:** w „Wspólny ranking ze znajomymi” skopiuj kod i wyślij znajomym, a oni wkleją go u siebie. Możesz też wkleić wyniki do pliku `1z10/ranking.json` (tablica) i zrobić commit, wtedy każdy zobaczy je od razu.
- Własne pytania: dopisz linijkę w `1z10/questions.js`.

Po włączeniu GitHub Pages (Settings → Pages → branch → `/ (root)`) strona jest pod `…github.io/<repo>/1z10/`.
