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

After merging this branch into `main`, open repository **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose `main` and `/(root)`, then save. GitHub Pages will publish `index.html`; the project-site address is typically `https://kushjohn266-hub.github.io/System-/` once the deployment finishes. Pages availability and settings are controlled by GitHub and the repository owner.

## Project files

- `index.html` — responsive interface, canvas-rendered world, local agent simulation, and command console.
- `README.md` — controls and publishing instructions.
