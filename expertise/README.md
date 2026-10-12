# Expertise

The Expertise section of the Book of Rituals (`project/brief-dip12.md`), in two tiers.

**Yours.** What you choose. `INDEX.md` is the list.
- **Knowledge:** 3 texts, 3 institutions, 3 experts, one card each in `texts/`, `institutions/`, `experts/`
- **Design:** details, materials, fabrication, craft in `design/` (for 5th years, the start of the ETS document)
- **Practice:** how other people work, in `practices/`

**The unit's.** `unit/` holds the voices the unit suggests: the brief itself (`unit/_brief.md`) and one card per name on the unit's list. Shared by everyone; listed in `INDEX.md` under "Unit consultants". See `unit/README.md`.

`sources/` holds the raw material behind every card, from both tiers.

**To add one:** `/gather <name>`. Claude makes the card, the sources folder and the INDEX row, and marks what it could verify.

**To make a unit consultant yours:** `/gather promote <name>`. The card is copied into your area and added to your shortlist.

**By hand:** copy `<area>/_template.md` to `<area>/<slug>.md` (area: `texts`, `institutions`, `experts`, `design`, `practices`), add a row to `INDEX.md`, and make `sources/<slug>/` with a `_source.md` listing what is in it and where it came from.
