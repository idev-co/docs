---
sidebar_position: 1
---

### `addkey` Command

The `addkey` command is accessible to administrators and is used to add a key to a player in the server. This command is primarily designed for in-game usage and is used to grant a key to a player associated with a vehicle.

#### Usage:

```
/addkey <playerId> <count> <blockKey>
```

#### Arguments:

- `<playerId>` (number): The ID of the player to whom the key should be added. The target player must be inside the target vehicle.
- `<count>` (number): The number of keys to add. Use a positive value to grant keys.
- `<blockKey>` (number): Determines whether the key should be blocked or unblocked. Use `1` to block the key (prevents giving or dropping), or `0` to unblock it.

#### Examples:

1. Grant two keys to player with ID 3 for the vehicle they are currently in, and unblock the keys:
   ```
   /addkey 3 2 0
   ```

2. Grant one key to player with ID 5 for the vehicle they are currently in, and block the key:
   ```
   /addkey 5 1 1
   ```

#### Notes:

- Only administrators with appropriate permissions can execute this command.
- The target player must be inside the target vehicle for this command to work.
- The `blockKey` argument allows administrators to block the key in the player's inventory, preventing them from giving or dropping it. This feature can be useful to avoid glitches related to key duplications or temporary job assignments.

> **Warning:** Improper usage of this command may cause undesired behavior in the server or affect player experience. Use with caution.