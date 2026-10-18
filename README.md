# Rooftop Mimic

A side-scrolling parkour game on one small rooftop level with a finish flag.
Run, jump, wall-jump and slide to the flag in all 5 rounds without the Mimic catching you, not once.

## The Mimic hides everywhere

Chimneys, vents, water tanks, billboards, dumpsters, doors. Red eyes peek out of random
hiding spots, real or fake, so you never know which one it's in. When you get close to the
one it's in, the spot shakes and it bursts out and chases you. Get far enough away
(or outlast it) and it slips into another hiding spot further ahead.

## It learns

The level splits twice (over the big building or through the alley underneath; across the
crane girders or through the corridor below). The Mimic remembers:

- **Which route you take** through each split, and hides on that route
- **Where you stop and stand still**, and hides near those places
- **Where it caught you before**

Each round it hides in more places and trusts its memory more. Between rounds it tells you
what it learned. Its memory is saved in your browser across attempts until you press
"Make it forget me".

## Controls

- Arrow keys / WASD / Space, or the on-screen buttons on a phone
- Run left/right · Jump (hold for higher) · Jump while against a wall to wall-jump
- Down while running to slide (faster than running, and fits under low beams)

## Play

Open `index.html` in a browser. Single file, no build step.
