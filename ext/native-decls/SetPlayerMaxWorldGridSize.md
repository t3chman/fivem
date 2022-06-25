---
ns: CFX
apiset: server
---
## SET_PLAYER_MAX_WORLD_GRID_SIZE

```c
void SET_PLAYER_MAX_WORLD_GRID_SIZE(int playerSrc, float maxWorldGridSize);
```

Sets the length of the sides of the max world grid square for a OneSync player. Defaults to `598.0` if set to `0.0`

The max world grid size and culling radius are intrinsically connected. The default culling radius is `424.0`, slightly larger than the distance from the center of the default max world grid square to the corner. 

## Parameters
* **playerSrc**: The player to set the max world grid size
* **maxWorldGridSize**: The length of the sides of the max world grid square. Defaults to `598.0` if set to `0.0`