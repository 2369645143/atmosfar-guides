---
title: "ATMOSFAR Co-op Multiplayer Guide: 4-Player Sessions"
description: "Master 4-player co-op in ATMOSFAR. Learn squad crew roles for the Cloud Cruiser, how to host private flight sessions, and resolve connection errors."
category: "Multiplayer Co-op"
badge: "PVE MULTIPLAYER • OCT 2026"
readingTime: "5 min read"
publishDate: "2026-10-16"
updatedDate: "2026-10-16"
icon: "ri-team-line"
lang: "en"
---

**ATMOSFAR** is engineered from the ground up for cooperative aerial teamwork. While solo flight is completely viable, operating a massive **Cloud Cruiser** mobile airbase while defending against aggressive aerial fauna becomes infinitely more manageable when coordinating across a specialized 4-player squad.

This guide details recommended crew specializations, multiplayer session setup, and proven fixes for common peer-to-peer network drops.

---

## The Four Essential Squad Roles

To maintain an operational fleet in hostile sky biomes, assign your 4-player crew into distinct flight disciplines:

### 1. Cloud Cruiser Helmsman (Commander)
* **Primary Station**: Main bridge flight console.
* **Responsibilities**: Navigation between floating island clusters, adjusting cruising altitude to avoid severe turbulence, and orienting the carrier's defensive turrets toward incoming hostiles.

### 2. Fleet Engineer & Power Architect
* **Primary Station**: Engine reactor room & battery conduits.
* **Responsibilities**: Managing reactor energy balancing between shields, engine plasma output, and life-support oxygen scrubbers. Instantly repairs blown capacitors during electromagnetic cloud storms.

### 3. Lead Scout Pilot (Wasp Specialist)
* **Primary Station**: Forward catapult landing bay.
* **Responsibilities**: Launches in the high-mobility Wasp craft to scout uncharted islands, deploy landing beacons, and retrieve high-value salvage pods too delicate for the heavy cruiser to approach.

### 4. Expedition Salvager & Ground Gunner
* **Primary Station**: Winch airlock & point-defense turrets.
* **Responsibilities**: Descends onto island surfaces via grapple ropes to mine mineral veins, fend off ground predators, and hook cargo crates directly into the carrier's retrieval nets.

---

## Hosting & Joining Co-op Flight Sessions

ATMOSFAR utilizes the **Steam P2P Networking Infrastructure**:
1. **Hosting a World**: From the main menu, select *Launch Expedition* -> *Host Co-op Session*.
2. **Setting Privacy**: Choose between *Friends Only* or *Invite Code*. We strongly recommend password-protecting private airbases during Early Access.
3. **Save Ownership**: The host player permanently retains world progression, island discovery coordinates, and Cloud Cruiser modular construction. Client players retain personal gear, suit upgrades, and custom Wasp airframe loadouts.

---

## Troubleshooting Multiplayer Drops & Connection Errors

If your squad encounters connectivity hitches during high-speed fleet formations:
* **NAT Type Traversal**: Ensure Steam's client ports (UDP 27000-27100) are forwarded or permitted in Windows Defender Firewall.
* **Host Bandwidth Allocation**: Because physics for the Cloud Cruiser are calculated on the host machine, ensure the player with the lowest ping and highest upload bandwidth hosts the session.
* **Reconnection to Moving Carrier**: If a teammate disconnects while airborne, they will safely respawn inside the Cloud Cruiser's medical bay upon rejoining rather than falling through the sky.
