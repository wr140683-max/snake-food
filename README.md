# 🐍 Snake Food

Modern, addictive, **full-screen** Snake game built for mobile (Play Store style).

**Repo:** https://github.com/wr140683-max/snake-food  
**Play:** Open `index.html` or deploy to Netlify / GitHub Pages.

---

## Features

### Controls (Play Store style)
- **Primary:** Swipe anywhere on the board to turn
- **Optional D-Pad:** Tap the "D-Pad" button to show/hide on-screen arrows
- Keyboard: Arrow keys / WASD
- Space = Pause / Resume

### Gameplay
- Classic Snake with **combo system** (keep eating to build x2, x3, x4)
- Golden **2x power-up** (temporary multiplier + speed boost)
- **Near-miss** warning (red edge glow when close to wall)
- Score milestones celebration (10, 25, 50...)
- Soft progressive speed (Easy / Normal / Hard)
- Local best score (saved in browser)

### Feel
- Segmented glowing snake with directional eyes
- Particle bursts + screen shake
- Motion trail
- Haptic feedback on mobile
- Wake Lock (screen stays on while playing)

### UI
- Clean dark theme
- Full-screen oriented play area
- Instant restart after Game Over
- NEW BEST celebration

---

## How to Play

1. Choose difficulty (Easy / Normal / Hard)
2. Tap **Play** or just **swipe** on the board
3. Swipe to change direction
4. Eat red food → grow + score
5. Build **combos** by eating continuously
6. Grab golden orbs for x2 multiplier
7. Don't hit walls or yourself

---

## Future Ideas (from research)

Popular modern Snake games on GitHub add:

| Feature | Why it helps retention |
|--------|------------------------|
| **Levels / Stages** | Progressive goals (eat 10 → next stage) |
| **Themes / Skins** | Unlock neon, matrix, forest, etc. |
| **Obstacles** | Appear after certain score |
| **Multiple food types** | Slow-mo, magnet, invincible |
| **Daily challenge** | "Score 30 today" |
| **Local leaderboard** | Top 5 scores |
| **Wrap-around mode** | Optional no-wall mode |

These can be added later without breaking the current core loop.

---

## Deploy

- **Netlify:** Drag & drop the folder or connect this repo
- **GitHub Pages:** Settings → Pages → Deploy from `main`
- Or just open `index.html` in any browser

---

## License

MIT – free to use, modify, and share.
