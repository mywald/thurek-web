# Tanzschule Thurek

Statische Webseite von [www.thurek.de](http://www.thurek.de): eine Seite (`index.html`) mit Bildern,
Styles und Bibliotheken – kein Build, kein Server-Code. Änderungen (Termine, Kurse) direkt in
`index.html`.

Grundlage ist die Vorlage [Freelancer](https://github.com/StartBootstrap/startbootstrap-freelancer)
von Start Bootstrap (MIT, siehe `LICENSE`). Eingecheckt ist nur, was die Seite ausliefert
(`.gitignore` ist eine Whitelist); die Build-Werkzeuge der Vorlage (npm, gulp, SCSS) liegen im
Archiv-Projekt.

- `css/thurek.min.css` – eigene Styles samt Bootstrap 4.3, minifiziert
- `js/` – Navigation (Freelancer) und jqBootstrapValidation
- `vendor/` – Bootstrap, jQuery, jQuery Easing, Font Awesome 5 (nur die eingebundenen Dateien)
