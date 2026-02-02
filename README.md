# ARC Raiders Trophy Tracker

A web-based progress tracker for the **Trophy Display** project quest line in [ARC Raiders](https://arcraiders.com). Helps players keep track of the materials they need to collect across all five steps and see what rewards they'll earn along the way.

## What It Does

The Trophy Display quest requires collecting 20 different materials by defeating specific ARC units and looting key locations. This tracker lets you:

- **Track your progress** across all 5 steps with increment/decrement counters for each material
- **See what you need** at a glance — item names, quantities required, and where to find them
- **View rewards** for each step and the final completion bundle
- **Save your progress** to a code you can store anywhere (clipboard, notepad, Discord, etc.)
- **Load progress** from a save code to pick up where you left off or switch devices
- **Auto-saves** to your browser's local storage so your progress persists between visits

## Steps Overview

| Step | Name | Enemies / Sources |
|------|------|-------------------|
| 1 | Roaming Threats | Ticks, Pops, Surveyors |
| 2 | Soaring Menaces | Spotters, Wasps, Hornets |
| 3 | Ferocious Foes | Shredders, Leapers, Bastions |
| 4 | Dominant Dangers | Rocketeers, Queens |
| 5 | Imposing Behemoths | Bombardiers, Matriarchs |

Completing all five steps unlocks the **Completion Bundle**: Jupiter Sniper, Guitar, Howl gesture, and 300,000 Coins.

## How to Use

1. Visit the [live site](https://rdsciv.github.io/RoamingThreats/)
2. Use the **+** and **-** buttons to track materials as you collect them
3. Click **Save** to copy a save code to your clipboard
4. Click **Load** to paste a save code and restore progress
5. Click **Reset** to start over

Your progress auto-saves in your browser, so you don't need to manually save unless you want a backup or want to transfer to another device.

## Tech Stack

- Single-page HTML app (no build step, no dependencies to install)
- [Tailwind CSS](https://tailwindcss.com) for styling
- Vanilla JavaScript
- Item images from the [ARC Raiders Wiki](https://arcraiders.wiki)
- Hosted on GitHub Pages

## Running Locally

Just open `index.html` in a browser. No server or build tools needed.

## Credits

- Game content and item images belong to [Embark Studios](https://www.embark-studios.com/) / ARC Raiders
- Item icons sourced from [arcraiders.wiki](https://arcraiders.wiki)
