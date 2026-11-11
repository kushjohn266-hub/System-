# COMMAND // CORE

A browser-playable, 2D command-center simulation: direct a central AI brain, deploy autonomous field units, and guide them around Outpost Meridian.

## Play locally

Open `index.html` in a modern browser. No build step, server, API key, or game engine is required. The simulation runs locally in your browser; the central-brain command interpreter is a lightweight local demo, not a connection to a hosted AI service.

## Controls

- **Deploy Agent / Add Unit to Crew:** add a Scout, Builder, or Guardian with a selected first task. Crew size is capped at eight.
- **Directive to Nexus:** enter an instruction and send it. Try `explore`, `gather`, `regroup`, or `defend`; Nexus interprets these intents and retasks the crew.
- **Click a unit:** select it in the map or roster. Click a point on the map while selected to send that unit there.
- **Scan Sector:** pulse-scan the map and report remaining resource caches.
- **Pause, speed, reset:** control the simulation timeline or return to the initial crew and map.

## Publish with GitHub Pages

The included Actions workflow deploys the repository root to GitHub Pages when code is pushed to `main`, or when manually triggered. To publish this branch, merge it into `main`, then in the repository open **Settings → Pages** and set the build and deployment source to **GitHub Actions**. The Actions run will publish the site; its deployment summary links to the live page. For a project site, the usual URL is `https://kushjohn266-hub.github.io/System-/` after deployment.

## Project files

- `index.html` — complete responsive interface, canvas-rendered world, local agent simulation, and command console.
- `.github/workflows/pages.yml` — GitHub Actions Pages deployment workflow.
