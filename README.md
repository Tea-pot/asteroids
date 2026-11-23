# Asteroids

A classic Asteroids-style space shooter built with HTML5 Canvas, optimized for desktop and mobile with touch controls and gamepad support.

## How to Play

**Goal:** Survive as long as possible. Destroy asteroids and UFOs to score points.

### Controls

- **Desktop:** Move mouse to steer ship, hold mouse button to fire
- **Mobile:** Left joystick to move, right fire button to shoot (hold for rapid fire)
- **Gamepad:** Left stick to move, A button or RT to fire

### Gameplay

- Asteroids break into smaller pieces when hit
- UFOs drop special weapons (limited ammo shown in top-left pie chart)
- Collision with asteroids or UFOs = game over
- **Score:** 10pts per hit, 50pts per asteroid destroyed, 300pts per UFO destroyed

### Special Weapons

- **TINY BEAM** - Rapid fire, low damage
- **BLASTER** - High damage, medium fire rate
- **LASER** - Pierces through multiple targets
- **EXPLOSION BEAM** - Area damage on impact

Press **START** to begin. Mobile automatically switches to fullscreen landscape mode.

## Features

- Pure HTML5/Canvas - no external dependencies
- Responsive controls: mouse, touch, and gamepad support
- Mobile-optimized virtual joystick + fire button
- Fullscreen landscape mode on mobile
- Special weapons with visual ammo indicator
- Particle effects and smooth animations

## Running Locally

Simply open `index.html` in a modern web browser. No build process required.

```bash
# Clone the repository
git clone https://github.com/Tea-pot/asteroids.git
cd asteroids

# Open in browser (or use any local server)
open index.html
```

## Mobile Setup

For the best mobile experience:
1. Add to home screen (iOS/Android)
2. Launch from home screen icon
3. Game will automatically enter fullscreen landscape mode

## Tech Stack

- Vanilla JavaScript (ES5)
- HTML5 Canvas API
- CSS3 (media queries for responsive controls)
- Gamepad API for controller support

## License

MIT License - feel free to use and modify as you like.

## Credits

Based on the classic Atari Asteroids (1979), as a starting point some code-pen examples was used ( MIT licence ). Built as a learning project for HTML5 game development.
