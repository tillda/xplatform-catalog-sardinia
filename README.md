# Sardinia — an XPlatform catalog

Twelve paved roads in Sardinia worth riding, two of them passes: the Orientale
Sarda and the Gennargentu, the mining coast of the south-west, and the granite
of the Gallura.

## Add it to XPlatform

1. Open **Catalogs**, then **Add**.
2. Type `tillda/xplatform-catalog-sardinia` and confirm.

The catalog installs as `user/sardinia`. **Check for updates** compares its
`version` with this repository's `index.yaml` and offers the newer one.

## Files

| File | Holds |
| --- | --- |
| `index.yaml` | the catalog's `id`, `version`, name and file list |
| `sardinia-paved.map.md` | the roads, one Entry each |

## Sources and licence

- Roads come from web research held to the XPlatform destination library's
  evidence bar.
- Names and facts come from Wikidata (CC0).
- Descriptions that draw on Wikipedia are CC BY-SA 4.0.

## Releasing a new version

Edit the files, raise `version` in `index.yaml` (dotted numbers: `1`, `1.1`,
`2`), and push. The app refuses an update whose `id` differs.
