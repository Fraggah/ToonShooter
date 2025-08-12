# Toon Shooter

<img width="1920" height="1080" alt="toonshooter" src="https://github.com/user-attachments/assets/a673f1e0-6b51-4af6-9c2a-c40a2510c90f" />

**Genre:** Top‑Down Wave Shooter  
**Engine:** Godot Engine (GDScript)  
**Platform:** PC / HTML5  

Toon Shooter is a top‑down wave‑based shooter featuring a data‑driven weapon system, an in‑game shop for purchasing guns and upgrades, and a scalable wave director. The focus is on clean gameplay architecture, balance, and robust spawning logic.

---

## 🎮 Technical Features

- **Wave Director**: Curates enemy waves via weighted archetypes, budget curves, and pacing rules (intensity, cooldown, miniboss flags).
- **In‑Game Shop**: Purchase new weapons, ammo, health, and **permanent/temporary upgrades** (fire rate, damage, reload, move speed).
- **Data‑Driven Weapons**: JSON/Resources define DPS, spread, recoil, projectile speed, ammo behavior, and rarity tiers.
- **Projectile System**: Object pooling for bullets/explosions to avoid GC spikes; optional `RayCast2D` hitscan for rifles.
- **Enemy AI**: Steering towards player with obstacle avoidance; archetypes (chaser, ranged, tank) with distinct behaviors.
---
