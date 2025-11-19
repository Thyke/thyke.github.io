---
title: "Kongar Awakening"
date: 2024-01-01
tags: ["C++", "Unreal Engine", "AI", "UnReleased", "ARPG", "GAS"]
summary: "GAS-based Action RPG - Vertical slice development ve massive performance optimization."
translationKey: "kongar_project"
---

### Proje Detayları
**Action RPG** türünde geliştirilmekte olan **Kongar** projesinde, **Vasanta Games** bünyesinde **Lead Programmer** olarak görev aldım. Daha önceki development cycle'da (1 yıl) sadece environment art üretilmiş olmasına rağmen, **4 aylık sürede vertical slice ve playable demo** geliştirerek projeyi production-ready hale getirdim.

**Proje Kurtarma & Hızlı Prototyping:**
* 1 yıllık unproductive development cycle sonrası projeye katıldım
* **4 ay içinde sıfırdan vertical slice ve playable demo** üreterek project viability'yi kanıtladım
* Core gameplay loop, combat mechanics ve RPG systems'i fully functional hale getirdim
* Modular architecture sayesinde rapid iteration ve feature expansion sağladım

**Gameplay Ability System (GAS) Implementation:**
* **Unreal Engine GAS'ı sıfırdan single-player** için kurdum ve yapılandırdım
* Ability system, attribute sets, gameplay effects ve gameplay tags architecture'ı tasarladım
* Modular ability design ile scalable combat ve progression systems oluşturdum
* Custom gameplay cues ve effect execution calculations implement ettim

**Core RPG Systems:**
* **Quest system** kurdum (objective tracking, branching quests, quest state management)
* **Dialog system** geliştirdim (conversation trees, branching dialogue, NPC interaction)
* Modular ve data-driven design ile designer-friendly toolset oluşturdum
* Event-driven architecture ile quest-dialog integration sağladım

**Combat & Boss Fight Systems:**
* **Melee combat system** geliştirdim (combo chains, hitbox detection, damage calculation)
* **Boss fight mechanics** tasarlayıp implement ettim (phase transitions, attack patterns, telegraphing)
* GAS integration ile ability-based combat flow kurdum
* Animation-driven combat events ve hit reactions sistemi oluşturdum

**Inventory & Equipment Systems:**
* **Inventory management system** geliştirdim (item stacking, sorting, capacity management)
* **Equipment system** kurdum (stat modifications, visual equipment, loadout management)
* GAS attribute system ile equipment stat bonus integration'ı yaptım
* Data-driven item definitions ve rarity systems tasarladım

**Mount System:**
* **At binme mekanizması** geliştirdim (smooth mount/dismount transitions, mounted combat)
* IK-based rider positioning ve procedural animation blending implement ettim
* Physics-based horse movement ve terrain adaptation sistemi kurdum

**Massive Performance Optimization (20 FPS → 100 FPS):**
* **16 km² open-world haritasını** 20 FPS'den 100 FPS'e çıkardım (%400+ improvement)
* **Nanite** conversion ve mesh optimization strategy'leri uyguladım
* **WPO (World Position Offset) optimization** ile vegetation rendering overhead'ini azalttım
* Shader complexity reduction ve material instance optimization yaptım
* **Texture atlas** sistemleri ile draw call'ları minimize ettim
* **ISM (Instanced Static Mesh)** conversion ile foliage ve prop rendering'i optimize ettim
* Culling strategies, LOD transitions ve streaming optimization uyguladım
* GPU profiling ile rendering bottleneck'leri tespit edip çözüm ürettim

**Architecture & Code Quality:**
* Tüm sistemleri **fully modular** ve loosely coupled şekilde tasarladım
* Component-based design ile maintainability ve extensibility sağladım
* Data-driven architecture ile designer workflow'unu kolaylaştırdım
* Clean code principles ve SOLID principles uyguladım

[Trailer](https://www.youtube.com/watch?v=t8wjeg1qneE)