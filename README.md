# The Not So World's Hardest Game

A browser arcade game about collecting every green coin while dodging red hazards. Reach the exit to clear a stage, earn yellow bonus coins, unlock player skins, and work through seven difficulty levels with 100 stages each.

## Play

Open [index.html](index.html) in a browser and press **Play**.

- Move with the arrow keys, `WASD`, or `ZQSD`.
- Press `R` to restart the current stage.
- Collect every green coin before entering the exit.
- Use power-ups to survive difficult layouts.
- On touch devices, use the on-screen joystick.

Progress is saved automatically in the browser, including unlocked skins, bonus coins, deaths, and your best stage time. The save belongs to that browser on that device.

## Run locally

No build step or dependencies are required. From this folder, either double-click `index.html` or run a simple local server:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Project notes

The game is intentionally self-contained in `index.html`: HTML, styling, canvas rendering, game rules, audio, and touch input all live together so it is easy to share and host as a static page.