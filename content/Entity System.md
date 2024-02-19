---
title: Entity System
publish: "false"
---
## What is an entity?
A game entity is some object that exists in the game world, usually the object is visible to the player, and usually it can move around. Examples:
- Missile
- Car
- Tank
- Grenade
- Gun

## What is the idea behind ECS

We avoid the hierarchical entities, they are formed by a combination of subcomponents that are responsible for a single thing, like rendering, movement, collision, and so on.
