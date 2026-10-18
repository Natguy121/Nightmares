# The Lantern Road

A short dream adventure game that is secretly a fear quiz.

Players walk through a dream with a slowly dying lantern and make 10 choices
("What do you hear behind you?", "Which path do you seal forever?", ...).
Each choice quietly adds points to fear categories: darkness, being chased,
deep water, falling, swarms, being alone, being trapped, the uncanny,
decay, and the void.

When they wake up, the game gives them a **Dream Seed**: a code to paste into
ChatGPT (or any AI image generator). The seed is an image prompt, base64-encoded
so it doesn't spoil the surprise, that generates their worst nightmare from
their top fears, the place they picked, and the sky they saw.

A "plain version" button shows the readable prompt if an AI won't decode the seed.

## Play

Open `index.html` in a browser. It's a single file with no build step, and
nothing is collected or sent anywhere; all answers stay in the player's browser.
To share it, host it with GitHub Pages (Settings → Pages → deploy from branch).
