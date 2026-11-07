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

- Podajesz nick, losuje się 10 pytań z nowej bazy 1000 pytań (seria 2) w 10 kategoriach i na 3 poziomach trudności. Tryb „mieszany” daje 4 łatwe, 4 średnie i 2 trudne, od najłatwiejszych. Można też wybrać jeden poziom i jedną kategorię. Pytania nie powtarzają się, dopóki nie wykorzystasz całej puli.
- 4 odpowiedzi, opcjonalny limit 20 s, na końcu lista błędów do powtórki.
- Ranking: każda gra to osobny wpis (wynik, czas, data). Obecny jest **sezon 2**. Ranking sezonu 1 (stara pula pytań) zostaje w sekcji „Archiwum”. Nowy sezon zaczyna się od zmiany `SEASON` w `index.html`.
- **Wspólny ranking:** w „Wspólny ranking ze znajomymi” skopiuj kod i wyślij znajomym, a oni wkleją go u siebie. Możesz też wkleić wyniki do pliku `1z10/ranking.json` (tablica) i zrobić commit, wtedy każdy zobaczy je od razu.
- Własne pytania: dopisz linijkę na końcu któregoś pliku `1z10/pytania_*.js` (po jednym na kategorię) w formacie `[C.G, 2, "Pytanie?", "Poprawna", "zła 1", "zła 2", "zła 3"]` (trudność 1–3).

Po włączeniu GitHub Pages (Settings → Pages → branch → `/ (root)`) strona jest pod `…github.io/<repo>/1z10/`.
