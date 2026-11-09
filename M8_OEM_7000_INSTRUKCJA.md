# M840i OEM 7000 — zmodyfikowany layout Cluster Themes

W istniejącym motywie `m` dodano napis `M8` obok trójkolorowego oznaczenia, zachowano styl inspirowany BMW M8 i dwa symetryczne łuki obrotomierza z zakresem **0–7000 obr./min**. Wybór w menu ma nazwę `M840i OEM 7000`. Zapisano także aktualizowany podgląd.

## Pliki

- `apps/cluster_themes/hud/layouts/m.json` — właściwy layout
- `apps/cluster_themes/hud/previews/m.json` — podgląd w menu
- `apps/cluster_themes/app.json` — nazwa i opis opcji

## Uruchomienie

Zbuduj aplikację z katalogu repozytorium poleceniem `python3 kit/tools/build.py cluster_themes`. Po instalacji przez zgodny instalator MGU wybierz w Cluster Themes motyw `M840i OEM 7000`.

### Ważne

To nakładka renderowana przez `cluster-render`, **nie oryginalny kod BMW M8**. Została zachowana geometria bazowa przeznaczona pod ekran G01 i ograniczenia nakładania fabrycznych elementów KOMBI. Na innych licznikach trzeba potwierdzić wymiary, widoczność i poprawność sygnałów. To nie zmienia limitu obrotów silnika.
