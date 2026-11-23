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

### Running with Python HTTP Server

For better compatibility and mobile testing, serve the game with Python's built-in HTTP server:

```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Then open `http://localhost:8000` in your browser.

### Testing on Mobile

1. **Start the Python server** on your computer (see above)
2. **Find your computer's local IP address:**
   - **macOS/Linux:** `ifconfig | grep "inet "` (look for 192.168.x.x)
   - **Windows:** `ipconfig` (look for IPv4 Address)
3. **Connect your phone to the same WiFi network** as your computer
4. **Open your phone's browser** and visit: `http://YOUR_IP_ADDRESS:8000`
   - Example: `http://192.168.1.100:8000`

The game will automatically enter fullscreen landscape mode on mobile.

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

Based on the classic Atari Asteroids (1979), as a starting point some code-pen examples was used ( MIT license ). Built as a learning project for HTML5 game development.
