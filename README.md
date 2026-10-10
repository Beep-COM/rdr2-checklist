# RDR2 Story Missions Checklist

> **AI transparency notice**
> This project was designed, written and coded entirely by AI ([Claude](https://claude.ai), made by [Anthropic](https://www.anthropic.com)), through a conversation with a person who directed the features and design. The mission list was compiled from [GTABase](https://www.gtabase.com/red-dead-redemption-2/missions/) and may contain mistakes. If something looks off, check it against the in-game Progress menu.

An unofficial checklist for all 110 main story missions of *Red Dead Redemption 2*, styled to look like the in-game map. It is a single HTML file with no install and no build step.

**Live page:** `https://beep-com.github.io/rdr2-checklist/`

## Features

- All 110 main story missions across 8 chapters, in story order, with the mission giver shown under each title
- A dotted trail through the missions that turns solid as you complete them, with a red marker for the next mission
- Chapter tabs with scroll arrows, and automatic jump to the next chapter when you finish one
- Chapter progress shading behind each chapter title, plus an overall progress bar
- Optional honor missions (the missable ones) marked with a diamond, with a toggle to hide them
- Hide completed missions
- Search by mission, person or chapter (press `/`)
- "Next unfinished" jump button and "Mark chapter done" shortcut
- A ↗ link on every mission to its GTABase page
- Export and import your progress as a small JSON file
- Light and dark appearance, following your system setting
- Keyboard controls: `←` `→` change chapter, `↑` `↓` move between missions, `Space` checks one off

This project covers main story missions only. Strangers, bounties, collectibles and other activities are not included.

## How to use it

Open `index.html` in any modern browser. It works straight from the file, or you can host it.

### Host it on GitHub Pages

1. Put the file in a public repository, named `index.html`.
2. Go to **Settings**, then **Pages**.
3. Set **Source** to **Deploy from a branch**, choose your main branch and the **/ (root)** folder, then save.
4. After a minute or two, the site is live at the link shown on that page.

To update it later, upload a new `index.html` to replace the old one, then hard refresh the page (Ctrl+F5).

## Where your progress is saved

Your progress is saved in your browser's local storage, so it stays on that device and browser. Clearing site data erases it. Use **Export** now and then to keep a backup, and **Import** to restore it. Import only adds missions to what you already have, and never unticks any.

## Credits

- **Mission list and guide links:** [GTABase](https://www.gtabase.com/red-dead-redemption-2/missions/)
- **Built by:** Claude, made by Anthropic
- **Fonts:** IM Fell English by Igino Marini and Zilla Slab by Typotheque for Mozilla, both open source and loaded through Google Fonts. The page falls back to Georgia if they can't load.

## Disclaimer

*Red Dead Redemption 2* is made by Rockstar Games. This is an unofficial fan project and is not affiliated with or endorsed by Rockstar Games or Take-Two Interactive. It uses no game assets; the map look is drawn from scratch.
