---
sidebar_position: 2
---

### `removekey` Command

The `removekey` command is accessible to administrators and is used to remove all keys associated with a specific vehicle from a player in a FiveM server. This command is primarily designed for in-game usage.

#### Usage:

```
/removekey <playerId>
```

#### Arguments:

- `<playerId>` (number): The ID of the player from whom all keys associated with the target vehicle should be removed. The target player must be inside the target vehicle for this command to work.

#### Examples:

1. Remove all keys associated with the vehicle that the player with ID 3 is currently in.
   ```
   /removekey 3
   ```

#### Notes:

- Only administrators with appropriate permissions can execute this command.
- The target player must be inside the target vehicle for this command to work.
- This command will remove all keys associated with the vehicle from the target player.

> **Warning:** Improper usage of this command may cause undesired behavior in the server or affect player experience. Use with caution.
