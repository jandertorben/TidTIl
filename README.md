# TidTil – Offizielle Webseite

**Familienzeit. Leicht gemacht.**

Offizielle Landingpage für [TidTil](https://jandertorben.github.io/TidTil/) – den ruhigen Familienplaner für iPhone. Gebaut mit [Hugo](https://gohugo.io/), deployed über GitHub Pages.

---

## Live

[jandertorben.github.io/TidTil](https://jandertorben.github.io/TidTil/)

## Stack

- **Hugo** – Static Site Generator
- **GitHub Pages** – Hosting
- **GitHub Actions** – Automatisches Deployment bei Push auf `main`

## Lokal starten

```bash
hugo server
```

Browser: `http://localhost:1313`

## Seitenstruktur

| Seite | Zweck |
|---|---|
| `/` | Landingpage mit Hero, Features, Philosophie, Datenschutz, App Store |
| `/datenschutz/` | Datenschutzerklärung (Privacy Policy URL für App Store) |
| `/support/` | Support-Kontakt (Support URL für App Store) |
| `/impressum/` | Impressum (gesetzliche Anbieterkennzeichnung) |

## Vor Veröffentlichung

Folgende Platzhalter in `config.toml` und den Content-Seiten ersetzen:

- `params.appStoreUrl` – Link zum App Store Eintrag
- Impressum: vollständige Adresse und Pflichtangaben ergänzen
- Datenschutz: rechtlich prüfen und mit finaler App-Version abgleichen
