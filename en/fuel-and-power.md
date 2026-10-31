---
title: "ATMOSFAR Fuel & Power Guide: Hydrogen, Camp & Repairs"
description: "Refuel your Wasp, charge backpack tools and check Camp Hub electricity. Learn the difference between hydrogen fuel and power."
category: "Survival Systems"
badge: "DEVELOPER SOURCE GUIDE"
readingTime: "5 min read"
publishDate: "2026-10-16"
updatedDate: "2026-10-31"
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

The backpack carries the battery used by your tools. In an [accepted developer answer by devl0f [Apog]](https://steamcommunity.com/app/1798230/discussions/0/573805072991183493/#c573805072991197446), checked October 31, 2026, the developer confirms daytime recharge and a power boost while piloting or sitting in the Wasp. Check the battery readout before and after a safe daytime pause.

This does not promise overnight charging or a fixed charge rate; a later player reported no charge from sitting overnight. Older alpha descriptions of other charging methods do not by themselves verify that a cable or glowing plant is a universal current-build solution.

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

## EA 1.0-5 resource and chest checks

The [official EA 1.0-5 notes](https://steamcommunity.com/app/1798230/allnews/), checked October 31, lower Wasp fuel use and stunner power use without numerical rates. Do not reuse an older build's observed drain as a fixed current value.

If chests do not appear with the camp, distinguish extreme-terrain placement failure, manual-attachment despawn and a forgotten camp location. See the [camp chest symptom table](/guides/opening-problems/#camp-chests-disappeared-distinguish-the-cause) for developer and community sources and the Camp Hub check. The developer's terrain explanation and a player's Hub recovery observation are separate evidence, not a guarantee that items will return.

## Version and sources

Checked October 16, 2026 against the three linked official development blogs. Those pages describe development builds; they do not establish final ingredient counts, production rates or exact controls.

## Early Access opening help

For the community accepted Utility Wasp power connection checks, official EA 1.0-4 tutorial respawn and research-drive notes, and unresolved camp/cave questions, see [opening problems and camp power](/guides/opening-problems/). Low FPS, DLAA changes and loading reports are covered in [performance troubleshooting](/guides/performance-troubleshooting/). This update was checked October 30, 2026; it does not turn the older development-source overview into a playtested release walkthrough.

## Camp power: launch-day community answer

The [accepted community answer](/guides/opening-problems/#portable-camp-has-no-power) distinguishes the Utility Wasp’s rear-left fuel inlet from its rear-right electrical connection. It says to run the engine and connect the Camp Hub to the Wasp for power. This is player guidance, not a measured power-output claim; check the current interface labels and the linked original thread.
