# Universal Play Web App

A responsive static web app / PWA launcher for EmulatorBIOS Online Emulator.

## Run locally
Open `index.html` in a browser. The emulator itself requires an internet connection.

## Publish free with GitHub Pages
1. Create a public repository on GitHub.
2. Upload the contents of this folder (make sure `index.html` is at the repository root).
3. In the repository, open **Settings → Pages**.
4. Set the source to **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for publishing, then open the URL shown in Settings → Pages.

Official guide: https://docs.github.com/en/pages/quickstart

## Important
The page tries to embed `https://emulatorbios.com/online-emulator/` in an iframe. The provider may block iframe embedding in its security headers. If so, use the **Open full player** / **Launch emulator** links, which open the official emulator page.

This is a launcher, not a standalone emulator. It does not include ROMs or BIOS files and does not emulate Xbox or modern PC games.
