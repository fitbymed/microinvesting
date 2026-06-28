# Rentio — landing page

Statyczny landing page (jeden plik `index.html`) dla oferty mikroinwestowania / pożyczki kapitału.

## Co zawiera
- Oferta pożyczki od **25 000 zł** do **5 000 000 zł**, min. okres **12 miesięcy**, umowa odnawiana co rok.
- Dwa warianty: wypłata **miesięczna (WIBOR + 5 p.p.)** oraz **na koniec roku (WIBOR + 8 p.p.)**.
- Kalkulator odsetek na żywo (suwak kwoty + edytowalny WIBOR).
- Wykres porównujący roczne odsetki dla **25k / 100k / 250k**.
- Animacje (orby w tle, count-up statystyk, reveal przy scrollu, animowany wykres).
- Aktualny WIBOR 3M wpisany jako baza: **3,84%** (stan na 24.06.2026).

## Jak zmienić WIBOR
Strona ma suwak WIBOR, więc każdy może przeliczyć na żywo. Domyślną wartość zmienisz w `index.html`:
- szukaj `value="3.84"` (suwak) oraz tekstów `3,84%`, `8,84%`, `11,84%`.

---

## Wgranie na GitHub (przez GitHub Desktop)

1. Otwórz **GitHub Desktop** → `File` → `New repository...`
2. Nazwa np. `rentio`, wybierz lokalny folder, kliknij **Create repository**.
3. Skopiuj `index.html` (i ten `README.md`) do utworzonego folderu repozytorium.
4. W GitHub Desktop pojawią się zmiany → wpisz opis commita (np. „pierwsza wersja") → **Commit to main**.
5. Kliknij **Publish repository** (możesz odznaczyć „Keep this code private", jeśli chcesz publiczne — wymagane dla darmowego GitHub Pages).

## Włączenie GitHub Pages

1. Wejdź na stronę repozytorium na github.com.
2. `Settings` → w menu po lewej **Pages**.
3. W sekcji **Build and deployment** → **Source**: wybierz **Deploy from a branch**.
4. **Branch**: wybierz `main`, folder `/ (root)` → **Save**.
5. Po ~1 minucie strona będzie pod adresem:
   `https://TWOJA-NAZWA-UZYTKOWNIKA.github.io/rentio/`

> Ważne: plik musi nazywać się `index.html` i leżeć w katalogu głównym repo (tak jest tutaj).

Gotowe — odśwież adres po chwili, jeśli na początku pokazuje 404.
