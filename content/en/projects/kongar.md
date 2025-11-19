---
title: "Kongar Awakening"
date: 2024-01-01
tags: ["C++", "Unreal Engine", "AI", "UnReleased", "ARPG", "GAS"]
summary: "GAS-based Action RPG - Vertical slice development and massive performance optimization."
translationKey: "kongar_project"
---

### Project Details
I served as the **Lead Programmer** at **Vasanta Games** for the **Action RPG** game **Kongar**, which was in development. Although I had only produced environment visuals in the previous development cycle (1 year), I developed a **vertical slice and playable demo** within 4 months, making the project production-ready.

**Project Rescue & Rapid Prototyping:**
* Joined project after 1 year of unproductive development cycle
* **Produced vertical slice and playable demo from scratch within 4 months**, proving project viability
* Brought core gameplay loop, combat mechanics, and RPG systems to fully functional state
* Enabled rapid iteration and feature expansion through modular architecture

**Gameplay Ability System (GAS) Implementation:**
* Set up and configured **Unreal Engine GAS from scratch for single-player**
* Designed ability system, attribute sets, gameplay effects, and gameplay tags architecture
* Created scalable combat and progression systems with modular ability design
* Implemented custom gameplay cues and effect execution calculations

**Core RPG Systems:**
* Built **quest system** (objective tracking, branching quests, quest state management)
* Developed **dialog system** (conversation trees, branching dialogue, NPC interaction)
* Created designer-friendly toolset with modular, data-driven design
* Implemented quest-dialog integration through event-driven architecture

**Combat & Boss Fight Systems:**
* Developed **melee combat system** (combo chains, hitbox detection, damage calculation)
* Designed and implemented **boss fight mechanics** (phase transitions, attack patterns, telegraphing)
* Established ability-based combat flow with GAS integration
* Created animation-driven combat events and hit reactions system

**Inventory & Equipment Systems:**
* Developed **inventory management system** (item stacking, sorting, capacity management)
* Built **equipment system** (stat modifications, visual equipment, loadout management)
* Integrated equipment stat bonuses with GAS attribute system
* Designed data-driven item definitions and rarity systems

**Mount System:**
* Developed **horse mounting mechanics** (smooth mount/dismount transitions, mounted combat)
* Implemented IK-based rider positioning and procedural animation blending
* Built physics-based horse movement and terrain adaptation system

**Massive Performance Optimization (20 FPS → 100 FPS):**
* Optimized **16 km² open-world map** from 20 FPS to 100 FPS (%400+ improvement)
* Applied **Nanite** conversion and mesh optimization strategies
* Reduced vegetation rendering overhead through **WPO (World Position Offset) optimization**
* Performed shader complexity reduction and material instance optimization
* Minimized draw calls with **texture atlas** systems
* Optimized foliage and prop rendering through **ISM (Instanced Static Mesh)** conversion
* Applied culling strategies, LOD transitions, and streaming optimization
* Identified and resolved rendering bottlenecks through GPU profiling

**Architecture & Code Quality:**
* Designed all systems to be **fully modular** and loosely coupled
* Ensured maintainability and extensibility through component-based design
* Simplified designer workflow with data-driven architecture
* Applied clean code principles and SOLID principles

[Trailer](https://www.youtube.com/watch?v=t8wjeg1qneE)