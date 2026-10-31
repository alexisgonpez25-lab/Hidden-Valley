# ⛰ The Hidden Valley

A 2D pixel-art, dark fantasy platformer made for a video game design class. The level design teaches the main mechanic, **jumping**, through the layout of the level itself, without written instructions or tutorials.

**▶ Play it here:** https://YOUR-USERNAME.github.io/REPO-NAME/

> Replace the link above with your own GitHub Pages URL.

## Controls

| Action | Keys |
|---|---|
| Move | Arrow keys or A / D |
| Jump | Space, W or ↑ (hold for a higher jump) |
| Restart level | R |
| Back to menu | Esc or the ☰ button |
| Mute / unmute music | M or the 🔊 button |

On touch devices, on-screen buttons appear automatically.

## Levels

The game has three levels. Each one is unlocked by completing the previous one.

1. **The Hidden Valley:** the original level, built from the physical cardboard prototype. It follows four stages: Introduction, Development, Twist and Conclusion.
2. **Moonlit Ridge:** more enemies and longer platforming sections.
3. **Storm Summit:** the hardest level, combining every mechanic.

## Mechanics

- **Jumping:** the core mechanic. Hold the button for a higher jump.
- **Spiky ball:** its spikes go in and out. With the spikes out it is dangerous. With them in (it turns lighter and shows a yellow ring) you can stomp it.
- **Crow:** flies in a wave pattern and can be stomped.
- **Cannon:** fires bullets every few seconds. Jump over them or stomp them. The cannon itself cannot be destroyed.
- **Spikes:** instant damage, so jump over them.
- **Crumbling platforms:** fall shortly after you step on them and come back later.
- **Jump pad:** the pink block launches you very high.
- **Water:** a safe zone. Falling in sends you back to the last checkpoint without counting as a death.
- **Lanterns:** checkpoints.
- **Optional rewards:** coins and a crystal in each level.

## Scoring

| Event | Points |
|---|---|
| Coin | 100 |
| Crystal | 500 |
| Spiky ball stomped | 200 |
| Crow stomped | 150 |
| Bullet stomped | 50 |
| Level completed | 500 |

Your best score for each level and your progress are saved in your browser.

## Settings

- **Volume** slider for music and sound effects.
- **Hitboxes** toggle, to see collision and damage boxes while you play.

## Design notes

- **Safe start:** the first section has no enemies, so the player can discover the jump freely.
- **Gradual difficulty:** each section adds one new idea instead of piling on everything at once.
- **Risk and reward:** optional rewards sit in harder spots, so the player chooses whether to risk them.
- **Visual language:** raised platforms suggest jumping, red spikes signal danger, and the glowing lanterns and the lit castle door guide the player forward.

## Tech

- A single `index.html` file with HTML, CSS and JavaScript, using the Canvas API.
- No libraries or external assets, except the *Press Start 2P* font from Google Fonts.
- Music and sound effects are generated in the browser with the Web Audio API.
- The world renders at a low resolution and is scaled up for the pixel-art look.

## Run locally

Download `index.html` and open it in any modern browser. No installation is needed.

## Credits

Level design, concept and documentation by Alexis Ivan Gonzalez Lopez.
