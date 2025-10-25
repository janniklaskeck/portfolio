---
layout: post
title:  "Off The Grid"
thumbnail: "/assets/img/off_the_grid/cover.webp"
date:   2025-10-22 16:59:24 +0200
categories: project professional
releasedate: 10/08/24
website: https://gameoffthegrid.com/
websitesteam: https://store.steampowered.com/app/3659280/Off_The_Grid/
websiteepic: https://store.epicgames.com/en-US/p/off-the-grid-7e3cc5
tools:  [Unreal Engine 5, Visual Studio, Perforce, Jira/Confluence]
permalink: "/:title/"
professional: true
---

Off The Grid is a extraction battle royal third person shooter.
Main feature are the cyberlimbs, arms and legs that can be changed during the game to gain powerful abilities.

Started as a Gameplay Programmer in May 2022, on the Cyberlimbs team.
Initially working on prototype limbs, creating barebones, playtest ready versions.
Examples: Sticky Goo, Micro Missiles, Mortar Legs

Later on was responsible for a prototype vehicle implementation, 5 seater(driver, 3 passengers, 1 top turret gunner).
Gameplay logic for handling driving, camera, turret, vfx/sfx.
Later on feature cancelled, plans for the map changed and jetpack was made more prominent.

Created Propagation system for gases/liquids, used for Toxic Smoke, Phosphporous Dart and Sticky Goo(+ its burning variant).
Samples the surrounding environment over time and looks for valid locations to continue spreading, with varying parameters.
Using a 3D grid of points, not voxelized but similar.
Toxic Smoke uses a simple setup, only checking from point to point, since it's gas.
StickyGoo also tries to determine if there is a "surface" at the target point, on which it can continue to spread.
The fire propagation checks for existing sticky goo areas.

Promoted to Senior Gameplay programmer, became responsible for most of the technical implementation of the cyberlimb abilities.
Including creating base code used by all cyberlimbs(asset loading, )
Worked on over 12 limbs, majorly involved in at least the initially released versions.

Senior Gameplay Programmmer for Cyberlimbs, worked on logic, animation scripting, VFX and more on over 12 limbs
