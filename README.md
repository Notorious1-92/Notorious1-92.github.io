# 🎮 Ivan's Browser Game Portfolio

Hey! Welcome to my portfolio repository. I'm a browser game developer who builds fully playable games that run directly in your browser — no downloads, no installs, no setup. Just click a link and play.

Every game in this repo is a **single self-contained HTML file.** That means all the game logic, physics, sound, and visuals are written from scratch in one place using nothing but HTML5, JavaScript, and the Web Audio API.

---

## 🕹️ How to Play

You have two options:

**Option 1 — Play online (recommended)**  
Visit the live portfolio: **https://Notorious1.github.io**  
Click any game card and it opens instantly in your browser.

**Option 2 — Run locally**  
1. Click the green **Code** button on this page
2. Select **Download ZIP**
3. Unzip the folder
4. Open any `.html` file directly in your browser — that's it

No terminal. No `npm install`. No server needed.

---

## 🗂️ What's in this repo

| File | Game | Genre |
|---|---|---|
| `spiderman_swing.html` | Web Rush | Action / Traversal |
| `god_of_war_rpg.html` | Spartan's Wrath | Action RPG |
| `skate_game.html` | Skate or Die | Skateboarding |
| `BlactopBrawlers.html` | Blacktop Brawlers | Arcade Sports |
| `DragonBattleZ.html` | Dragon Battle Z | Fighting |
| `SuperClaudeo.html` | Super Claudeo Bros | Platformer |
| `index.html` | Portfolio site | — |

---

## 🕷️ Web Rush
*Inspired by Spider-Man*

Swing through the city using real pendulum physics. Your web anchors to whatever surface you aim at, and your momentum carries you forward. Take out enemies mid-swing, collect pickups, and chain combos to top the leaderboard. Every sound — the web snap, the thwip, the crunch of a landing — is generated live in code. No audio files anywhere.

**Controls:** `Mouse` to aim and shoot web · `Space` to release

---

## ⚔️ Spartan's Wrath
*Inspired by God of War*

Fight through 6 waves of enemies with a full combat system — attack, block, dodge, and 4 unlockable skills. The difficulty escalates wave by wave and ends with boss encounters against Ares and Zeus. Land enough hits to fill your Rage meter and unleash your most powerful move.

**Controls:** `A` Attack · `S` Block · `D` Dodge · `1–4` Skills

---

## 🛹 Skate or Die
*Inspired by Tony Hawk's Pro Skater*

You have 2 minutes. Hit quarter-pipes, grind rails, pull off manuals, and land wallrides to stack your combo multiplier as high as it'll go. Bail and you lose your combo. The trick meter fills a special move slot — use it at the right moment. Your best scores are saved to a local leaderboard.

**Controls:** `Arrow keys` to move · `Z X C` for tricks · `S` Manual

---

## 🏀 Blacktop Brawlers
*Inspired by NBA Street Vol. 2*

3-on-3 street basketball with 8 characters, each with unique stats and a signature special move. The CPU reads the game — it knows when to drive for a dunk, when to pull up for three, and when to get aggressive if it's losing. Pick your squad, choose a court, and run it.

**Controls:** `Arrow keys` to move · `Z` Pass · `X` Shoot · `C` Special

---

## 🐉 Dragon Battle Z
*Inspired by Dragon Ball Sparking Zero*

1v1 fighter with a full ki system. Build meter by landing hits, spend it on ki blasts, or hold it for a fully charged Ultimate Move. Fights go aerial — double jump into combos and juggle your opponent. Best of 3 rounds wins. Every punch, blast, and super is a layered synthesized sound built with the Web Audio API.

**Controls:** `Arrow keys` to move · `Z` Punch · `X` Ki Blast · `C` Ultimate

---

## 🎮 Super Claudeo Bros
*Inspired by Super Mario Bros*

A classic side-scrolling platformer with a scrolling camera, parallax backgrounds, enemies to stomp, coins to collect, question blocks to hit, and a lives system. Built entirely on canvas with no libraries — every frame is drawn by hand.

**Controls:** `Arrow keys` to move · `Space` to jump

---

## 🛠️ How it's built

If you're a developer and want to look under the hood, here's the approach used across every game:

- **HTML5 Canvas** handles all the rendering — characters, backgrounds, particles, and UI are all drawn with the 2D canvas API every frame
- **Vanilla JavaScript** powers the game logic — physics, collision detection, enemy AI, state machines, and combo systems, all written from scratch
- **Web Audio API** generates every sound effect in real time using oscillators, frequency envelopes, and layered waveforms — no audio files are loaded anywhere
- **localStorage** saves leaderboards and high scores between sessions

There are no frameworks, no game engines, no external libraries, and no build tools. The goal was to prove that a genuinely fun, polished game experience is achievable with just the platform itself.

---

## 👤 About me

I'm a browser game developer focused on recreating the feel of iconic console and arcade games in the browser. I care about getting the details right — the screen shake that lands with a punch, the combo system that makes you want one more run, the sound design that sells every hit without a single audio file.

I'm open to game dev roles, freelance work, and game jams.

- 🌐 Portfolio: file:///C:/Users/Ivan/Downloads/portfolio.html
- 📬 Email: elmontro201@gmail.com
- 💼 LinkedIn: https://linkedin.com/in/yourhandle

---

## 📄 License

All games and code in this repository were written by me. Feel free to look through the code and learn from it. Please don't re-upload or redistribute the games as your own work.

---

*Thanks for stopping by — hope you enjoy the games!*
