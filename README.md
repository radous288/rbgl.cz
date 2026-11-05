# rbgl.cz
Web pro RB Global Logistik s.r.o.

## Kam nahrát fotky a loga
Web si fotky najde sám podle názvu souboru. Přípona může být jpg, jpeg, png, webp (u log i svg). HTML není potřeba upravovat.

| Co | Složka | Název souboru |
|---|---|---|
| Logo firmy | hlavní složka (vedle index.html) | `logo.png` (nebo `logo.jpg`, `logo.svg` – pak upravit v index.html) |
| Mercedes-Benz Tourismo | `fotky/` | `tourismo-1.jpg`, `tourismo-2.jpg` … (až 8) |
| Mercedes-Benz Sprinter | `fotky/` | `sprinter-1.jpg`, `sprinter-2.jpg` … |
| Iveco Daily Irisbus | `fotky/` | `iveco-1.jpg`, `iveco-2.jpg` … |
| Fotky z výletů | `vylety/` | `vylet-1.jpg`, `vylet-2.jpg` … (až 30) |
| Loga referencí | `reference/` | např. `viscuma-plastic.png`, `miele-technika.png` … |

Číslo `-1` je hlavní fotka autobusu (zobrazí se i na úvodní stránce), ostatní se zobrazí jako náhledy.
Názvy souborů log referencí jsou v index.html u každé reference v `data-foto="reference/..."`.
