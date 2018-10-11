# SlayTheSpireModding
The website is hosted at https://alexdriedger.github.io/SlayTheSpireModding.

The purpose of this site is to be a unified location for Slay the Spire modding documentation.

## Features

- BaseMod wiki is fully moved to this website
- Key pieces of the ModTheSpire wiki
- Some key docs have been rewritten (including the Getting Started page)
- One stop shop to getting started with modding
- Section for playing with mods (aka people who want to play with mods but not develop them)
- Built with [Docusaurus](https://docusaurus.io/) and published with GitHub Pages

## Development

### Requirements

- Yarn >= 1.5
- Node >= 8.x
- Docusaurus >= 1.4

### Running Site Locally

```
cd website
yarn start
```

### Adding/Editing Documentation

All documentation is written in Markdown in the `docs` folder. Editing is fairly straightforward.

When adding new pages, there are a couple steps to remember.

**Metadata**

Each doc needs metadata at the top of the file with an `id` and `title`. For consistency keep file names in `test-doc-stuff` format with the id be the same as the file name.
```
---
id: known-mods
title: List of Known Mods
---
```

**Sidebar**

In order for docs to show up in the sidebar, it must be added to `website/sidebars.json`. When adding new docs, remember to add it to the appropiate section (or make new sections)

### Deployment

Submit a PR once you have made changes and tested them locally. Once they are merged into master, Travis CI will automatically redeploy the website with the changes!

## What's Next

- The [ModTheSpire wiki](https://github.com/kiooeht/ModTheSpire/wiki) could easily be moved over to this website
- Search bar with [Algolia](https://community.algolia.com/docsearch/) (Docs found [here](https://docusaurus.io/docs/en/search#docsNav))
- Blog posts for modders to share their knowledge / ideas / project highlights