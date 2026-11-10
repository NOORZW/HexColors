# 🎨 Hex Colors

A playful website for learning hex color codes by playing with them. Mix colors, guess codes, memorize shades, race the clock, and break your keyboard on it. Every right answer earns XP, and there are 20 trophies to win.

**[Play it here](https://noorzw.github.io/HexColors/)**

> **Flashing lights warning:** Keyboard Party has an optional strobe button. It is off until you press it, flashes at most 3 times per second, and stops by itself after 6 seconds. It is hidden if your device is set to reduce motion.

## What is in it

### Games
| Game | What you do |
| --- | --- |
| **Hex Lab** | Slide red, green and blue, or type a hex code, and see shades, the opposite color and the gray version |
| **Palette Party** | Make five-color palettes (Anything, Pastel, Neon or Dark), lock the ones you love, and copy them |
| **Odd One Out** | Find the one tile that is a slightly different shade. You get 45 seconds, and the grid gets bigger and sneakier |
| **Name That Hex** | See a color, pick its hex code |
| **Which Color?** | See a hex code, pick its color |
| **Match It** | Mix a color to match the target and get a percent score |
| **Color Memory** | Memorize a color before it disappears, then mix it from memory. Five rounds, each one faster |
| **Hex Math** | Turn a hex pair like `3C` into a regular number from 0 to 255 |
| **Gradient Maker** | Build a linear or radial gradient and copy the CSS |
| **Keyboard Party** | Mash letter keys or tap the stage. The page colors go random and things pop up. Press **Space** to reset |

### Extras
- **Color of the day:** a new color every day, the same for everyone
- **XP and levels:** climb from Pixel to Crayon, Painter, Colorist, Hex Wizard and Rainbow Legend
- **Trophy Room:** 20 trophies, each with its own drawing. Locked ones show how to win them
- **Custom art:** all 31 pictures (11 game icons and 20 trophy badges) are drawn as SVG right in the code
- **Pop emoji or pop my art:** in Keyboard Party, switch between popping emoji from the full Unicode list and popping the custom art

## How hex colors work

A hex code is a color written as `#RRGGBB`: one pair of digits each for red, green and blue.

- Each pair is a number from `00` (none) to `FF` (all of it)
- Hex counts with 16 symbols: 0 to 9, then A to F
- `#FF8800` is full red, about half green and no blue, which makes orange
- When all three pairs match, you get gray

## Run it on your computer

There is nothing to install. Download `index.html` and open it in a browser.

## How it is built

- One HTML file with the CSS and JavaScript inside it
- No frameworks and no libraries
- Art is inline SVG, drawn by hand in the code
- Scores, XP, trophies and settings are saved in your browser with `localStorage`, so they stay on your device
- The rounded font is [Fredoka](https://fonts.google.com/specimen/Fredoka) from Google Fonts
- The emoji list is built when the page loads, from Unicode itself

## Put your own copy online

1. Make sure the main file is named exactly `index.html` and sits at the top level of the repo
2. Make the repo public
3. Go to **Settings → Pages**
4. Under "Build and deployment", choose **Deploy from a branch**, then branch `main` and folder `/ (root)`
5. Wait a few minutes, then open the link shown on that page

## Ideas for later

- A two-player color duel
- Hex Lab remembering your last few colors
- More trophies

## Credits

Made by [NOORZW](https://github.com/NOORZW). The chunky, playful style is inspired by the games on [neal.fun](https://neal.fun), and this project is not connected to that site.
