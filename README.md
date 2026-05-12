# Fatal Labyrinth — Tribute

A browser-based tribute to SEGA's 1990 roguelike **Fatal Labyrinth**. Descend 30 floors of a procedurally generated dungeon, fight monsters, manage hunger, and retrieve the Holy Goblet from the Ancient Dragon.

Built as a single HTML file using Copilot Cowork (code) and ChatGPT (sprites + music).

![Fatal Labyrinth](screenshot.png)

---

## How to Run

No build step, no dependencies. Just open the file in a browser.

1. Download or clone this repo.
2. Open `fatal-labyrinth.html` in any modern browser (Chrome, Firefox, Edge, Safari).
3. Pick a difficulty and play.

> **Note:** Browsers may block local audio autoplay. Music starts after you click a difficulty button.

---

## How to Play

You start with a rusty dagger and some food. Your goal: reach floor 30 and defeat the Ancient Dragon to claim the Holy Goblet.

### Controls

| Action | Keys |
|---|---|
| Move | Arrow keys or `W` `A` `S` `D` |
| Wait one turn | `.` or `Space` |
| Pick up item | `G` |
| Use / equip item | `1` – `9` |
| Drop item | `Shift` + `1` – `9` |
| Save game | `F5` |
| Load game | `F9` |

### Tips

- **Equip your dagger early** — press `1` on the first turn. Unarmed combat is rough.
- **Eat before you starve.** When the hunger bar drops low, eat bread or roast meat.
- **Equipped items stay in your inventory** with an `[E]` marker — using the same slot again unequips them.
- **Scrolls are powerful.** A Scroll of Blast can clear a room. A Scroll of Map reveals the entire floor.
- **The Ancient Dragon teleports you** every 5–8 turns and breathes fire at range. Save your healing potions.

### Difficulty

| Tier | Description |
|---|---|
| Easy | Weaker monsters, more HP, more loot, slower hunger |
| Normal | The classic experience |
| Hard | Tougher monsters, less HP, less loot |
| Very Hard | Brutal — for veterans only |

---

## Credits

- **Code:** Generated with [Copilot Cowork](https://copilot.cloud.microsoft/cowork)
- **Sprites & music:** Generated with ChatGPT
- **Inspiration:** SEGA's *Fatal Labyrinth* (1990)

## License

MIT — feel free to fork, modify, and learn from it.
