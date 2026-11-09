# Tanzschule Thurek

Statische Webseite von [www.thurek.de](https://www.thurek.de): eine Seite (`index.html`) mit
eigenem Stylesheet, Schriften und Bildern – kein Framework, kein JavaScript, kein Build.
Änderungen (Termine, Kurse, Preise) direkt in `index.html`; je Kurs gibt es dort eine Karte
mit Beschreibung, Termin und Preis.

- `index.html` – Inhalt; das Datenschutz-Fenster ist ein HTML-`popover`, das der Browser
  selbst öffnet und schließt
- `css/thurek.css` – Layout und Farben (oben die Farbvariablen)
- `css/fonts.css`, `fonts/` – Lato und Montserrat, lokal statt von Google Fonts
- `img/` – Fotos, Icon für Apple-Geräte; `favicon.svg`/`favicon.ico` im Hauptverzeichnis
- Lageskizze im Kontakt: SVG direkt in `index.html`, vereinfacht nach OpenStreetMap (Daten ODbL,
  daher der Hinweis „© OpenStreetMap-Mitwirkende“ in der Skizze)

Eingecheckt ist nur, was die Seite ausliefert (`.gitignore` ist eine Whitelist).

## Rechte

Texte, Fotos und Logo (Tanzpaar): © Tanzschule Thurek, alle Rechte vorbehalten.
Das Repository ist öffentlich, damit die Seite über GitHub Pages ausgeliefert werden kann;
eine Lizenz zur Weiterverwendung ist damit nicht verbunden.

Die Schriften Lato und Montserrat stehen unter der SIL Open Font License 1.1
(`fonts/OFL-*.txt`).
