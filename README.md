# Walk Scene

An early browser prototype with a character, a fixed view, and a single prop. Hold **WASD** or the **arrow keys** to move. Release the keys to stop.

## Run locally

From this directory, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open http://127.0.0.1:8000/ in a browser. The demo uses built-in Canvas and requires no packages.

## Current limitations

Movement works in all four directions, and the scene view stays fixed. Diagonal speed and frame timing differ from the intended movement. The map boundary blocks travel, but the prop can be crossed under some conditions. Walk-behind rendering, direction changes, and a visible walk cycle are unfinished. The full canvas fits a desktop viewport. Narrow viewports can clip it.
