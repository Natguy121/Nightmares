# The Midnight Carnival

A short horror game that is secretly a fear quiz.

Players wander an abandoned carnival at midnight (carousel, hall of mirrors,
funhouse, fortune teller, ghost train, Ferris wheel...) while something follows
them. They make 10 choices, and each one quietly adds points to fear categories:
darkness, being chased, deep water, falling, swarms, being alone, being trapped,
the uncanny, decay, and the void.

At the end the creature "learns their face" and the game gives them a
**Dream Seed**: a code to paste into ChatGPT (or any AI image generator). The seed
is a base64-encoded image prompt for an extreme close-up of **the nightmare's
face**, built from their top three fears, where the carnival was, and the sky
they saw. A "plain version" button shows the readable prompt if an AI won't
decode it.

Animations: drifting fog, glowing eyes that appear in the dark (more and redder
as the night goes on), screen shake and red flash on jump-scare choices,
glitching title, and a face that forms out of the dark at the end. Respects
"reduce motion" settings.

## Play

Open `index.html` in a browser. It's a single file with no build step, and
nothing is collected or sent anywhere; all answers stay in the player's browser.
To share it, host it with GitHub Pages (Settings → Pages → deploy from branch).
