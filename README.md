# Webseite von Quittel

Statische Seite für GitHub Pages: https://quittel.github.io

- `index.html` Startseite, `impressum.html`, `datenschutz.html`, `404.html`
- Schrift DM Sans liegt in `fonts/` (SIL Open Font License), keine externen Inhalte, keine Cookies

## Veröffentlichen

Das Repo ist privat, solange die App noch nicht im Store ist (GitHub Pages ist kostenlos nur für öffentliche Repos).

    gh repo edit Quittel/quittel.github.io --visibility public --accept-visibility-change-consequences
    gh api -X POST repos/Quittel/quittel.github.io/pages -f "source[branch]=main" -f "source[path]=/"

## Zum App-Start

In `index.html` den Platzhalter „Bald im App Store“ gegen den auskommentierten Link zum App Store tauschen.
