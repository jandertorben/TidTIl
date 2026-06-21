# TidTil Hugo Website

Moderne, skandinavisch ruhige Hugo-Landingpage für die iOS-App TidTil.

## Start

```bash
hugo server
```

Danach im Browser öffnen: `http://localhost:1313`

## Vor Veröffentlichung ersetzen

In `config.toml`:

- `baseURL`
- `params.appStoreUrl`
- `params.supportEmail`
- `params.ownerName`

In `content/datenschutz.md`, `content/support.md`, `content/impressum.md`:

- TODO-Stellen ersetzen
- Datenschutz mit finaler App-Technik abgleichen
- Impressum rechtlich prüfen

## App-Store-relevante Seiten

- `/datenschutz/` als Privacy Policy URL
- `/support/` als Support URL
- `/impressum/` für Anbieterkennzeichnung in Deutschland
