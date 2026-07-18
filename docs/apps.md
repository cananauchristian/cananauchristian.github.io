# MSX-Portal – Apps

Stand: 18.07.2026

| App | Primäre Adresse | Alternative | Besonderheit |
|---|---|---|---|
| Lampa | `http://lampa.mx` | Direkte Einrichtung als Startparameter | HTTP, gegebenenfalls offenes Schloss |
| MSXPlayer | `https://v4.msxplayer.ru` | `https://msxplayer.ru` | v4 ist eine Testversion |
| Seasonvar | `https://seasonvar.club/msx/welcome.php` | `https://seasonvar.club` | Primär als MSX-Content eingebunden |

## Portal

Startparameter:

`cananauchristian.github.io`

Direkte Startdatei:

`https://cananauchristian.github.io/msx/start.json`

## Dateistruktur

- `msx/start.json`: Einstiegspunkt für Media Station X
- `msx/menu.json`: Hauptmenü
- `msx/apps/*/start.json`: Zwischenseiten der einzelnen Apps
- `msx/shared/unavailable.json`: Allgemeine Fehlerseite