# Run From The Mimic

A three-lane runner (think Subway Surfers) set in a short subway tunnel with a
finish line. Survive all 5 rounds without the Mimic catching you, not even once.

## How the Mimic learns

It remembers your habits and uses them against you:

- **Where you run when its claw slams down.** It tracks, for each lane, which lane you
  flee to, and aims the next claw there. From round 3 it can slam two lanes at once
  (one lane is always left open).
- **Which way you dodge out of the middle lane.** It puts a train waiting in the
  lane you usually dodge into.
- **Jump vs. switch lanes, slide vs. switch lanes.** If you always jump barriers, a bar
  is waiting where you land. If you always slide, a barrier follows the bar.

How much it trusts its memory goes up every round. Between rounds it tells you what
it has learned. Its memory carries across attempts (saved in your browser) until
you press "Make it forget me".

## Controls

- Arrow keys / WASD, or swipe on mobile
- Left/right: switch lanes · Up: jump · Down: slide (or fast-fall mid-jump)
- Hitting an obstacle or getting clawed lets it close in; running clean lets you pull away.

## Play

Open `index.html` in a browser. Single file, no build step.
To share it, host it with GitHub Pages (Settings → Pages → deploy from branch).
