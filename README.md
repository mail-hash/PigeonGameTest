# PIGEON — a one-line city

A small browser game: a pigeon drawn in a single continuous pen-and-ink line
walks, jumps, and flies around a 3D line-art city. He lives in a treehouse in
the central park.

Live: https://birdworks.ca/pigeon/

## Controls

WASD / arrows to walk and turn, Space to jump (hold Space to fly), E to peck.
Fly up and land on the treehouse platform to come home.

## Contents

- `index.html` — the whole game (Three.js, single file)
- `assets/sprites/` — 12 pigeon animation frames + treehouse, transparent PNGs
  (stand, front, walk a/b/c, peck, jump crouch/air, fly up/mid/down, landing)
- `assets/raw/` — original Higgsfield generations (white background)
- `treehouse-animations/` — 4 looping treehouse animations (mp4):
  gentle sway, falling leaf, door opening, pigeon landing
- `screenshots/` — automated test captures

## How it was made

Character frames generated with Higgsfield (nano banana pro) from Chris's
one-line pigeon reference drawings; treehouse animations with Seedance 2.5
from the treehouse sketch. Backgrounds keyed to transparency locally.
Run locally with any static server, e.g. `python3 -m http.server`.
