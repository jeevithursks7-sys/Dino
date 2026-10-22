# Chrome Dino — standalone runner

A standalone browser version of the classic T-Rex runner, based on the community extraction of Chromium's offline runner. The original BSD-style license and attribution are preserved in `LICENSE`.

## Run locally

Open `index.html` in a modern browser. If your browser blocks local resources, serve this folder with any static HTTP server.

## Controls

- **Space / Up Arrow:** jump or start
- **Down Arrow:** duck
- **J:** toggle immortality on/off. When off, the next collision ends the run normally.

The best score is saved in browser local storage as you play.

## Deploy to Vercel

Import this folder/repository as a static project. No build command is required; the output directory is the project root.
