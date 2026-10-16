---
title: "ATMOSFAR Fuel & Power Guide: Hydrogen, Camp & Repairs"
description: "Refuel your Wasp, charge backpack tools and check Camp Hub electricity. Learn the difference between hydrogen fuel and power."
category: "Survival Systems"
badge: "DEVELOPER SOURCE GUIDE"
readingTime: "5 min read"
publishDate: "2026-10-16"
updatedDate: "2026-10-16"
icon: "ri-flashlight-line"
lang: "en"
---

## Fuel and electricity do different jobs

**Liquid hydrogen powers flight; electricity powers tools and equipment.** A full fuel reserve does not mean your backpack or camp has electricity. Start by checking the meter on the device that stopped working.

This is a practical system overview based on developer blogs, not a list of final-build recipes. Button prompts and ingredient counts should come from your installed build.

## How to prepare Wasp fuel

1. Check your Wasp’s fuel level before choosing a destination.
2. Locate hydrogen crystals; the developer describes deposits near hydrogen geysers.
3. Bring crystals to a hydrogen refinery and check its required electrical supply.
4. Confirm that the refinery produced liquid hydrogen, then follow the current interaction prompt to refuel.
5. Plan both the outbound flight and the return trip. Check damage as well: a damaged craft can perform poorly and use more fuel.

**Repair is a separate task.** Use a Welder and the materials requested in game. Washing dirt off a Wasp is cosmetic in the developer description, not a substitute for repairing damage. [Fuel and maintenance source](https://www.atmosfar.game/feed/dev-blog-5-wasps-101).

## Backpack or hand tool out of power?

The backpack carries a battery used by your tools. Developer examples include charging in sunlight, near bioluminescent plants and via the Utility Wasp’s charge cable. Check the current build for the available connection or charging prompt.

A useful preparation routine is to charge tools before salvage work, bring repair materials and leave enough reserve for the return. This routine is editorial advice, not a fixed battery-capacity requirement.

## Camp equipment will not run

The **Camp Hub** connects a Utility Wasp to electrical camp equipment. Check:

- Is the hub deployed and connected to a suitable supply?
- Does the supply have charge or generation available?
- Is the machine you need connected and powered?
- Does the total active demand fit within the available supply?

The developer also describes solar panels as an additional camp power source. A crafting table makes equipment; a research desk studies artifacts to unlock craftables; a hydrogen refinery produces fuel. They have different jobs. [Backpack, camp and tools source](https://www.atmosfar.game/feed/dev-blog-6-life-of-a-vagabond).

## Cloud Cruiser: check power before fuel production

The developer describes a nuclear reactor supplying most ship systems, while forward thrust uses liquid hydrogen. Refineries process crystals; exterior hydrogen siphons collect hydrogen from the air. Both depend on electricity.

Fuel storage also needs cooling power in this design. A reactor outage can therefore affect fuel storage as well as machinery. The developer measures generation and demand in **Power Units (PU)**; use the values shown in your build instead of assuming a fixed kW recipe. [Cloud Cruiser power source](https://www.atmosfar.game/feed/dev-blog-9-cloud-cruiser-pt-1).

## Quick troubleshooting order

| Symptom | Check first | Next step |
| --- | --- | --- |
| Wasp cannot continue flying | Fuel and damage | Refill or repair as indicated in game |
| Hand tool stops | Backpack battery | Use an available charging method |
| Camp machine will not work | Hub connection and supply | Inspect active demand and the machine’s required inputs |
| Refinery produces no fuel | Electrical supply and crystals | Check the current recipe and output storage |
| Cruiser systems fail together | Reactor and total demand | Restore supply before restarting nonessential equipment |

The order above is an editorial diagnostic aid. It is not a claim that every failure has the same cause.

[Open your expedition checklist](/guides/starter-survival-checklist/) · [Plan co-op hosting](/coop/)

## Version and sources

Checked October 16, 2026 against the three linked official development blogs. Those pages describe development builds; they do not establish final ingredient counts, production rates or exact controls.
