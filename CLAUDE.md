# CLAUDE.md – Vino – Wein lernen (`wein-lern-app`)

@~/Nextcloud/Claude/Projekte/MiniApps/REGELN.md

Die Regeln oben (REGELN.md) gelten für jede Session in diesem Repo, dazu das Mini-App-Muster aus den CLAUDE-Anweisungen. Hier steht nur, was **diese** App betrifft.

## Diese App

- **Live:** https://mvonulmerbach-ship-it.github.io/wein-lern-app/ · Beschreibung und Abweichungen: `README.md`
- **Familie:** Lern-Vorlage · Geschwister: `kaffee`, `klassik-oper-lern-app`, `philo` – Änderungen an gemeinsamen Teilen dort mitziehen (REGELN §4)
- **Version:** `CACHE` in `sw.js` – bei jeder Änderung hochzählen; die Zahl steht nur dort.
- `aromarad.html` ist eine Kopie aus `aroma-rad` – hier nie ändern.

## Abschluss (DoD nach REGELN §2)

UI-Prüfung im Repo-Ordner, erwartet „UI-PRUEFUNG GRUEN“ (kein Befund der Schwere ≥ 2), danach die Bildschirmfotos aus dem genannten Ordner ansehen:

```powershell
& "$env:LOCALAPPDATA\Mietverwaltung\venv\Scripts\python.exe" "$env:USERPROFILE\Nextcloud\Claude\Projekte\App-Design-Datenbank\Werkzeuge\ui_pruefen.py" .
```

Am Ende Summary und Description für dieses Repo als eigene Codeblöcke; committet und gepusht wird von Max.
