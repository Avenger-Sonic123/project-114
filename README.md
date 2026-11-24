# Realtime Filter — Follow-up Prototype

A follow-up snapshot of the PoseNet webcam filter exercise.

**Repository created:** 2022-03-11  
**Project status:** Learning project / historical snapshot  
**Earliest recorded commit (author date):** 2022-03-10

## Features and implementation

- Live camera rendering.
- Pose callback logging nose coordinates.
- PNG snapshot export.

## Technologies

HTML, CSS, JavaScript, Bootstrap, jQuery, p5.js, ml5.js, PoseNet.

## Project structure

| File | Purpose |
| --- | --- |
| [`index.html`](index.html) | Main page and user interface |
| [`main.js`](main.js) | Project-specific JavaScript |
| [`style.css`](style.css) | Page styling |

Key functions in the source:
- `main.js`: `gotPoses()`, `take_snapshot()`.

## Run or explore locally

```bash
git clone https://github.com/Avenger-Sonic123/project-114.git
cd project-114
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. The local server requires Python 3; browser-based dependencies may also require internet access.

Allow camera access and inspect the webcam and developer console.

## Current status and limitations

The overlay is not implemented in the checked-in JavaScript; this snapshot closely matches Project-113.

## Related project snapshots

Other repositories in this project family:
- [Project-113](https://github.com/Avenger-Sonic123/Project-113) — repository created 2022-03-11
- [mustache-thingy](https://github.com/Avenger-Sonic123/mustache-thingy) — repository created 2022-06-22

---

Source reference: [`1b0bfc50`](https://github.com/Avenger-Sonic123/project-114/tree/1b0bfc50f8efdbc84dc18be6fbc23eb668b5e492) on `main`, verified against GitHub on 2026-11-24. Documentation is based on static source review; runtime behavior has not been tested.
