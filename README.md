# solid hitbox entity
### This Minecraft Bedrock Edition Addon adds an entity that behaves like solid blocks, useful for creating movable and scalable hitboxes
<br>Limitations:
1. Uses `runtime_identifier: "minecraft:boat"`
2. Always faces North, not possible to rotate them.
3. If multiple large-sized hitboxes (>8) are riding an entity, they mess up the `custom_hit_test` of that rideable entity, all sorts of right-click and left-click interactions stop working in survival gamemode.