# WSMLol

**A free desktop companion app for League of Legends (Windows and macOS).**
WSMLol helps you during the ~30 seconds of champion select and after your games, with clear, statistics-based advice instead of raw tables.

[**Download the latest version**](https://github.com/GodWass/wsmlol-releases/releases/latest) · [Privacy policy](PRIVACY.md) · [Terms of use](TERMS.md) · Contact: abdiwassim4@gmail.com

---

## Features

- **Champion select, live** (official local League Client API): your role and lane opponent, ban and pick suggestions with their winrate and sample size, an estimated win probability, and the most played build for your champion (runes, summoner spells, items, skill order) with one-click import.
- **Loading screen**: once your game has started, the rank, season winrate and champion mastery of the 10 players (names shown by the game itself at that point).
- **In-game overlay** (optional): a separate, transparent, click-through window showing your own stats, the skill to level up and, while you hold Tab, the estimated gold difference per lane next to the game's scoreboard.
- **Profile and match history**: rank and LP over time, recent games, full post-game analysis (scoreboard, loadouts, timeline), season duos.
- **Champion and player search**: matchups, best and worst teammates, most played builds, filterable by role.

Statistics come from Emerald to Master ranked solo/duo games and are smoothed so that small samples are never presented as reliable. A statistic is only recommended above 100 games.

## Fair play and privacy

- **The core of WSMLol is free.**
- **Your Riot API key is never in the app**: all Riot API calls go through our own backend.
- **No de-anonymization**: in ranked champion select, WSMLol never shows or looks up the names the client hides.
- **No interaction with the game**: no memory reading, no injection, nothing drawn inside the game window. The overlay only uses the official local Live Client Data API and shows what the scoreboard already shows.
- **No automation of decisions**: suggestions are recommendations; WSMLol never picks or bans for you. Optional automatic runes and spells only change your own setup, after you lock in your champion.
- **No MMR estimation, no hidden timers, no betting.**

## Install

1. Open the [latest release](https://github.com/GodWass/wsmlol-releases/releases/latest).
2. Download **`WSMLol_x.y.z_x64-setup.exe`** (Windows) or the **`.dmg`** (macOS, Apple Silicon).
3. Run the installer.

The app is not code-signed yet:

- **Windows**: SmartScreen may show "Windows protected your PC". Click **More info**, then **Run anyway**.
- **macOS**: right-click the app, then **Open**.

**Updates**: in the app, **Settings → About → Check for updates**. The update is downloaded, verified with our signing key, installed and the app restarts.

---

### En français

**WSMLol** est une application compagnon gratuite pour League of Legends (Windows et macOS) : conseils en champ select (bans, picks, build), scouting de l'écran de chargement, overlay en jeu optionnel, profil et analyse de parties. Téléchargement : [dernière version](https://github.com/GodWass/wsmlol-releases/releases/latest). Mises à jour : **Paramètres → À propos → Vérifier les mises à jour**. [Politique de confidentialité](PRIVACY.md) · [Conditions d'utilisation](TERMS.md) · Contact : abdiwassim4@gmail.com

---

WSMLol isn't endorsed by Riot Games and doesn't reflect the views or opinions of Riot Games or anyone officially involved in producing or managing Riot Games properties. Riot Games, and all associated properties are trademarks or registered trademarks of Riot Games, Inc.
