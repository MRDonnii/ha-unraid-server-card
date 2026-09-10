# Unraid Server Card

Et selvstændigt, tema-kompatibelt Lovelace-kort til Home Assistant. Kortet er flyttet fra en aktiv installation til et separat repository, så kildekode og versionshistorik kan vedligeholdes sikkert.

## Installation

Kopiér `ha-unraid-server-card.js` til `/config/www/ha-unraid-server-card/` og registrér ressourcen som et JavaScript-modul:

```text
/local/ha-unraid-server-card/ha-unraid-server-card.js?v=0.1.0
```

Tilføj derefter korttypen `custom:ha-unraid-server-card` i Lovelace. De nødvendige entities angives i kortets konfiguration; repositoryet indeholder ingen installationens dashboardkonfiguration eller personlige data.

## Udvikling

```bash
npm run check
```

## Licens

MIT
