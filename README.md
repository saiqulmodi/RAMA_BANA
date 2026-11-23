# Ramdhanu 3D Archery

**Live Play:** [https://saiqulmodi.github.io/ramdhanu-3d/](https://saiqulmodi.github.io/ramdhanu-3d/)

A zero-dependency, browser-based 3D tournament archery game built with **Three.js**, **Web Audio API**, and **Tailwind CSS**. Engineered for crisp 60 FPS performance across Desktop (`Keyboard + Mouse`), Mobile (`1-Thumb Touch & Scope`), and Console Controllers (`PS5 DualSense / Gamepad`).

---

## Core Gameplay & Ballistics
* **True Projectile Physics:** Real-time gravity drop (`9.81 m/s²`), arrow grain mass (`350–550 gr`), crosswind drift damping, and exact arrowhead tip-to-target-face plane intersection (`10, 8, 6, 4, 2` ring scoring).
* **Progressive Stage Loop:** Clear **5/5 hits** per stage to advance **+25m** downrange (`70m → 95m → 120m → 145m+`), earn **+1 permanent quiver arrow** per cleared stage, and cycle through **Morning Mist**, **Golden Sunset**, and **Twilight Stadium Floodlights** (with Stage 4+ uphill/downhill terrain elevation).
* **Sweet-Spot Tension Meter:** Hold draw until the circular arc meter hits the **Gold Sweet Spot** (`82%–96%` starter window) for a **+15% Steady Release** multiplier before arm-fatigue tremor sets in.

## 3 Tournament Target Disciplines
1. **Stationary (`1.00×`):** Classic long-range wind & elevation marksmanship.
2. **Rail Move (`1.25×`):** Ground-mounted motorized carriage with glowing apex turnaround bumpers (`1, 2, 3, 4+ mm/s` left/right & depth).
3. **Pendulum Arc (`1.50×`):** Overhead steel gantry suspension swinging left/right and forward/back (`5, 6, 7, 8+ mm/s`).

## Unlockable 3D Bow Armory & Daily Challenge
* **Ramdhanu Bamboo** *(Starter)* — Balanced velocity, `82%–96%` sweet spot.
* **Golden Imperial Recurve** *(Stage 3)* — `+3%` speed, widened `78%–97%` sweet spot.
* **Vajra Carbon Compound** *(Stage 5)* — `+8%` velocity, twin golden cam wheels.
* **Celestial Sovereign** *(Stage 7 or `10,000+` pts)* — `+10%` velocity, iridescent aura, `75%–98%` master sweet spot.
* **Daily Wind Challenge & Streak:** Date-seeded deterministic wind patterns (`YYYY-MM-DD`) and consecutive daily play streak tracking.

## Controls
| Input | Aim | 3.5× Rangefinder Scope | Draw & Loose |
| :--- | :--- | :--- | :--- |
| **Desktop** | Mouse Drag / `WASD` / Arrows | Hold `Right-Click` or `Shift` | Hold & Release `Space` |
| **Mobile** | Drag Canvas or `Hold & Drag Aim` | Hold `Hold Scope 3.5×` | Hold & Release `Hold & Drag Aim` |
| **Gamepad** | Left Stick / D-Pad | Hold `L1` / `L2` | Hold & Release `Cross (A)` or `R2` |
