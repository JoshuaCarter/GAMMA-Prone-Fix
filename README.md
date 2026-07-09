# Dorn's Prone Fix v0.1.17

Makes low-crouch ("prone") in **S.T.A.L.K.E.R. G.A.M.M.A.** useful within modding limits — hacky workaround, not real prone. Watch the demo.

## Demo

https://github.com/user-attachments/assets/d76e38ac-12f6-43be-a209-573fa6dc55bb

## The problem

Vanilla prone is fake: low crouch with a dropped view but high body. You think you're behind cover; enemies shoot your face. You stick out of tight gaps while feeling hidden in first person.

## What this mod does

- Lowers posture closer to real prone
- Fixes headlamp to follow your view, not your floating head
- Hides legs and arms on the prone body to reduce wall clipping and ugly shadows

## What to expect

- **First person** — feels more like prone; **third person** — looks ridiculous
- Prone in/out is janky (shadows only; less janky than vanilla shadows)
- Best effort — my first mod
- 20% more damage when prone by default (adjust 100–200% in MCM)

## Installation

1. Download the latest release from https://github.com/JoshuaCarter/GAMMA-Prone-Fix/releases
2. Install via MO2 like normal

## Warnings!

- Overrides `stalker_smart_cover_animation.omf` — won't play nice with other mods that do the same
- Pose uses camera height — broken in 3rd person

## Other mods

- https://github.com/JoshuaCarter/GAMMA-Dont-ReEquip-PDA
- https://github.com/JoshuaCarter/GAMMA-Faster-Skinning
- https://github.com/JoshuaCarter/GAMMA-Field-Strip-All-Keybind
- https://github.com/JoshuaCarter/GAMMA-FPS-Counter
- https://github.com/JoshuaCarter/GAMMA-Giant-Jump
- https://github.com/JoshuaCarter/GAMMA-Optimal-Tool-Use
- https://github.com/JoshuaCarter/GAMMA-Radiation-Grain-Fix
- https://github.com/JoshuaCarter/GAMMA-Tooltip-Weapon-Damage
