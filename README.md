# BATTLEFRAME ⚡ (NOTHING OS EDITION)

A tactical top-down sci-fi fortress shooter inspired by **Galaxy Defense: Fortress TD**, redesigned with the signature **Nothing OS / Nothing Phone** industrial aesthetic. Built with HTML5 Canvas, modern CSS, and Vanilla JavaScript.

Defend the **Glyph Defensive Perimeter** piloting an advanced Ceramic-White Class-S Mecha against escalating waves of alien swarms, sprint crashers, armored carapaces, shield drones, and titan dreadnoughts.

![BATTLEFRAME](https://img.shields.io/badge/BATTLEFRAME-NOTHING%20OS-D71921?style=for-the-badge)
![HTML5 Canvas](https://img.shields.io/badge/HTML5-Canvas-FFFFFF?style=for-the-badge&logoColor=000000)
![Vanilla JS](https://img.shields.io/badge/Vanilla-JavaScript-000000?style=for-the-badge)

---

## ⬛ Nothing OS Industrial Design System

Battleframe has been completely transformed to adhere to Carl Pei's **Nothing Tech / Nothing OS** design philosophy:

* **Stark Monochrome Contrast**: Deepest OLED pitch black (`#000000`), ceramic pure white armor (`#FFFFFF`), frosted glass surfaces (`rgba(255,255,255,0.06)`), and carbon matte chassis elements.
* **Signature Nothing Red (`#D71921`)**: Active sensor dots `( ● )`, pulsing status pips, critical warning strobes, and glowing mecha visor slits.
* **Authentic Dot-Matrix Typography**: Google Fonts `'Silkscreen'` (authentic NDot dot-matrix style) for tactical headers, wave numbers, scores, and pill badges; alongside `'Space Mono'` for precision flight telemetry.
* **Glyph Interface Language**: Rounded squircles (`border-radius: 20px`), capsule pill buttons (`border-radius: 9999px`), segmented white Glyph LED light bars, and circular dotted matrix inspection platforms.
* **High-Contrast Combat Elements**: Pure white railgun laser bolts, white/crimson Prism pulse lance beams, ceramic white orbit drones, and segmented Glyph perimeter lines pulsing red under threat.

---

## 🎮 How to Play

No dependencies or installation required. Simply open `index.html` in any modern web browser (desktop, tablet, or mobile).

### Controls
| Input | Action |
| :--- | :--- |
| **`A` / `D` or `←` / `→`** | Move Mecha Left / Right (Dynamic roll banking) |
| **Touch / Drag** | Glide Mecha to Touch Position (Mobile / Tablet) |
| **Move = Straight Fire** | Fires pure straight twin railgun lasers while maneuvering |
| **Idle = Auto-Aim** | Automated targeting computer locks onto high-threat runners |
| **`Space` or Tap OD Gauge** | **( ● ) Glyph Overdrive** screen-clearing pulse (when primed) |
| **`1`, `2`, `3` or Tap** | Select Overdrive Module Upgrade |
| **`F` Key or Button** | Toggle Fullscreen Mode |
| **`ESC`** | Pause / Resume |
| **`R` / `H`** | Restart or Return to Hangar after game over |

---

## ⚡ Kinetic Arcade Feel & Systems

* **🔴 ( ● ) Glyph Overdrive**: Eliminate aliens to charge the vertical Nothing OS Glyph LED gauge. When primed, your mecha activates a pulsating white Glyph halo—press `Space` or tap the gauge to unleash a catastrophic screen-clearing shockwave.
* **🔢 Kill Streak Multiplier**: Chaining kills within 2.0 seconds stacks a `x2`, `x3`... `x8+` combo multiplier with rising melodic sine chimes and boosted scoring. Taking shield damage resets the streak.
* **⚡ Kinetic Hit-Stop & Camera Shake**: Heavy kills (Carapaces, Bosses) trigger multi-frame freeze stops and crisp directional camera jolts for tactile, crunchy arcade impact.
* **🔊 Procedural Web Audio API SFX**: Zero external audio assets—pure procedural oscillator sound effects for laser clicks, crunchy heavy kills, shield impact thuds, rising combo pings, and sub-bass Overdrive detonation sweeps.
* **🏆 Persistent Local Highscores**: Best score and peak kill streak are stored via `localStorage`, displayed in the top Hangar telemetry bar (`BEST // ...`) and on the Game Over diagnostic summary card.

---

## 🛸 7 Core Weapon Systems (Simultaneously Equippable)

You can assemble all 7 weapon systems simultaneously during a single run:

1. **🛸 Drone Swarm Hive** (`#38BDF8` Sky Cyan):
   - Orbiting autonomous combat drones that seek and engage swarms with Arc-Sting shock darts, kinetic splitters, knockback bursts, and Level 5 **Recovery Sortie Protocols** to repair shields.
2. **💎 Prism Beam Projector** (`#F43F5E` Hot Magenta):
   - High-energy periodic pulse lance charging a pre-fire tracer before unleashing a devastating 0.8s laser blast every ~2.8s, featuring refractive secondary rays, sweeping wave arcs, and incendiary scorched ground patches.
3. **🚀 Skyfire Missile Battery** (`#C084FC` Cyber Violet):
   - Shoulder-mounted pods firing homing missiles with salvo saturation, heavy armor piercing, napalm residue, and submunition cluster bomblets.
4. **⚡ Volt Arcing Coil** (`#00E5FF` Electric Cyan):
   - Cascading high-voltage lightning discharge leaping across swarms, applying **High-Voltage Lockout (Stun)** and death-nova shockwaves.
5. **🔥 Inferno Orbit Wheel** (`#FF5500` Flame Orange):
   - Spinning saw blade gears orbiting the mecha chassis, shredding contact foes, generating a flame trail, and deflecting perimeter breaches.
6. **💥 Scatter Cannon Bastion** (`#F59E0B` Amber Gold):
   - Heavy rotary flak cannon blasting wide kinetic pellet spreads, proximity detonation charges, and anti-armor bore slugs that pierce enemy hulls.
7. **🌌 Singularity Field Disruption** (`#A855F7` Void Purple):
   - Deploys gravitational black holes dragging enemies into a crushing center vortex, applying gravimetric tether slows and resonance vulnerability (+35% damage from all weapons).

---

## 🔄 Cross-Weapon Tactical Synergies (Auto-Activated)

Equipping compatible weapon pairs automatically unlocks devastating fusion synergies with on-screen fanfare and HUD badges:

* **💥 Graviton Detonation** (*Skyfire Battery + Singularity Field*):
  - Missiles implode with micro-singularities upon impact, pulling swarms together before detonating.
* **🔄 Rotary Flak Ring** (*Inferno Wheel + Scatter Bastion*):
  - Orbiting saw blade wheels fire flak pellets outward every revolution, creating a defensive shredder ring.
* **⚡ Conduit Beam Pulse** (*Volt Coil + Prism Beam*):
  - Continuous Prism Laser conducts high-voltage electric arcs along the beam to all adjacent targets.
* **🌐 EMP Shockwave Net** (*Singularity Field + Volt Coil*):
  - Gravitational black hole collapse releases a massive EMP surge, freezing and stunning all enemies in radius for 1.8s.
* **🌠 Horizon Impact Singularity** (*Skyfire Battery + Singularity Field II*):
  - Catastrophic event-horizon orbital bombardment combining cluster saturation with dual black hole collapse.

---

## 🔱 Vanguard Systems & Tactical Chips (Offense)

* **🎯 Primary Barrel Output**: Increases direct kinetic railgun damage (+25% per rank).
* **🔱 Multi-Chamber Rifling**: Adds additional railgun barrels (Twin → Triple → Quad → Quintuple volley).
* **⏩ Trigger Acceleration**: Rapid-cycle trigger overclock (+22% autofire rate per rank).
* **👁 Precision Crit Optics**: Targets structural stress points (+12% Crit Chance, 220% Critical Damage).
* **🩸 Opening Salvo Execution**: Ambush protocol (+45% damage against enemies with >70% HP).
* **💀 Low-Health Culling Bonus**: Instantly disintegrates non-boss enemies under 15% HP with `CULLED!` execution.
* **🦅 Alpha Predator Protocol**: Anti-heavy targeting (+35% damage vs Titan Boss & Carapaces).
* **🧬 Unified Emplacement Amp**: Synchronizes autonomous stations (+20% DPS to Drones, Missiles, Wheels, Coils).

---

## 🛡️ Hull & Core Engineering (Defense / Sustain)

* **🛡️ Deflector Aegis Barrier**: Expands barrier capacity (+1 Shield Cell) and releases recovery shockwaves.
* **🔋 Barrier Regen Flux**: Accelerates shield recharge delay (-20% time per rank).
* **🔧 Nanite Field Restoration**: Passive nanite swarm repair restores 1 shield cell every 14 seconds.
* **🧱 Reactive Kinetic Plating**: 30% chance to absorb breach contact damage with zero shield loss.
* **❄️ Disruption Duration Augment**: Extends Freeze, Stun, and Slow durations by +50% per rank.

---

## 👾 Enemy Archetypes & Behaviors

1. **Scout Crawler** (`Gray & Amber`): Steady baseline vanguard.
2. **Sprint Crasher** (`Crimson & Orange`): Creeps forward, then revs its thruster and **sprints** straight down the lane!
3. **Shield Drone** (`Cyan Energy Bubble`): Projects an energy shield bubble protecting itself and adjacent allies with 50% damage reduction.
4. **Armored Carapace** (`Heavy Tungsten`): High-HP heavy tank resisting non-thermal kinetic rounds.
5. **Brood Splitter** (`Toxic Emerald`): Splinters into two micro-crawlers upon destruction.
6. **Titan Behemoth Boss** (`Dreadnought`): Wave 5 boss with dual plasma cannons and an active top HUD health meter.

---

## 📜 License
MIT License. Created by [Knecrow](https://github.com/Knecrow).
