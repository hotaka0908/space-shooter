# Space Shooter

A retro-style space shooter game built with HTML5 Canvas and vanilla JavaScript.

## Play Now

https://space-shooter-b5m9c43ox-hotakas-projects.vercel.app

## Features

- Space shuttle with engine flame animation
- 3 enemy types with unique behaviors:
  - **UFO** (100pts) - Wobbles side to side
  - **Asteroid** (200pts) - Rotates while falling
  - **Alien** (300pts) - Chases the player
- Level system - difficulty increases every 10 enemies passed
- Retro sound effects using Web Audio API
- High score saved to localStorage
- Share your score on X (Twitter)
- Mobile touch controls

## Controls

### PC
| Key | Action |
|-----|--------|
| ← → | Move left/right |
| ↑ / Space | Shoot |

### Mobile
- **◀ ▶** buttons to move
- **FIRE** button to shoot
- Tap screen to start

## Tech Stack

- HTML5 Canvas
- Vanilla JavaScript
- Web Audio API (no external sound files)
- CSS3

## Local Development

```bash
# Clone the repository
git clone https://github.com/hotaka0908/space-shooter.git

# Open in browser
open index.html

# Or start a local server
python3 -m http.server 8080
```

## License

MIT
