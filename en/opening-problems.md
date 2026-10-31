---
title: "ATMOSFAR Opening Problems: Camp Power & Tutorial Help"
description: "Check ATMOSFAR EA 1.0-5 camp and reactor fixes, missing chests and PACE Scope frequency hints, with official and community sources kept distinct."
category: "Starter Troubleshooting"
badge: "EARLY ACCESS · SOURCE CHECK"
readingTime: "4 min read"
publishDate: "2026-10-30"
updatedDate: "2026-10-31"
sourceNote: "EA 1.0-5 and new community replies checked October 31, 2026. Earlier EA 1.0-4 checks retain their October 30 scope. Official and community evidence are identified separately; this is not a release-build playtest."
icon: "ri-map-pin-line"
lang: "en"
---

## EA 1.0-5: reactor and camp storage fixes

The [official EA 1.0-5 announcement](https://steamcommunity.com/app/1798230/allnews/), published October 30 and checked October 31, lists reactor-core loss after detaching a Hauler magnet, a core despawning in the cargo lift, and camp Hub/storage despawning during manual attachment to a Wasp inside the Cloud Cruiser. It also lists specific Pearl Island and Mawknest terrain traps. These are described cases, not a claim that every missing object or blocked objective is fixed.

Record the exact action and version if a problem continues after updating. The notes do not promise to restore previously lost cores or stored items. A [reactor-loading discussion](https://steamcommunity.com/app/1798230/discussions/0/573805072991231149/) contains a proposed route and reports of failed attempts, so it does not establish a guaranteed installation or recovery method.

## Camp chests disappeared: distinguish the cause

| What happened? | Evidence and first check | What remains uncertain |
| --- | --- | --- |
| Chests/buildables failed to appear after redeploying on extreme terrain | Developer [devl0f [Apog] explains placement failure and a missing warning](https://steamcommunity.com/app/1798230/discussions/0/573805072991192623/#c573805072991198158). Compare the ground with a flatter deployment area | This is not proof that every chest-disappearance case has the same cause |
| You need to locate a chest after that placement problem | A [community reply reports finding chests in the Camp Hub and placing them again](https://steamcommunity.com/app/1798230/discussions/0/573805072991192623/#c573805072991194700). Inspect the Hub before rebuilding | This is a player's recovery observation, not guaranteed restoration of all contents |
| Hub/storage vanished while manually attaching it to a Wasp inside the Cloud Cruiser | This specific despawn path appears in the official EA 1.0-5 fix list | Updating does not promise retroactive recovery; record attachment action and version if repeated |
| You flew away and forgot where the entire camp was left | This is the separate [forgotten-camp question below](#lost-mobile-camp-is-there-a-confirmed-retrieval-method) | Neither a terrain-placement explanation nor the attachment fix confirms a universal recall feature |

These checks distinguish placement, attachment and location problems. If a chest is still absent, report the terrain, Hub contents, action before disappearance and exact version. Do not delete the save to test a suggested recovery.

## PACE Scope: which target and frequency?

First read the target name in your active objective. The [PACE Scope frequency discussion](https://steamcommunity.com/app/1798230/discussions/0/573805072991115682/) mixes more than one target; using a number for the PACE Antenna is not the same as tuning for the Security Base.

<details>
<summary>Show the community frequency hint (spoiler)</summary>
<p><strong>71.2</strong> is reported for the <strong>Security Base / PACE Scope</strong> target, with multiple players confirming it in the thread checked October 31, 2026. The earlier <strong>52.8</strong> reply concerns the <strong>PACE Antenna</strong>, a different target.</p>
<p>This is a dated community answer, not developer confirmation or our own playtest. Check the active objective and available target names first. The thread does not establish that a frequency is universal across all saves and patches, or a precise log location.</p>
</details>

If tuning does not advance the objective, record its exact text, target name and installed version rather than assuming that repeating a number completes every prerequisite.

## Weather data and the military base

**Developer explanation, checked October 31, 2026:** [Fredrik distinguishes the military base from the weather-data location](https://steamcommunity.com/app/1798230/discussions/0/573805072991227463/#c573805072991229966). The military base contains the Striker. Weather data is in the **largest settlement on that same island**, inside a **larger building toward its upper area**. Read the active objective before assuming you are looking for the military base.

Detailed wiring and battery directions in other replies are separate community guidance; they are not the developer's confirmed complete route. This guide does not supply unverified coordinates, battery counts or a guaranteed access sequence. Use the [quest symptom filter](/tools/troubleshooting/?symptom=quest) to distinguish this from the PACE frequency question.

## Docked storage is not the attachment-despawn fix

A [developer reply checked October 31](https://steamcommunity.com/app/1798230/discussions/0/573805072991228002/#c573805072991228343) confirms that Camp Hub trunk access while docked to the Cloud Cruiser is intended, but an interaction bug is being tracked. A large Wasp pad was suggested only as a **possible** workaround. An experimental hotfix was a plan, not a confirmed release.

If a visible docked chest will not interact, do not classify it automatically as the EA 1.0-5 manual-attachment despawn fix. Record the pad, docking action, whether the trunk is visible and the installed version. See [docked Camp Hub interaction](/guides/cloud-cruiser-first-base/#docked-camp-hub-trunk-interaction) or the [storage symptom filter](/tools/troubleshooting/?symptom=storage).


## Portable camp has no power

Fuel and electricity are separate resources. A running hydrogen fuel process does not by itself prove that your camp has a working electrical connection. If camp equipment stops, start with the Camp Hub's displayed power supply rather than making more fuel blindly.

A [Steam answer by echo, accepted by the topic author](https://steamcommunity.com/app/1798230/discussions/0/573805072991127017/#c573805072991131697), describes the following checks:

1. Identify the **Utility Wasp**. Its rear-left connection is for fuel; its rear-right connection is for electricity.
2. Check the current interaction labels so you use the electrical connection, not the fuel inlet.
3. Run the Wasp's engine and connect the camp Hub to the Wasp for electrical supply.
4. Recheck the Hub output and the machine's connection and required inputs.

This is a **community accepted answer**, not an Apog Labs instruction or our own device test. No power output, fuel-use rate or permanent-power unlock sequence is established here. If your current build differs, record the version and visible connection labels. See [fuel and power](/guides/fuel-and-power/) for the developer-source system overview.

## Respawned inside the Pearl Island foundry?

The official **EA 1.0-4** notes list **VENU-14352**: updated main-discovery respawn locations on Pearl Island to prevent returning to the foundry facility. Check your installed version against the [official update notes](https://steamcommunity.com/app/1798230/allnews/). This fix concerns that respawn problem; it is not a promise to fix every door, objective or mission-order block.

If it still occurs after updating, use the in-game bug reporter with your version, exact objective and the steps before death and respawn. Do not reset the save merely to follow an old Demo walkthrough.

## Research drive missing after recovery

**VENU-14419** is listed in the EA 1.0-4 fixes for research drives being lost upon recovery. Record the version and recovery action if you still encounter it. The note does not say that an already missing drive will automatically be restored, so this guide cannot promise item recovery.

## Lost mobile camp: is there a confirmed retrieval method?

Not from the [launch-day thread checked here](https://steamcommunity.com/app/1798230/discussions/0/573805072991121075/). Another player suggested a compass marker, but the author replied that only the Cloud Cruiser marker was visible. That exchange does not verify a camp-retrieval feature.

For a report, include the last known island or landmark, whether the camp was deployed, the last relocation action and the current objective/version. These are reporting details, not a guaranteed recovery method. Do not delete or overwrite your save to test an unconfirmed workaround.

## Hauler Wasp trapped in a cave

The [community discussion](https://steamcommunity.com/app/1798230/discussions/0/573805072991115981/) contains player hints but no complete route verified by this guide. Finding the cave entrance and opening an exit are different tasks. We do not prescribe a door key, shortcut or exit sequence without confirming it.

Record the location, objective text, doors you can interact with and the last completed action before seeking help. For the craft's role and lifting context, use [Cargo/Hauler salvage preparation](/guides/cargo-wasp-salvage/).

## Before trying a walkthrough

Follow the current objective and input labels. Old Demo routes cannot establish the Early Access layout. Use the [first-flight preparation guide](/guides/prologue-walkthrough/) for safe checks and [performance troubleshooting](/guides/performance-troubleshooting/) for low FPS, DLAA and loading reports.

## Sources and scope

EA 1.0-5 notes, the PACE thread, camp-placement developer reply and reactor discussion were checked October 31, 2026. Earlier EA 1.0-4 and launch-day power/camp/cave checks were made October 30. The power and frequency instructions are attributed community guidance; unresolved questions are not advertised as solved.
