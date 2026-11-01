# Italia – Explore with all senses

Desková hra pro 2–6 hráčů (lidé i počítač) na jednom zařízení – mobil i počítač.
Sbírejte pochutiny, vína a pamětihodnosti Itálie, inkasujte výplaty v bankách Milano, Ancona a Roma
a vybírejte poplatky od soupeřů.

## Spuštění
Hra je jediná statická stránka (`index.html`) bez serveru a bez instalace. Stačí ji otevřít v prohlížeči,
nebo zveřejnit přes GitHub Pages:

1. Vytvořte repozitář (např. `italia`) a nahrajte do něj **celý obsah této složky** (včetně složky `karty` a souboru `.nojekyll`).
2. V repozitáři otevřete **Settings → Pages**, zvolte *Deploy from a branch*, větev `main` a složku `/ (root)`.
3. Za chvíli bude hra na adrese `https://<uživatel>.github.io/italia/`.

Na telefonu lze stránku přidat na plochu („Přidat na plochu“) – spustí se jako aplikace.

## Obsah
| Soubor | Co obsahuje |
|---|---|
| `index.html` | celá hra – mapa, pravidla, počítačoví hráči, vlajky a bankovky (vloženo přímo v souboru) |
| `karty/` | obrázky 76 karet políček a 11 speciálních karet |
| `manifest.json`, `icon-*.png` | ikona a nastavení pro „Přidat na plochu“ |

Rozehraná hra se ukládá v prohlížeči (localStorage) daného zařízení.
