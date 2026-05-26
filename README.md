# 🃏 AstralDraw — Gacha Poker

A single-file browser game combining gacha card pulling with poker hand building. No installs, no build step — just open `index.html` and play.

**[Play it live →](https://krez-dot.github.io/balacha)**

---

## How to Play

1. **Summon** cards with gems (Hand Pull ×5 or 10× Summon)
2. **Select 5 cards** from your results to form a poker hand
3. **Evaluate** the hand to earn gems back
4. **Equip Jokers** to multiply rewards — they drop from pulls
5. **Challenge Bosses** to earn Shards, then craft specific jokers in the Shop

---

## Features

- 🎴 **Gacha pull system** with pity counter (hard pity at 80, soft pity at 65)
- ♠ **Poker hand evaluation** — High Card through Royal Flush
- ⭐ **Rarity system** — 3★ / 4★ / 5★ cards with chip bonuses; 5★ cards act as wilds
- 🃏 **24 Jokers** across 3 rarities with unique effects that stack
- ⚔️ **Boss Battles** — 4 bosses with unique gimmicks; deal damage by playing poker hands
- ⚗️ **Joker Crafting** — spend boss-win Shards to craft any joker you want
- 📋 **Daily & Weekly Missions** with gem rewards
- 🏪 **Shop** — buy gem packs with Gold, exchange dupes, craft jokers
- 💾 Auto-saves to localStorage — progress persists across sessions
- 📱 **Mobile responsive**

## Bosses

| Boss | HP | Gimmick |
|------|----|---------|
| 👺 Goblin King | 2,500 | Flushes deal ×2 damage |
| 🗿 Iron Golem | 5,000 | Pairs or below deal 0 damage |
| 💀 Shadow Lich | 3,500 | Same hand twice heals it 300 HP |
| 🐉 Ancient Dragon | 10,000 | Deal 10,000 in 5 rounds or lose 2,000 gems |

## Joker Rarities

| Rarity | Drop Chance | Craft Cost |
|--------|-------------|------------|
| ★★★ | 70% | 3 Shards |
| ★★★★ | 24% | 6 Shards |
| ★★★★★ | 6% | 12 Shards |

---

Built as a single HTML file (~3,800 lines) with vanilla JS, CSS animations, and Web Audio API sfx.
