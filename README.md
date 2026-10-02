# Nuael Engine

**A 2D game engine on the Deno + JavaScript stack — build your game into a single native exe with one button. No toolchains, no Python, no installers.**

> **Status: pre-alpha (v0.1.0-pre-alpha).** Things work, things may change. Feedback welcome.

## Why Nuael

- **One-button builds** — from project to a single cross-platform exe. Download → open → press Build → ship.
- **Prototypes (stamps)** — design an entity once, stamp it across scenes, propagate changes or reset overrides. Spawn prototypes at runtime from scripts.
- **Built-in ML (zml)** — train tiny NPC brains (10–100k params) **locally, inside the engine, no Python**. NPC behavior is learned data: retrain with a different reward, get a different character.

## The demos (see Releases)

| Demo | Shows |
|---|---|
| **Space Shooter** | Full game frame: splash → lobby → levels → win/lose. Atlases, animation, sound, project settings, one-button build. |
| **ZML NPC Arena** | Two NPCs, one technology: «trained to fight» vs «trained to never fight». The difference is a training command, not code. |

## Quick start

1. Grab `NuaelEditor` from **Releases**.
2. Open a demo project, press **Play**.
3. Press **Build** → get a single exe of the game.

## Stack

Deno 2 · WebUI · PixiJS v8 · custom ECS · Process Pair architecture · zml (local RL micro-models)

## Roadmap

Pre-alpha → stabilization → **2D+3D** (Orillusion 3D layer) → GUI framework spin-off.

## License & pricing

The editor and demos are distributed as **freeware binaries** (see LICENSE). Source code is not public at this stage.

**All pre-alpha and alpha versions are free.** Terms may be revised from the beta stage onward — but anything you've already downloaded stays free under the terms it shipped with. Your games are always yours.

---
*Made by Tvortsa. Pre-alpha — we're just getting started.*
