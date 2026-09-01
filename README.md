# sands-player

Live prototypes for the **Player** surface in the conference app (SandS Media).

Root is an index, not a prototype. Each prototype lives in its own folder, so a new
one is added — never swapped in over the last one. Inside a prototype folder, `flow/`
is the annotated user-flow version of that same prototype.

| Path | What it is | Link |
|---|---|---|
| `/` | Index of every Player prototype in this repo. | [open](https://tcappelletti-stack.github.io/sands-player/) |
| `/tracks/` | **Tracks — BASTA programme** — the programme surface: session cards, filters and the session detail. | [open](https://tcappelletti-stack.github.io/sands-player/tracks/) |
| `/tracks/flow/` | **Tracks — track display logic** — annotated state-and-transition frames for how tracks are displayed and filtered. | [open](https://tcappelletti-stack.github.io/sands-player/tracks/flow/) |

All prototypes are self-contained single-file HTML — no build, no install, no login.

**All prototypes:** [sands-prototypes](https://tcappelletti-stack.github.io/sands-prototypes/)

## Notes

- Prototypes are design artefacts, not production code — they mock data and interactions to make the intended behaviour unambiguous. Where a flow and the current build disagree, the flow is the request.

## Adding a prototype

Create a folder, drop in `index.html`, and add a row to the table above and a card to
the root `index.html`. Its annotated flow goes in `<folder>/flow/index.html`. Never
overwrite an existing prototype's folder — the links are shared.

## Updating

Replace the relevant `index.html` and commit. GitHub Pages redeploys automatically.
