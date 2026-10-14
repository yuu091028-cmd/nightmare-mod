# Nightmare Swarm (Forge 1.20.1)

A high-difficulty Minecraft Forge 1.20.1 mod source project.

## Boss summon egg

The mod adds **ナイトメア・ボス召喚エッグ** to the Spawn Eggs creative tab. Right-click to summon a random vanilla hostile mob upgraded as a boss. In Survival, the egg is consumed; in Creative, it is not. Bosses use vanilla mob models, not custom 3D models.

## Features

- Attempts to spawn 8–14 hostile mobs every 5 seconds near non-creative, non-spectator players.
- Rough nearby-hostile cap of 90.
- About one in four ordinary spawns can be an elite mob.
- Every third global wave attempts to include a boss; random boss spawns are also possible.
- Bosses have 800–1800 base HP, heavy attacks/armor, netherite armor, glowing, a custom name, and a soul-flame/crimson particle aura.
- **Boss health bar** appears for players within 64 blocks.
- **Boss attacks:** summons three elite reinforcements every 10 seconds and calls lightning on its target every 15 seconds. Below half health it enrages and gains more damage/speed.
- **Enemy evolution:** mod-spawned non-boss enemies that survive can evolve up to three stages, gaining health, damage, armor, speed, and a new name.
- **Scaling difficulty:** later waves increase boss attack damage and armor (with caps).
- **Bonus drops:** mod-spawned enemies give an extra random reward; normal enemies mostly drop common valuables, with a small rare-loot chance. Bosses can drop diamond blocks, netherite ingots, enchanted golden apples, totems, nether stars, elytra, tridents, beacons, dragon breath, or shulker boxes.

## Build

Requirements: Java JDK 17 and internet access for Gradle/Forge dependencies.

1. Open this folder in IntelliJ IDEA as a Gradle project.
2. Run the Gradle task `build`.
3. The output JAR should appear under `build/libs/`.
4. Put that JAR into `%appdata%\\.minecraft\\mods` and launch Minecraft Forge 1.20.1.

This is a **source project, not a prebuilt JAR**. It has not been compiled or tested in Minecraft in this environment. Back up worlds and test in a separate world first. The spawn rate and boss attacks are intentionally intense and may cause lag. Compatibility with Dragon Block Noea is unverified.
