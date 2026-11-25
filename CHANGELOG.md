# Changelog

All notable changes to this theme are documented here.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), versions follow [Semantic Versioning](https://semver.org/).

## [Unreleased]

## [1.0.1] - 2026-11-25

### Changed
- Contour background lighter in weight: about 12 KB per mode instead of 20 KB; index contours in the colour of the fine lines (only wider), so section titles on top keep 4.5:1.
- Red, orange, green and blue scales derived from the map inks, so alerts, danger and success buttons and chips stay within the map print.
- Lower tile sliders (card-mod) only with a mouse; touch screens keep the full finger size.
- Dialog corners 4 px like the cards; switches react to hover.

### Fixed
- README: corners are rounded by 4 px, not square; the thermostat ring is the one control below 3:1 (its arcs are drawn half transparent by the frontend); `card-mod-root` is no longer part of the theme; light colours also stay in entities card rows; note for slow wall tablets.

## [1.0.0] - 2026-11-25

### Added
- First release: one theme with light mode (day map) and dark mode (night map).
- Contour background as an embedded SVG, white map sheets with a thin forest-green rim, no shadows. Works without add-ons.
- Five map inks only (forest green, contour brown, water blue, road red, ink); every palette colour of the frontend is mapped onto them. Text 4.5:1 and controls 3:1 in both modes.
- Road red for active devices, forest green for locked, armed and at home, ochre for pending; forest-green switches, selection and keyboard focus, narrow system fonts.
- Map density: sheets 6 px apart, larger section titles, square tile sliders and buttons, a printed thermostat track.
- Optional card-mod rules: red map pin and red state line on active device tiles, coloured light tiles in road red, lower tile sliders, dashed trail lines between rows of entities cards, letter-spaced capitals for titles, badges and the sidebar, map font and framed selection in the sidebar, focus ring on badges.
