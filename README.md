# Ketten der Kinneret-Rekonstruktion

Ketten (`posterior.npz`, `prior.npz`) der Läufe aus
[kinneret_reconstruction_python](https://github.com/TimonNetzel/kinneret_reconstruction_python), abgelegt nach dem
Fingerabdruck ihrer Sampler-Einstellungen und Eingangsdaten: `ketten/<fingerabdruck>/`. `index.json` ordnet die
Läufe des Katalogs ihren Ketten zu; `ketten/<fingerabdruck>/ketten.json` beschreibt Einstellungen und Code-Stand.

Verwendung (im Hauptverzeichnis von kinneret_reconstruction_python):

```bash
git clone <dieses Repo> ../kinneret_reconstruction_laeufe
kinneret-recon batch --ketten ../kinneret_reconstruction_laeufe      # Ketten neu auswerten statt sampeln (~15 min)
kinneret-recon ketten sichern ../kinneret_reconstruction_laeufe      # neue Ketten aus results/ hinzufügen
```
