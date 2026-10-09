# 🌌 SINGULARITY: Orbital Gravity Sling

An unconventional, physics-driven HTML5 playable mobile demo exploring **Newtonian orbital gravity mechanics**, spacetime curvature visualization, and kinetic slingshot flight loops.

Developed with pure **HTML5 Canvas 2D** and the **Web Audio API** with zero external dependencies (<300ms load time).

---

## 🕹️ Core Game Mechanic
Unlike conventional arcade runners or joystick games, you do **not** steer the quantum probe directly:
* **Tap & Hold** anywhere on screen to spawn an active **Gravitational Singularity (Black Hole)**.
* Spacetime dynamically warps and curves around your finger.
* The probe enters an orbital arc calculated via Newtonian inverse-square gravity ($F = \frac{G \cdot M}{r^2}$).
* A real-time **predicted trajectory line** forecasts your slingshot path.
* **Release** your finger to catapult the probe out of orbit at supersonic tangential speeds!

---

## 🛠️ Tech Stack
* **Language:** Vanilla JavaScript (ES6+)
* **Rendering:** HTML5 Canvas 2D (Locked 60 FPS, Einstein grid curvature distortion)
* **Audio:** Web Audio API (Synthesized gravity resonance & crystal harmonics)
* **Target:** Mobile portrait-first, zero-asset instant browser play
