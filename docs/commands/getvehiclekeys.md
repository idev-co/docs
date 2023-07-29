---
sidebar_position: 4
---

### `getvehiclekeys` Command

The `getvehiclekeys` command is accessible to administrators and is used to determine the number of keys associated with a specific vehicle's license plate in the inventories of all players on the server.

#### Usage:

```
/getvehiclekeys <licensePlate>
```

#### Arguments:

- `<licensePlate>` (string): The license plate of the vehicle for which you want to find the number of keys. (8 characters maximum ⚠️)

#### Examples:

1. Check the number of keys associated with the vehicle with the license plate "ABC123" in all players' inventories:
   ```
   /getvehiclekeys ABC123
   ```

#### Notes:

- Only administrators with appropriate permissions can execute this command.
- The command will find the number of keys associated with the specified vehicle's license plate in all players' inventories.

> **Warning:** Improper usage of this command may cause undesired behavior in the server or affect player experience. Use with caution.