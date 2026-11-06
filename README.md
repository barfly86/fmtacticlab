[README.md](https://github.com/user-attachments/files/34482838/README.md)
# FM27 Tactic Generator

**A tactic generator for Football Manager 27 built for players who don't want to spend hours in the tactics screen.**
Pick a formation and a playing style, or just choose your favourite manager, and get a complete FM27 tactic: roles for every player in and out of possession, team instructions, a consistency check and a ready-to-load `.fmf` file.

🌐 **Live:** _add your URL here (e.g. GitHub Pages / your domain)_
☕ **Support the project:** [buymeacoffee.com/barfly86](https://buymeacoffee.com/barfly86)

Available in **English, Polish, Spanish and German**.

---

## Features

- **Formation + style in a few clicks.** 10 formations (4-2-3-1, 4-3-3, 4-4-2, 4-2-4, 4-2-2-2, 4-4-2 diamond, 3-4-3, 3-5-2, 5-2-1-2, 3-4-2-1), 5 playing styles (possession, attack & pressing, counter-attacks, direct play, solid defence), where you attack (narrow / mixed / wide) and how strong your team is.
- **Built on the official presets.** Every tactic starts from the 90 official FM27 presets by Sports Interactive, so it fits the match engine.
- **Quick pick: favourite manager.** 15 manager-inspired setups (Guardiola, Slot, Amorim, De Zerbi, Simeone, Gasperini, Kovač, Glasner, Iraola, Hoeneß, Luis Enrique, Ancelotti, Mourinho, Fonseca, Fàbregas) with their signature roles and instructions.
- **Both phases of play.** An interactive pitch that switches between the in-possession and out-of-possession shape, with every role, duty and player instruction.
- **Consistency check.** Warnings about settings that clash: too many Attack duties, a gap between the press and the defensive line, a high line without a Sweeper Keeper, no width, tactic complexity and its effect on Tactical Effectiveness.
- **Explained decisions.** Every role and instruction comes with a short explanation, plus a "what to watch in the first matches" list.
- **Advanced mode (optional).** Adds settings that dominated in tests of the FM27 trial version. These may stop working after a match engine update.
- **`.fmf` file.** Generates a recipe that a bookmark turns into a tactic file you can load in the game.

## How to use

1. Open the generator and choose a manager **or** a formation, style, attacking direction and team strength.
2. Review the roles, team instructions and the consistency check.
3. Either copy the tactic as text and set it up in the game, **or** create an `.fmf` file (below).

### Creating an `.fmf` file

The file is built with the free tactic editor at [tactics.sortitoutsi.net](https://tactics.sortitoutsi.net).

**First time only:** drag the green **FM27 → file** button onto your browser's bookmarks bar (show the bar with `Ctrl+Shift+B`). If dragging doesn't work, copy the bookmark code and paste it into the URL field of a new bookmark.

**Every time you want a file:**
1. Click **Copy recipe** in the generator.
2. Open tactics.sortitoutsi.net in a separate tab and **log in** (register first if you have no account). Only once you are logged in, click the **FM27 → file** bookmark.
3. Paste the recipe into the window that appears and click **Create .fmf file**. The file goes to your Downloads folder.
4. In the game: tactics screen → **Load Tactic** → pick the downloaded file.

The bookmark only runs on tactics.sortitoutsi.net. It takes an official FM27 preset as a base, applies the recipe and checks that every position and role was set. The site limits the number of requests, so create files one at a time.

## Hosting

The whole generator is a single, self-contained `index.html` with no build step, server or database.

**GitHub Pages:** push `index.html` to a repository → *Settings → Pages* → deploy from the `main` branch.
**Netlify:** drag the folder with `index.html` onto [app.netlify.com/drop](https://app.netlify.com/drop).

All preset data, team instructions, manager setups and translations live in the data section at the top of the script in `index.html`, so updates after a match engine patch only touch that section.

## Data sources

- 90 official FM27 presets by Sports Interactive, read via [tactics.sortitoutsi.net](https://tactics.sortitoutsi.net).
- Tactic tests from the 5-day FM27 trial version (used only in advanced mode).

Role and instruction names are kept in English, exactly as they appear in the game. The match engine will change with updates, so treat every generated tactic as a solid starting point and fine-tune it to your players after 5–6 matches.

## Disclaimer

Unofficial fan tool. Not affiliated with Sports Interactive, SEGA or tactics.sortitoutsi.net. Football Manager is a trademark of its respective owners. Manager styles are interpretations of their play within FM27 settings, not their official tactics.

## Support

If the generator helped you build your tactic, you can [buy me a coffee](https://buymeacoffee.com/barfly86). It keeps the project going: updates for new match engine versions, more managers and new features.

## Author

Created by **barfly86**.

## License

© 2026 barfly86. All rights reserved.
