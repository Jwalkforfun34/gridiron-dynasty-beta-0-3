# Gridiron Dynasty Beta 0.8.8.2

Legacy UI cleanup hotfix.

This build preserves Beta 0.8.8 league memory, Career Look, combine rankings, draft favorites, and Beta 0.8.7.1 progression while cleaning inherited UI wiring that could call older renderers.

Key fixes:
- Old event handlers now resolve the current renderer instead of capturing pre-redesign functions.
- Roster Position / Group, sort, and direction keep the modern mobile card presentation.
- League Roster trade targets now open the dedicated Trades screen instead of the old Draft workflow.
- Quick UI Tour no longer duplicates its overlay on repeated renders.
- Procedural portrait SVG IDs are unique when the same player appears more than once on screen.
- League Roster rows now use the modern procedural portraits instead of the legacy silhouette.
- Hidden hamburger/drawer compatibility shell remains non-player-facing for inherited code compatibility.

GitHub Pages entry point: `index.html`.
