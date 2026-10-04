# Changelog

All notable changes to this repository. Append-only; newest first.

## [2026-10-05] - Orvii org profile: brand datasheet + comprehensive README

### Added
- `profile/README.md` — comprehensive English org profile: identity, acronym pillars, ts-lto overview with equivalence-gate framing, four-item research agenda, working principles, collaboration routes.
- `profile/hero.svg` — animated brand hero: hand-drawn "Orvii" wordmark (font-independent strokes), amber/orange orbital scope with the leaf-"o" emblem, datasheet chrome. CSS keyframes only (GitHub sanitizer safe), reduced-motion fallbacks.
- `profile/terminal.svg` — animated research-loop terminal (hypothesize / instrument + measure / make it public / write it down).
- `profile/pillars.svg` — O·R·V·I·I pillar rail with flowing dash line; `userSpaceOnUse` gradient so the rail renders in strict SVG renderers.
- `CHANGELOG.md` — this file.

### Notes
- Brand palette: `#FE9106` primary, `#FEAF12` highlight, `#FE7007`/`#F05F03` shadows, `#F8F5F2` text, `#0b0806` ground.
- Verified: xmllint well-formed, rsvg-convert rasterizes all three, no `<script>` / external refs.
