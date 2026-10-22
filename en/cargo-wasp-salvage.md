---
title: "ATMOSFAR Cargo Wasp Guide: Hoisting & Large Scrap Recovery"
description: "Plan Cargo Wasp lifting jobs, distinguish handheld extraction from large scrap processing, and prepare a destination before pickup."
sourceNote: "Based on official development diaries, checked on 2026-10-16. These describe alpha or EA beta builds; release-build controls and numerical values have not been tested."
category: "Vehicles & Salvage"
badge: "DEVELOPER SOURCE GUIDE"
readingTime: "3 min read"
publishDate: "2026-10-16"
updatedDate: "2026-10-16"
icon: "ri-flight-takeoff-line"
lang: "en"
---

## When the handheld Extractor is not enough

The Cloud Cruiser diary describes scrap too large for the handheld Extractor. Its recovery loop is to transport the piece with a Cargo Wasp to a material processor that you build on the Cruiser. Deliver it to the processor’s external entrance for processing. [Processor source](https://www.atmosfar.game/feed/dev-blog-10-cloud-cruiser-101).

This depends on access to a Cargo Wasp and a suitable Cruiser. The developer confirms the Cloud Cruiser was absent from the Steam Next Fest Demo. Do not treat this as a Demo unlock route. [Demo scope](https://www.atmosfar.game/feed/dev-blog-15-cloud-cruising-to-early-access).

## Understand the hoist

The Wasp diary describes a powered magnetic hoist with an extendable and retractable cable. It can engage and release objects. Cargo Wasps are slow and costly to fuel and maintain; precise handling matters more than speed. [Wasp source](https://www.atmosfar.game/feed/dev-blog-5-wasps-101).

The earlier Cargo diary also describes towing scrap too large to dismantle on site. It supports the lifting role, but its early cargo-lift layout is not a current construction blueprint. [Early design context](https://www.atmosfar.game/feed/dev-blog-2-up-in-the-atmosfar).

## Plan the job in this order

This checklist is editorial workflow advice, not a tested control sequence:

1. Confirm what the current build allows you to lift and where you will deliver it.
2. Prepare the destination and its required equipment before pickup.
3. Check vehicle damage, fuel, hoist power and the return route.
4. Use the displayed hoist controls; establish a stable approach before engaging the load.
5. Move slowly, align with the receiving area and release only when you have a clear view.
6. Inspect the processor output and available storage before planning another load.

| Problem | Check before retrying |
| --- | --- |
| Hoist does not engage | Current interaction prompt, power and target eligibility |
| Delivery is blocked | Receiving equipment and approach space |
| Processing does not start | Module requirements and inputs shown in your build |

These checks are editorial suggestions; they do not establish the cause of every failure. No payload limit, cable length, fuel rate or keybind is inferred here.

[Fuel & repairs](/guides/fuel-and-power/) · [Weather planning](/guides/weather-and-navigation/) · [Crafting & research](/guides/crafting-and-blueprints/)

## Source versions

The 2023 Cargo overview is an early design; Wasp 101 (2025-03-03) and Cloud Cruiser 101 (2025-07-28) describe alpha builds. The Demo clarification is from 2026-04-09 (EA beta). Checked 2026-10-16; final-build operation remains untested.
