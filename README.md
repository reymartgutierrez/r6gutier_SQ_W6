# Sidequest 6 — Vertical Scrolling Shoot 'Em Up

## Setup and Interaction Instructions

To run the sketch locally, open `index.html` in Google Chrome using Live Server.

**Controls:**
- Move: WASD
- Shoot: Spacebar (shoots in the direction you last moved)
- Restart: R (after win or game over)

Dodge the dark square obstacles and shoot the orange blobs. Survive until the progress bar fills to win.

**Adding Your Own Sounds**
1. Add your sound files to `assets/sounds/`
2. In `preload()`, uncomment the `loadSound()` lines and update the file paths
3. Uncomment the `play()` or `loop()` calls in the relevant functions

**Editing the Obstacles**
Open `data/obstacles.json` to change obstacle positions and sizes. Each entry has:
- `x` — horizontal position in pixels
- `worldY` — vertical position in world coordinates (negative = higher up in the level)
- `size` — width and height of the square in pixels

**Opening the Chrome Console**
- **Windows:** Press `F12` or `Ctrl + Shift + J`, then click the **Console** tab
- **Mac:** Press `Cmd + Option + J`

## Assets

| File                                | Source
| ----------------------------------- | -----------------------------------
| 'assets/images/w6background.png' [1]| Magnific - Cartoon forest at sunset a nature inspired landscape in dark beige and green
| 'assets/images/villagercharacter.png' [2] | Flaticon - Villager free icon
| 'assets/sounds/backgroundmusic.mp3' [3] | THRLL (YouTube) - Dark Ambient - Horror Background Music No Copyright

## References

[1] Magnific AI. 2026. Cartoon forest sunset nature-inspired landscape dark beige green. Premium AI Image. Retrieved June 17, 2026 from https://www.magnific.com/premium-ai-image/cartoon-forest-sunset-natureinspired-landscape-dark-beige-green_163820150.htm

[2] Flaticon. 2026. Villager Free Icon. Retrieved June 17, 2026 from https://www.flaticon.com/free-icon/villager_9194281

[3] YouTube. 2026. oO0DvpIWhd0 Video Playlist. Retrieved June 17, 2026 from https://www.youtube.com/watch?v=oO0DvpIWhd0&list=RDoO0DvpIWhd0&start_radio=1
