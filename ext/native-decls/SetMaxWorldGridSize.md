---
ns: CFX
apiset: server
---
## SET_PLAYER_MAX_WORLD_GRID_SIZE

```c
object SET_PLAYER_MAX_WORLD_GRID_SIZE(int playerSrc, float maxWorldGridSize);
```

Sets the height/width of the max world grid square for a OneSync player. Defaults to 598.0 if set to 0.0

The max world grid size and culling radius are intrinscally connected. The default culling radius is 424.0, slightly larger than the distance from the center of the default max world grid square to the corner. 

## Parameters
* **playerSrc**: The player to set the max world grid size
* **maxWorldGridSize**: The height/width of the max world grid square