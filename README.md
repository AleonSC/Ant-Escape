# Ant Escape

A small browser roguelite: your ant scurries toward the mouse cursor while the garden's bugs try to eat it. Keep it alive as long as you can.

## Play

Open `index.html` in a browser. There's no build step and nothing to install.

- **Mouse**: the ant follows the cursor
- **Click / Space**: dash (you can't be hit while dashing)
- **P / Esc**: pause
- **1 / 2 / 3**: pick a mutation on level-up

## How it works

- The ant sprays acid at the nearest bug on its own.
- Squashed bugs drop crumbs. Collect crumbs to level up and pick one of three mutations (damage, fire rate, multishot, piercing, speed, health, regen, an orbiting worker ant escort, and more).
- New enemies show up over time: spiders chase you, wasps line up and dive at you, beetles are slow and tanky, and bombardier beetles keep their distance and shoot.
- A Spider Queen boss arrives every 90 seconds.
- Sugar cubes restore one heart. Your best run is saved in the browser.

## Obstacles and traps

Each run gets a random garden layout.

- **Rocks** block you, walking bugs and all shots. Wasps fly over them. Bombardier shots break on them too, so use them as cover.
- **Honey puddles** slow down you and every walking bug.
- **Traps** are sprung by stepping on their glowing pressure pad. A dashed line links each pad to its trap. Pads recharge after use (the *Trap Engineer* mutation makes that faster).
  - **Flytrap**: snaps shut and eats every bug in its circle. The Spider Queen just loses a chunk of health.
  - **Acorn drop**: an acorn falls on the marked circle a moment later and crushes everything there, including you if you're standing in it.
  - **Sprinkler**: the pad is on the sprinkler. It sprays for a few seconds, pushing bugs away, washing out enemy shots and hurting bugs nearby.
