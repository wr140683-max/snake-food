# Snake Food 🐍

Addictive HTML5 Snake game with skins, stages, gems, levels, daily challenges, and leaderboard.

**Live:** https://wr140683-max.github.io/snake-food/

## Features
- Swipe + optional D-Pad
- Easy / Normal / Hard
- 7 skins (Common → Mythic) with score or 💎 unlock
- 6 stages / maps (Classic, Forest, Neon City, Desert, Ice Cave, Void)
- Level progression + Daily Challenge
- Local leaderboard (Global / India tabs)
- Rare unlock announcement toast
- Mobile + Desktop

## Forest Stage Colors
Updated to cinematic dark forest palette (research-based):
- Background: `#1A2B1E` → `#0C1D0C`
- Food: `#A3E635` (bright lime)
- Style: deep canopy / shadowroot game UI

## Leaderboard
Currently **local** (this device). Tabs: 🌍 Global / 🇮🇳 India.

### Real worldwide leaderboard
Use **Firebase Realtime Database** or **Supabase** (free tier):
1. Create project → enable Realtime Database
2. On game over: write `{ name, score, region, date }`
3. Board tab: read top 50 ordered by score
4. Region filter for India vs Global

## Convert to APK + Google Play Store

### Recommended: Capacitor
```bash
npm install -g @capacitor/cli
mkdir snake-app && cd snake-app
npm init -y
npm install @capacitor/core @capacitor/cli @capacitor/android
npx cap init "Snake Food" com.yourname.snakefood --web-dir=www
# copy index.html into www/
npx cap add android
npx cap sync
npx cap open android
```
Then in Android Studio: **Build → Generate Signed Bundle / APK** (use AAB for Play Store).

### Play Console steps
1. Create developer account ($25 one-time)
2. Create new app → upload signed **AAB**
3. Store listing: title, short + full description, screenshots, icon 512px, feature graphic
4. Privacy policy URL (required)
5. Content rating + target audience
6. Submit for review

### Faster no-code
- https://www.htmltoapp.net/ — upload HTML/ZIP → APK
- Bubblewrap (TWA) if you add PWA manifest + service worker first

### Checklist
- [ ] Icon 512×512
- [ ] Feature graphic 1024×500
- [ ] Phone + tablet screenshots
- [ ] Privacy policy page
- [ ] Signed release AAB
- [ ] Content rating questionnaire

## License
MIT — free to use and publish.
