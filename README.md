# 🥩 Hook 'n' Chew RPG

**An intense action RPG where you slice, hook, and devour your way through 6 brutal zones!**

## 🎮 Play Now

Visit: **[https://devilhero-games.github.io/devils-fest/](https://devilhero-games.github.io/devils-fest/)**

## ✨ Features

- **6 Zones** with progressive difficulty (Easy → Brutal)
- **7 Unique Heroes** with different stats and abilities
- **Wave-Based Combat** - Defeat all enemies to advance
- **3 Attack Types**:
  - 🔪 Slash - Close range AOE attack
  - 🪝 Hook - Pull individual enemies
  - 💥 Special - Powerful ability (costs SP)
- **Character Progression** - Level up, unlock premium heroes
- **Persistent Saves** - Your progress is saved locally
- **Mobile Friendly** - Touch controls & responsive design
- **Shop System** - Buy gems and coins (simulated)

## 🎯 Gameplay

### Combat
- Move with **Arrow Keys** or **WASD**
- Press **1** for Slash, **2** for Hook, **3** for Special
- Or use **Mobile D-Pad** on touch devices
- Avoid enemy attacks and stay alive!

### Zones
1. **Butcher's Alley** (Easy) - Rats & Zombies
2. **Slaughter Lane** (Normal) - Mix of enemies
3. **Meat Market** (Normal) - Chefs & Brutes
4. **Blood River** (Hard) - Boss arrives
5. **Cursed Abattoir** (Hard) - Multiple bosses
6. **Demon Kitchen** (Brutal) - Ultimate challenge

### Heroes
- **Blade Butcher** (Free) - Balanced slasher
- **Hook Master** (150g) - Tank with defense
- **Smoke Baron** (250g) - Fast ranger
- **Bone Witch** (60💎) - High attack mage
- **Blood Knight** (90💎) - Supreme tank
- **Feral Ripper** (130💎) - Berserker damage
- **Cursed Chef** (160💎) - Support specialist

## 💾 Save Data

Your progress is automatically saved in browser **localStorage**:
- Gold & Gems
- Level & XP
- Owned heroes
- Zone stars
- Unlocked zones

## 🛠️ Technical Stack

- **Pure HTML5** - No frameworks
- **Canvas API** - All graphics rendered in real-time
- **localStorage** - Persistent game state
- **Responsive Design** - Works on desktop, tablet, mobile
- **Touch Events** - Full mobile support

## 🚀 How to Host

This game is hosted on **GitHub Pages**:

1. Fork this repository
2. Go to Settings → Pages
3. Select `main` branch as source
4. Your game will be live at: `https://yourusername.github.io/devils-fest/`

## 📝 Development

The entire game is in `index.html` (single file):
- **CSS** - Styled overlay screens, HUD, controls
- **JavaScript** - Full game engine, physics, AI, UI

### Key Functions
- `update()` - Game logic each frame
- `draw()` - Render canvas
- `attack()`, `special()`, `hook()` - Combat actions
- `spawnWave()` - Enemy spawning
- `doSave()` - Persist player state

## 🐛 Known Issues

None at launch! 🎉

## 🎨 Art Style

- Pixel-art inspired characters
- Dark color palettes per zone
- Emoji for variety & charm
- Minimal but effective UI

## 📱 Mobile Tips

- Use portrait mode for best control
- D-Pad on bottom left
- Action buttons on bottom right
- Full finger control support

## 🎵 Sound

*Coming in v2.0*

## 📄 License

Free to play & modify!

---

**Made with ❤️ by Devilhero Games**

*Slash. Hook. Devour. Victory.*