# Manga Tracker

A personal web app for tracking manga, manhwa and manhua reading progress. Built for my own use, starting with manga and planned to grow into movies and music.

**Live demo:** https://pramukhsm18.github.io/manga_tracker/

<!-- Add a screenshot once you have one:
![Manga Tracker](screenshots/home.png)
-->

## Features

- Tracks last chapter read and total chapters for each title
- Progress bar and a "Caught up" or "chapters left" status per title
- +1 and -1 chapter buttons, plus editable read and total counts
- Search by title
- Filter by All, Behind or Caught up
- Sort by recently updated, title, most read, or most chapters left
- Summary at the top: total titles, caught up, behind, average % read
- Add and remove titles
- Light and dark theme that follows the device setting
- Pre-loaded with 95 titles from my reading list

## Tech stack

- HTML, CSS and vanilla JavaScript in a single `index.html` file
- Progress is saved in the browser with `localStorage`
- Hosted on GitHub Pages

No build step and no backend.

## Run it locally

1. Clone the repo:
   ```bash
   git clone https://github.com/PramukhSM18/manga_tracker.git
   ```
2. Open `index.html` in a browser.

## Known limitations

- Data is stored per browser and per device. Clearing site data erases your progress, and the live site and a local copy do not share data.
- No cover images yet.

## Roadmap

- [ ] Cover images fetched automatically from a manga database API
- [ ] Cloud storage (Supabase) so progress syncs across devices
- [ ] Movies and music tracking
- [ ] Export and import of the list

## Data

The starting list lives in the `SEED` array inside `index.html`: title, last chapter read, total chapters.
