# meshview.dk — kendte MeshCore-kanaler

Katalog over kendte danske MeshCore-kanaler, vedligeholdt af [meshview.dk](https://meshview.dk).

## Filer

- **`channels.json`** — kataloget i det format CoreScope forbruger direkte
  (`channels-by-country.json`-formen: `generated_at`, `license`, `countries`).
  Det er denne fil `knownChannelsUrl` skal pege på.
- **`upstream/dk.json`** — samme kanaler i bidragsformatet til det fælles
  community-katalog [marcelverdult/meshcore-channels](https://github.com/marcelverdult/meshcore-channels)
  (én fil pr. land: `code`, `name`, `channels`). Bruges kun til PR opstrøms.

## Bidrag

Mangler der en kanal? Åbn et issue eller en PR mod `channels.json`
