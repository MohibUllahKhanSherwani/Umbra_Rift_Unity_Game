# UmbraRift

UmbraRift is a Unity 3D platformer built around a **dual-realm dimension swap mechanic**, where the player transitions between the **Physical** and **Spiritual** realms to navigate environments, collect items, and defeat enemies.

The core focus of the project is **gameplay mechanics**, **visibility-based interaction**, and **progressive level design** rather than narrative.

---

## Core Concept

The game world exists in two overlapping realms:

- **Physical Realm**: The default world state with limited interaction.
- **Spiritual Realm**: An alternate dimension revealing hidden paths, collectibles, and enemies.

The player can switch between realms in real time to solve traversal and combat challenges.

---

## Gameplay Mechanics

- **Realm Switching**
  - Toggle between Physical and Spiritual realms using a key-based input.
  - Objects and enemies change visibility and interactivity based on the active realm.

- **Platforming**
  - Precision jumping and movement-based challenges.
  - Realm-specific platforms and paths.

- **Combat**
  - Enemies are partially visible in the Physical realm.
  - Enemies become fully visible and damageable in the Spiritual realm.
  - Player uses slow-moving projectile orbs for combat.

- **Enemy Waves and Boss**
  - Clearing an initial enemy group spawns a portal.
  - The portal periodically spawns enemies.
  - A boss enemy appears after sustained combat.

---

## Level Design Overview

- **Level 1**
  - Introduces basic movement and platforming.

- **Level 2**
  - Introduces realm-switching.
  - Collectibles are visible only in the Spiritual realm.

- **Level 3**
  - Introduces combat mechanics.
  - Enemies require realm awareness to defeat.

---

## Controls

| Action | Key |
|------|-----|
| Move | WASD |
| Jump | Space |
| Realm Switch | Q |
| Shoot | Mouse Click |

---

## Technology Stack

- **Engine:** Unity 3D
- **Language:** C#
- **Tools:** Unity Editor, ProBuilder
- **Lighting:** Mixed real-time and baked lighting
- **AI:** Basic enemy
