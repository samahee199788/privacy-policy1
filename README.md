# FridgeChef

A small, responsive browser prototype for finding simple recipes from ingredients you already have.

## Run locally

From the repository root, start a static server:

```sh
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000). Pantry items, saved recipes, and shopping-list entries are stored in the browser's local storage. This prototype uses sample recipes and does not call an AI or external service.

In the recipe navigation, the arrow keys move focus between tabs; press Enter or Space (or click) to activate the focused tab.

## Browser smoke test

With the static server running, open [http://localhost:8000/tests/smoke.html](http://localhost:8000/tests/smoke.html). The page checks pantry matching, corrupted-storage recovery, recipe instructions and favorites, shopping-list persistence, and keyboard navigation in an embedded browser frame. It reports PASS or FAIL.
