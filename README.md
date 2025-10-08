# 2D Hero Shooter

A fast-paced, top-down 2D hero shooter built in **HTML5 Canvas + JavaScript**.  
Players select from unique heroes with different kits, battle AI opponents, and fight to capture control points.

---

## 🎮 Gameplay

- **Hero Selection**: Choose from multiple heroes, each with distinct abilities, roles, and ammo capacities.
- **Abilities**: Core abilities are mapped to standard FPS-style controls.
- **Objective Play**: Teams fight to capture and hold the central point. Progress fills gradually to 100% for victory.
- **AI Opponents & Teammates**:
  - Maintain separation (no stacking).
  - Use abilities contextually (no spam).
  - Attempt to capture and defend points.
- **Reload & Ammo**: Each hero has unique ammo capacity and must reload strategically.

---

## 🕹️ Controls

- **WASD** – Movement  
- **Mouse (LMB)** – Primary Fire  
- **E** – Ability 1  
- **Shift** – Ability 2  
- **Q** – Ultimate  
- **R** – Reload  

---

## ✨ Heroes

- **Flux**: Projectile-based ranged attacker with gravity powers.  
- **Aegis**: Close-range defender, empowered by shield slams.  
- **Nyx**: Shadow-themed assassin with staged charge mechanics.  
- *(More heroes in development…)*

---

## 🚩 Objectives

- Stand uncontested on the point to capture it.  
- Capture progress increases slowly to **100%**.  
- If both teams are on the point → progress pauses.  
- If the enemy retakes → their progress decays yours to 0 before building their own.  
- Victory is achieved at **100% capture**.

---

## 🛠️ Development Notes

- Implemented in a **single `2d.html` file** (HTML, CSS, JS inline).  
- Current focus: gameplay polish, AI behavior, and capture logic.  
- Known improvements underway:
  - AI spacing & smarter ability usage.
  - Capture system refinement.
  - Additional hero kits and visuals.

---

## 🚀 Getting Started

Clone the repo and run locally:

```bash
git clone https://github.com/yourusername/2d-hero-shooter.git
cd 2d-hero-shooter
open 2d.html
