# PeppermintGrave Music Vault

A self-contained personal ambient music archive by **PeppermintGrave**.

The project is designed to run as a static website. No build process, framework, server, or external JavaScript dependency is required.

## Features

- Dark green and cyan archive interface
- Local MP3 playback
- Playlist with ten original recordings
- Play, pause, previous, next, shuffle, repeat, and volume controls
- Ambient mode
- Keyboard controls
- Responsive layout for phones, tablets, and desktops
- No animation on the initial “Not Playing Yet” text

## Folder structure

```text
peppermintgrave-music-vault/
├── index.html
├── README.md
├── LICENSE
├── audio/
│   ├── Paper Moons.mp3
│   ├── When the Night Learns Your Name.mp3
│   ├── Old Notebook.mp3
│   ├── Where the Silence Grows.mp3
│   ├── When You Still Knew Me.mp3
│   ├── Where the Daylight Ends.mp3
│   ├── From the Other Side of the Screen.mp3
│   ├── Still Here.mp3
│   ├── Static Skies.mp3
│   └── Mosslight Drift.mp3
└── images/
    └── icon.png
```

## Run locally

Open `index.html` in a browser. For the most reliable local audio behavior, serve the folder with a simple static server or upload the repository to GitHub Pages.

## Deploy with GitHub Pages

1. Create a new GitHub repository.
2. Upload the contents of this folder.
3. Make sure `index.html` is in the repository root.
4. Open **Settings → Pages**.
5. Select the main branch and the root folder.
6. Save and wait for GitHub Pages to publish the site.

## Audio files

The player expects the MP3 files to remain inside the `audio/` folder with the exact filenames shown above. Filename capitalization and spaces matter.

## Credits

Created and maintained by **PeppermintGrave**.

© 2026 PeppermintGrave. All rights reserved, except where the included license states otherwise.
