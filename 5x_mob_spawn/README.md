# 5x Mob Spawn Rate Addon

A Minecraft Bedrock Edition addon that increases hostile mob spawns by approximately 5x the normal rate.

## Features

- **5x Increased Spawn Rates**: Hostile mobs spawn much more frequently
- **Compatible Mobs**: Affects Zombies, Skeletons, Creepers, Spiders, and Endermen
- **Adjustable**: Max mobs increased to 40 (from default ~8)
- **Difficulty Independent**: Works on all difficulty levels

## Installation

1. Download the addon folder (`5x_mob_spawn`)
2. Place it in: `com.mojang/behavior_packs/` on your device
3. Open Minecraft Bedrock
4. Create a new world or edit an existing one
5. Go to Behavior Packs and enable "5x Mob Spawn Rate"
6. Start the world

## How It Works

This addon modifies the spawn weight and maximum mob limits for hostile mobs. The increased `max_mobs` value of 40 (compared to the default ~8) allows significantly more mobs to spawn in loaded chunks simultaneously.

## Adjustments

To fine-tune the spawn rate, edit `entities/spawn_rules.json`:
- Increase/decrease the `weight` values to prioritize certain mobs
- Modify `max_mobs` values for more/fewer total mobs
- Adjust `brightness` conditions to restrict spawns to darker areas

## Compatibility

- Minimum version: Minecraft Bedrock 1.20.0+
- Works on all platforms (Windows, console, mobile)

## Notes

- This addon may impact game performance on lower-end devices
- Spawning is still controlled by normal Minecraft lighting and biome rules
- Mobs will still require proper spawn conditions (darkness, solid blocks, etc.)

## Affected Mobs

- Zombie (weight: 100)
- Skeleton (weight: 80)
- Creeper (weight: 50)
- Spider (weight: 20)
- Enderman (weight: 10)
