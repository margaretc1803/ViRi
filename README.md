# ViRi — project

**Read `../START-HERE.md` first.** It is the current, authoritative description of this project.

## Layout of this folder

```
dist-elevated/          the website — this is the only build that matters
  index.html            shell + fixed 1280px viewport
  styles.css            design system and every layout
  app.js                router, all views, all interaction
  explore-data.js       8 cities, 61 venues, 112 members, ~1,189 sample classes
  assets/               36 images and one licensed font file
  README-redesign.md    the design record — every decision, round by round
  README-explore.md     the map, the class browser, and where real data must come from
ASSET-INVENTORY.md      all 36 assets, with provenance status
ASSET_SOURCES.json      provenance for the 12 assets that survive from the first build
Photos/                 Margaret's supplied source photographs
.openai/hosting.json    inert; names a ChatGPT Sites project from the first build
```

There is no build step and no dependency to install. Open `dist-elevated/index.html`, or serve it:

```
python3 -m http.server 8000 --directory dist-elevated
```

## History

An earlier version of this file described a burgundy, Canva-derived site with a cover video, a
reviews tab, and Ferly / DM Serif Display / Barlow Condensed typography. All of that was replaced
during the redesign. That document is kept at `../archive/project-README-original.md` for history
and should not be used as guidance.
