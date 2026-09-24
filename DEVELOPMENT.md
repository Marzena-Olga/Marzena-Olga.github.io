# Garaż Marzeny — Indian Scout 2022

Statyczna strona z moimi notatkami z adaptacji oświetlenia amerykańskiego Indian Scouta na Europę.

## Struktura

- `index.html` — przekierowanie strony głównej do instrukcji.
- `scout/index.html` — instrukcja z fotografiami i tabelą pinów.
- `scout/styles.css` — wygląd strony, układ mobilny i style wydruku.
- `scout/images/` — oryginalne zdjęcia; `pic3.jpg` zachowane z repozytorium, niewykorzystane w instrukcji.

## Podgląd lokalny

W katalogu repozytorium uruchom:

```bash
python3 -m http.server 8000
```

Otwórz `http://localhost:8000/scout/`.

## GitHub Pages

Skopiuj zawartość paczki do repozytorium i zatwierdź zmiany. Przy publikacji z gałęzi wybierz w ustawieniach GitHub Pages właściwą gałąź i katalog główny (`/`). Strona nie wymaga instalowania zależności ani procesu budowania.

## Edycja

Treść zmieniaj w `scout/index.html`, a kolory i odstępy w `scout/styles.css`. Kliknięcie zdjęcia otwiera oryginał w nowej karcie. Wszystkie zasoby są lokalne — strona nie wymaga zewnętrznych fontów ani skryptów.

Zmiana wyglądu zachowuje treść techniczną pierwotnych notatek; nie stanowi jej weryfikacji.
