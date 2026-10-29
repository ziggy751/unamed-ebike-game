---
name: mtb-emoto-bike-models
description: Research, create, improve and integrate realistic 3D bikes, e-motos, vehicles and upgrade components in this game's website. Use whenever adding or changing a bike, vehicle, 3D vehicle part, model from photo, garage upgrade or related vehicle asset.
---

# Vehicle 3D Modelling Skill — MTB & E-Moto Game

## Mandatory scope
Apply this workflow to **every bike and vehicle-related 3D model**, existing or new, including mountain bikes, downhill/enduro/dirt-jump bikes, Surron, Talaria, E Ride Pro, Stark Varg, other e-motos, vehicles and individual aftermarket parts. Work in the actual existing website repository. Do not assume the project has Voltline-specific files, builders, or tools. Inspect the current engine, models, data, physics, garage, persistence and asset pipeline first. Preserve working features, maps, controls, camera and game saves.

## Research before modelling
Identify each vehicle's exact manufacturer, model, year and variant, and whether it is stock or customised. Search official manufacturer photography, geometry charts, manuals and specifications; supplement with multi-angle reference images and videos. Collect side-on (both sides), front, rear, top and 3/4 views, plus close-ups of frame, suspension, linkage, battery/motor, drivetrain, wheels, brakes, handlebars and components. Record URLs and which dimensions are verified versus estimated. Never claim an approximate shape is exact.

For custom builds, use real-life custom-bike photos (including TikTok-style builds) for design reference, but maintain accurate geometry. Plain-colour Surron requests must use clean solid-colour panels, not automatically copy racing graphics. Respect licensing; do not redistribute copyrighted photographs, proprietary models or brand artwork without permission.

## Build accurate geometry, not generic recolours
Use measured wheel diameter and wheelbase to calibrate reference images into real-world units; rectify perspective when needed. Trace frame and structural shapes carefully. Create actual 3D thickness and proper front/rear geometry; validate both side silhouettes and 3/4 views. Avoid slab-sided frames, floating parts, intersecting meshes, fake suspension, generic silhouettes and mismatched wheels.

Model separate, appropriately detailed frame tubes/beams, swingarms, battery and motor housings, suspension linkages, forks, rear shocks, wheels, spokes, tyres, brakes, rotors, handlebars, controls, cables, fasteners, chain/sprockets and seat. MTBs have pedals and bicycle drivetrains; footpeg-equipped e-motos have throttle and footpegs, **not bicycle pedals or pedalling animations**. Hardtails have no rear shock. Use PBR materials and efficient geometry/LODs for browser performance. Use licensed assets or original geometry; no unlicensed photo-skin shortcuts.

## Real branded upgrades
Research actual components and compatible products from Title MTB, Chromag, Fox, RockShox, Öhlins, SRAM, Shimano, TRP, Magura, Hope, Renthal, Deity, Race Face, Burgtec, OneUp, Maxxis, Schwalbe, Industry Nine, DT Swiss, Warp 9, EXT and other verified brands. Create distinct geometry and accurate dimensions for actual product variants, not menu-only names or recolours. When installed, replace the correct visible 3D part. Enforce realistic compatibility. Connect upgrades to relevant ride physics (mass, steering, damping, traction, braking, gearing, etc.) and persist selected product IDs and settings across refreshes.

## Integrate in the real game
Find and follow existing vehicle registry, scene graph, asset loader, suspension animation, physics, garage, bike selection and saved-build conventions. Ensure steering pivots, wheel rotation, fork travel, shock/linkage travel and rider contacts remain aligned. Add working garage preview, selection, actual in-game assets and saved configurations. Never create unused files or placeholder models while claiming completion.

## Verify and iterate
Render front, side, rear and both 3/4 views; compare proportions against the chosen references and refine. Check for gaps, clipping, wrong axle spacing, mismatched seat and suspension positions. Test in game on turns, rough terrain, jumps, braking and landings. Test garage part swaps, different bikes and browser refresh. Run project build and available tests; report exact successes, failures and limitations. Prioritise a smaller number of accurate, fully integrated models over hundreds of unfinished placeholders.

## Updates
Keep assets and component data cleanly organised by brand/model/category. Follow the project's version/changelog convention (v1.0, v1.1, v1.2, etc.) for releases, not every edit. Summarise what was researched, built, integrated and tested, and explicitly list unfinished work. Preserve existing user saves.
