# RDR2 Missions Checklist

> **AI transparency notice**
> This project was designed, written and coded entirely by AI ([Claude](https://claude.ai), made by [Anthropic](https://www.anthropic.com)), through a conversation with a person who directed the features and design. The mission list was compiled from [GTABase](https://www.gtabase.com/red-dead-redemption-2/missions/) and may contain mistakes. If something looks off, check it against the in-game Progress menu.

An unofficial checklist for the 110 main story missions and 26 Strangers side missions of *Red Dead Redemption 2*, styled to look like the in-game map. It is a single HTML file with no install and no build step.

## Features

- All 110 main story missions across 8 chapters, in story order, with the mission giver shown under each title
- Two sections, Story Missions (with a tab per chapter) and Strangers: the 26 side missions (47 tickable steps; longer stories are one entry with a dropdown for parts I, II, III and so on), grouped by the chapter they unlock in, with a hint showing whether each group is unlocked yet (the optional time-sensitive ones are already in the story chapters)
- A dotted trail through the missions that turns solid as you complete them, with a red marker for the next mission
- Chapter tabs that always fit on screen, and an automatic jump to the next chapter when you finish one
- Chapter progress shading behind each chapter title, plus an overall progress bar
- Strangers that can be missed (currently Fundraiser and The Widow of Willard's Rest) carry a missable warning
- Optional honor missions (the missable ones) marked with a diamond, with a toggle to hide them
- Filters in one pop-up: hide completed missions, honor missions, the Special Edition mission, or Strangers
- Search by mission, person or chapter (press `/`)
- "Next unfinished" jump button and "Mark chapter done" shortcut
- A ↗ link on every mission to its GTABase page
- Undo for your last tick, chapter shortcut, import or reset (`Ctrl+Z`)
- A Data pop-up in the footer to export and import your progress as a small JSON file, or reset it
- A Stats pop-up with completion per chapter, Stranger stories finished, and which chapter is closest to done
- Optional sound effects (a stamp thud when you tick a mission, a rustle when you change chapter), with a Sound on/off switch in the footer
- A Credits pop-up, and a first-visit notice that the page was made entirely by AI
- Light and dark appearance, following your system setting
- Keyboard controls: `←` `→` change chapter, `↑` `↓` move between missions, `Space` checks one off

Bounties, collectibles and other activities are not included.

## How to use it

Open the HTML file in any modern browser. It works straight from the file, with no server or install needed.

## Where your progress is saved

Your progress is saved in your browser's local storage, so it stays on that device and browser. Clearing site data erases it. Use **Export** now and then to keep a backup, and **Import** to restore it. Import only adds missions to what you already have, and never unticks any.

## Credits

- **Mission list and guide links:** [GTABase](https://www.gtabase.com/red-dead-redemption-2/missions/)
- **Stranger parts:** [GTABase Stranger pages](https://www.gtabase.com/red-dead-redemption-2/strangers/)
- **Missable warnings:** [TrueAchievements walkthrough](https://www.trueachievements.com/game/Red-Dead-Redemption-2/walkthrough/4). Parts and warnings may differ slightly from the in-game journal
- **Built by:** Claude, made by Anthropic
- **Fonts:** IM Fell English by Igino Marini and Zilla Slab by Typotheque for Mozilla, both open source and loaded through Google Fonts. The page falls back to Georgia if they can't load.

## Disclaimer

*Red Dead Redemption 2* is made by Rockstar Games. This is an unofficial fan project and is not affiliated with or endorsed by Rockstar Games or Take-Two Interactive. It uses no game assets; the map look is drawn from scratch.
