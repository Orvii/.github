# Changelog

## [2026-10-05] - Brand banner, published table, research-set diagram, CI loops

### Added
- `assets/` — approved brand lockups: `banner-dark.png`, `banner-light.png` (white-backgrounded, per brand owner), `banner-light-transparent.png`, `logo.png`
- `profile/research-set.svg` — seven-node diagram of the public research repos with methodology edges
- `.github/workflows/npm-metrics.yml` — monthly npm snapshot committed back by CI (replaces the machine-bound systemd timer; see Orvii/retractions 005)
- Published table in `profile/README.md` listing all seven public repos

### Modified
- `profile/README.md` — brand banner above the datasheet hero; reliability agenda de-localized (research question, not local infrastructure); verbatim bio sentence and ampersand acronym (audit findings from crashed run wf_29d51455-b09, recovered from transcripts)

## [2026-10-04] - Org datasheet profile

### Added
- `profile/hero.svg`, `profile/terminal.svg`, `profile/pillars.svg` — animated datasheet instruments (CSS keyframes only, sanitizer-safe, reduced-motion aware)
- `profile/README.md` — org identity, ts-lto teaser (private, no links), research agenda, house rules
