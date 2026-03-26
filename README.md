# Blue

A minimalist browser-based flappy game set in a scrolling city. Navigate a blue bird through gaps between downtown buildings the further you fly, the denser the skyline gets.

Built with vanilla HTML5 Canvas. No dependencies, no build step.

---

## How to play

| Control | Action |
|---|---|
| `Space` or `↑` | Flap |
| Click / Tap | Flap |
| Play button (top right) | Start / stop |

- Tap or press space to flap upward
- Let go and the bird glides down
- Fly through the gap between each pair of buildings
- Each building pair you clear scores one point
- Hit a building or the ground and it's over

Your best score is remembered for the session.

---

## Visuals

The game uses a muted, layered city aesthetic across three randomised colour palettes each run has a different mood. The background features:

- Parallax skyline with silhouetted buildings at three depths
- Telephone poles with shoes on the wires
- Scrolling street-level ground with trees
- A detailed animated blue bird with wings, crest, eye shine, and feet

---

## Installation

No install needed it's a single HTML file.

**Run locally:**

```bash
# Clone the repo
git clone https://github.com/your-username/blue.git
cd blue

# Open directly in your browser
open blue.html
```

Or just drag `blue.html` into any browser window.

**Serve with a local server (optional):**

```bash
# Python
python3 -m http.server 8000

# Node (npx)
npx serve .
```

Then visit `http://localhost:8000/blue.html`.

---

## Mobile

Works on iPhone and iPad out of the box tap anywhere on the canvas to flap. The game scales to fill the screen in both portrait and landscape orientations.

---

