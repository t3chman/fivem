---
ns: CFX
apiset: client
---
## SET_CLIENT_CULLING_RADIUS

```c
void SET_CLIENT_CULLING_RADIUS(float radius);
```

Sets the culling radius for the client. Entities that would be created beyond this range will be suppressed. Particularly helpful for modifying the world grid owners culling range alongside SET_PLAYER_CULLING_RADIUS
Set to `0.0` to reset.

## Parameters
* **radius**: The radius.
