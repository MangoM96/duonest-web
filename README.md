# duonest-web

Minimale statische Website für `duonest.de` — Platzhalter-Startseite plus
Impressum/Datenschutz, damit App Store Connect eine gültige Datenschutz-URL
bekommt, solange die eigentliche Landing Page noch nicht existiert.

Inhalt von `/impressum/` und `/datenschutz/` ist 1:1 aus den In-App-Screens
übernommen (`lib/features/profile/presentation/impressum_screen.dart` bzw.
`datenschutz_screen.dart` im `duonest`-Repo) — bei Änderungen dort bitte
hier nachziehen, sonst laufen die Texte auseinander.

Deploy: GitHub Pages, Custom Domain `duonest.de` (siehe `CNAME`). Reines
statisches HTML/CSS, kein Build-Schritt.
