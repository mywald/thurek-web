# Tanzschule Thurek

Statische Webseite von [www.thurek.de](http://www.thurek.de): eine Seite (`index.html`) mit Bildern,
Styles und Bibliotheken – kein Build, kein Server-Code. Änderungen (Termine, Kurse) direkt in
`index.html`.

Grundlage ist die Vorlage [Freelancer](https://github.com/StartBootstrap/startbootstrap-freelancer)
von Start Bootstrap (MIT, siehe unten). Eingecheckt ist nur, was die Seite ausliefert
(`.gitignore` ist eine Whitelist); die Build-Werkzeuge der Vorlage (npm, gulp, SCSS) liegen im
Archiv-Projekt.

- `css/thurek.min.css` – eigene Styles samt Bootstrap 4.3, minifiziert
- `js/` – Navigation (Freelancer) und jqBootstrapValidation
- `vendor/` – Bootstrap, jQuery, jQuery Easing, Font Awesome 5 (nur die eingebundenen Dateien)

## Rechte

Texte, Fotos und Logo (Tanzpaar): © Tanzschule Thurek, alle Rechte vorbehalten.
Das Repository ist öffentlich, damit die Seite über GitHub Pages ausgeliefert werden kann;
eine Lizenz zur Weiterverwendung ist damit nicht verbunden.

Fremde Teile mit eigener Lizenz:

- Gestaltung und Code basieren auf [Freelancer](https://github.com/StartBootstrap/startbootstrap-freelancer)
  von Start Bootstrap – MIT, `LICENSES/freelancer-MIT.txt`
- Bootstrap, jQuery (MIT) und Font Awesome Free (Icons CC BY 4.0, Schriften OFL) unter `vendor/` –
  Lizenzhinweis jeweils am Anfang der Datei
- jQuery Easing – BSD-3-Clause, `LICENSES/jquery-easing-BSD.txt` (die minifizierte Datei hat keinen Hinweis)
- Schriften Lato und Montserrat – SIL Open Font License 1.1, `fonts/OFL-*.txt`
