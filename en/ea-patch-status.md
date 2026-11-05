---
title: "ATMOSFAR EA Patch Status: 1.0-8, 1.0-9 & Experimental"
description: "Check reactor recovery, inventory changes and EA 1.0-10 experimental features without confusing preview changes with the default branch."
category: "Early Access Guides"
badge: "SOURCE CHECK · EA"
readingTime: "4 min read"
publishDate: "2026-11-03"
updatedDate: "2026-11-05"
sourceNote: "Official material, original community replies and editorial advice are distinguished below. Checked 2026-11-03; not our own release-build playtest."
icon: "ri-compass-line"
lang: "en"
---

<h2 id="ea-1-0-8">EA 1.0-8: inventory and core handling</h2>

**Official patch, checked November 3.** The [developer notes](https://store.steampowered.com/news/app/1798230/view/712290761518876903) list an inventory-related crash fix (VENU-14237), several core respawn/extraction fixes (VENU-14745, VENU-14934, VENU-14937), and Quinn dialogue after obtaining the Striker (VENU-10204).

The report panel not closing after Submit is also listed as fixed (VENU-14886); that panel fix does not mean the gameplay issue you reported is resolved.

Inventory is retained after death/respawn (VENU-14887). The Hauler magnet has a larger area (VENU-14910), PACE drones respawn less frequently (VENU-14811), and the Cruiser HUD warns about insufficient fuel for requested thrust (VENU-14906). That warning is not a confirmed cure for [0 MN](/guides/cloud-cruiser-first-base/#zero-thrust-unconfirmed).

<h2 id="ea-1-0-9">EA 1.0-9: core recovery and Camp Hub placement</h2>

**[Official hotfix, updated English notes](https://store.steampowered.com/news/app/1798230/view/712290761518877157?l=english).** The updated notes cover core respawn locations after save/reload (VENU-15017), rare extraction corner traps (VENU-14937), and placing a Hub atop a stored Hub (VENU-15090).

For an **already stuck core**, some players may need to save and reload to trigger respawning. This is the developer's scoped instruction, not a universal recovery method. See [core delivery and recovery](/guides/reactor-core-delivery/).

**Updated English notes, checked November 5:** [EA 1.0-9 VENU-15168](https://steamcommunity.com/app/1798230/allnews/?l=english) also lists intermittent Scope tuning failure for the PACE Security Base. [Compare frequency and progression symptoms](/guides/opening-problems/#pace-security-tuning-ea109); no universal frequency or save-recovery guarantee.

<h2 id="experimental-1-0-10">EA 1.0-10 preview: experimental branch</h2>

**[Official preview](https://store.steampowered.com/news/app/1798230/view/712290761518877314); not confirmed as the default release.** It announces FOV and rebinding improvements, storage stack/split/sort, co-op client crafting from shared inventories, core waypoint/recovery, repair hitboxes and Jet Ring lever persistence. Do not apply this list to the default branch merely because its version number is higher.

The developer asks players loading default saves in Experimental to save subsequent progress into a **new slot** to reduce corruption risk. Features may regress and stability varies. Check the branch and displayed version before following a fix.

## Match the symptom first

Use the [version/symptom helper](/tools/troubleshooting/) for specific records. Core loss, a Wasp pad collision, unopened storage and zero thrust are separate cases. Historical entries stay available; no result for your version means no verified match in this guide, not proof the problem is absent.
