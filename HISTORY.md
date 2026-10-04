# Changelog & Version History

All notable changes to the **ParsiSaz Web Portal & Documentation** are documented here.
Format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), following [Semantic Versioning](https://semver.org/).

---

## [v1.2.0] - 2026-10-04

### Added
- **Interactive Challenges & Limitations Modal (`docs/index.html`)**:
  - Detailed technical drawer displaying game engine architecture, reverse-engineering obstacles, font hurdles, and workarounds.
  - Step-by-step installation guides with copy-to-clipboard functionality for game paths.
- **Deep Technical Data per Repository (`docs/games-data.json`)**:
  - Extracted engine details (Unity, OGRE, Java/LWJGL, REDengine, RAGE, Firefly).
  - Reverse-engineering challenges (RTL text shaping, disconnected cursive letters, inverted word ordering, glyph injection).
  - Exact target directories for mod file extraction.
- **Agent Commit Message Integration**:
  - Created `.agent/commit_message.txt` for automatic commit message generation used by `update.sh`.

### Changed
- **README.md Streamlining**:
  - Transformed `README.md` into a lightweight, elegant portal gateway.
  - Added high-visibility call-to-action badges pointing directly to `https://parsisaz.github.io/parsisaz/`.
  - Moved heavy static markdown tables to the dynamic web portal.
- **Search & Filtering (`docs/index.html`)**:
  - Extended real-time search to query engine names, challenges, and limitations keywords.

---

## [v1.1.0] - 2026-10-04

### Added
- Multi-category game filtering (`AAA`, `2026 Releases`, `2020-2025`, `Classics`).
- Catalog of ParsiSaz internal toolchains (`Parsik`, `farsiSaz`).
- Mobile-responsive layout and dark mode glassmorphism UI.

---

## [v1.0.0] - 2026-10-04

### Initial Release
- Initial deployment of ParsiSaz interactive GitHub Pages portal.
- Catalog data schema for community games and translations.
