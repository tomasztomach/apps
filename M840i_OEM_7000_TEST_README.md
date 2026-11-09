# BMW M840i OEM 7000 — wersja testowa

## Wariant
W aplikacji Cluster Themes: **M840i OEM 7000**. Dwa lustrzane obrotomierze do 7000 rpm, bieg i prędkość centralnie, zmienione oznaczenie M840i, jednostki metryczne (km/h, °C, bar) i format 24h. Lewy panel: rzeczywista temperatura oleju i ciśnienie doładowania (gdy sygnały dostępne). Prawy panel: dostępne z samochodu ustawienia napędu/układu jezdnego — nie imitujemy fikcyjnych trybów.

## Pliki
`apps/cluster_themes/hud/layouts/m.json` — layout. `apps/cluster_themes/hud/previews/m.json` — obrazek podglądu. `apps/cluster_themes/app.json` — domyślne jednostki i nazwa motywu.

## Instalacja
Repo zawiera `mgu-repo.json`; prześlij zawartość katalogu `apps-main` do publicznego repo GitHub (tak, aby `mgu-repo.json` był w korzeniu), dodaj jako nowe źródło w MGU Store i zainstaluj/odśwież Cluster Themes. Zależności muszą być dostępne na jednostce.

## Ograniczenia
**Źródła testowe, nie przetestowane na samochodzie**. Obrazek preview jest przybliżony i nie gwarantuje renderowania KOMBI 1:1. Wartości oleju i doładowania zależą od sygnałów pojazdu i mogą być niedostępne. Rzeczywiste BMW M8 ma funkcje MDM/M xDrive niedostępne dla standardowego M840i; aplikacja ich nie aktywuje. Nie używaj do jazdy, zanim nie zweryfikujesz poprawności wszystkich wskazań na postoju.
