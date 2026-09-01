# sands-player

Live prototypes for the **Player** surface in the conference app (SandS Media).

Root is an index, not a prototype. Each prototype lives in its own folder, so a new
one is added — never swapped in over the last one. Everything under `flows/` is an
annotated user-flow prototype.

| Path | What it is | Link |
|---|---|---|
| `/` | Index of every Player prototype in this repo. | [open](https://tcappelletti-stack.github.io/sands-player/) |
| `/tracks/` | **Tracks & filters** — session cards, session detail, active filter pills, web/native card parity. | [open](https://tcappelletti-stack.github.io/sands-player/tracks/) |
| `/flows/` | Annotated user flows — one folder per epic (`flows/epic1/`) or per ticket (`flows/PROD-xxxx/`). None published yet. | — |

All prototypes are self-contained single-file HTML — no build, no install, no login.

**All prototypes:** [sands-prototypes](https://tcappelletti-stack.github.io/sands-prototypes/)

## Notes

- Prototypes are design artefacts, not production code — they mock data and interactions to make the intended behaviour unambiguous. Where a flow and the current build disagree, the flow is the request.

## Adding a prototype

Create a folder, drop in `index.html`, add a row to the table above and a card to the
root `index.html`. Never overwrite an existing prototype's folder — the links are shared.

## Updating

Replace the relevant `index.html` and commit. GitHub Pages redeploys automatically.
