# media-watchdog-privacy

Veröffentlichte Datenschutzerklärung der Android-App **Media Watchdog**
(Paketname `de.pauli.mediawatchdog`).

- Deutsch: <https://soccertrash.github.io/media-watchdog-privacy/>
- English: <https://soccertrash.github.io/media-watchdog-privacy/en.html>

Die Seiten liegen unter GitHub Pages (aus `main` / Root). Die deutsche URL wird in der Play
Console unter *App-Inhalte → Datenschutzerklärung* eingetragen und ist in der App verlinkt.

Der App-Code liegt im privaten Repo `Soccertrash/MediaWatchdog`; dort sind
`docs/datenschutz.md` und `docs/privacy.md` die Quelle der Wahrheit. `index.html` und `en.html`
werden daraus erzeugt:

```bash
playstore/tools/privacy-html.sh ~/Projects/media-watchdog-privacy
```

Dieses Repo ist nur deshalb getrennt und öffentlich, weil GitHub Pages auf privaten Repos einen
kostenpflichtigen Plan erfordert. Ändert sich das Verhalten der App (neue Berechtigung, neue
Datenart, Netzwerkzugriff), muss diese Seite mitgeändert werden, immer in beiden Sprachen.

## Kontakt

Manfred Pauli · soccertrash.dev@gmail.com
