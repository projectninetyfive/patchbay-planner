# Patchbay Planner

A free, browser-based planner for laying out studio patchbays.

List your gear, give each output a priority, pick your mixer and audio interface, and the planner lays out normalled patchbays for you: which jack goes where, what is half-normal, normal or thru, and how to patch common jobs like sampling, resampling the mix or running an effect on an insert.

**Open the planner:** https://projectninetyfive.github.io/patchbay-planner/

## What it does

- **Generates the bays** from your gear list, drawn like a real 1U front panel, with a list view for phones.
- **Built-in gear library** of around 90 synths, samplers, drum machines and effects, so most units add their outputs and inputs in one click. Anything else can be added as a blank unit.
- **"I want to…" signal paths** show the exact cords for a job, and you can draw your own patches.
- **Level checks** flag pro (+4 dBu), consumer (−10 dBV) and instrument level mismatches, and balanced vs unbalanced connections.
- **MIDI plan** suggests clock and channel routing.
- **Exports**: printable patchbay labels, a wiring checklist, a patch sheet, an SVG of the bays and a cable list as CSV.
- **Share a studio** as a link or a short code. Opening one makes a copy, so nobody's own studio is changed.
- Undo and redo, several studios side by side, and JSON backups.

It starts with an example studio built around an Akai MPC60 and a pile of vintage samplers and synths. Press **New** to start your own.

## Privacy

Everything runs in your browser. Your studios are saved in this browser's local storage and are never uploaded anywhere. Clearing your browser data removes them, so use **Download backup** to keep a copy, or to move a studio to another computer.

## Running it yourself

It is a single HTML file with no build step. Download `index.html` and open it in any modern browser, or host it anywhere that serves static files.

## Feedback and fixes

Found a wrong connection for a piece of gear, or want a unit added to the library? Open an issue on this repository with the make, model and its rear-panel outputs and inputs. Pull requests are welcome.

## Licence

MIT. See [LICENSE](LICENSE).
