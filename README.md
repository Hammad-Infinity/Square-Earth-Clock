# Square Glow Watch

A single-file, dependency-free analog clock rendered in SVG. Time is displayed through nested square outlines that grow from the center, with glowing hands and a click-triggered light ripple. Watch [Demo](https://hammad-infinity.github.io/Square-Earth-Clock/).

## Features

- Nested square rings for hours, minutes, and seconds
- Glowing active hand segments
- Hour tick marks along the outer edge, with longer marks at 12, 3, 6, and 9
- Click or tap the clock face to trigger a ripple animation
- Light and dark themes with a toggle button
- Responsive sizing that adapts to viewport width and height
- Safe-area inset support for notched displays
- No build step, no dependencies, no external assets

## Requirements

A modern web browser with support for SVG, CSS transitions, and CSS custom properties.

## Usage

Open `Square Glow Watch.html` in a browser.

- The clock starts automatically and updates every second.
- Click or tap anywhere on the clock face to play the ripple animation.
- Click or tap the button in the top-right corner to switch between the dark and light themes.

## Files

| File | Description |
| --- | --- |
| `Square Glow Watch.html` | The complete application: markup, styles, and script in a single file |

## Notes

- Time is read from the device's local clock.
- The theme defaults to dark on load and is not persisted between sessions.
- The hour hand uses a 12-hour cycle.

## License

This project is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0). See the [GNU AGPL-3.0 license text](https://www.gnu.org/licenses/agpl-3.0.html) for details.
