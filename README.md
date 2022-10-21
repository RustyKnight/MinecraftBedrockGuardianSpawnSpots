# Minecraft Bedrock, Guardian Spawn Spots V0.0.1

![MinecraftBedrock](https://img.shields.io/badge/MinecraftBedrock-1.19.30-orange)

## Description

Guardians on Minecraft Bedrock use specific spawn locations in each chunk that the ocean monument occupies. These spots are independent of orientation of the spawn location and have been discussed at length in several videos/posts. For the purpose of this page it is important to understand how the structure is brought in. The structure is centered on a chunk and the center of the monument is always chunk aligned in the same way regardless of rotation. When the structure comes in to the world the center chunk is consistent along with the north west corner.

## Taken from

[Bedrock Technical Resource Pack](https://github.com/RavinMaddHatter/Bedrock-Technical-Resource-Pack)

This strips out the feature into a standalone addon and updates it to support 1.19.30

## How To Use

To use this feature, place an armor stand in the center chunk of the ocean monument, and apply a **prismarine shard** item to armor stand. It does the rest of the math to find the spawn spots. There is no need to find a specific block or look for a specific direction, this feature accounts for all of that for you. You simply place the armor stand at the center chunk (the highest tower) and it figures it all out for you.

Guardians will spawn if any green blocks are exposed. covering up all green blocks block all guardian spawns. You can use any of the green blocks with water in them as a spawn spot for designing your own farm.

* If the armor stand is not placed in the center chunk of the ocean monument, the displayed spawn spots will be incorrect.
