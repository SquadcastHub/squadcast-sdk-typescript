# CommonV3EntityOwner

Represents the owner of an entity.

## Example Usage

```typescript
import { CommonV3EntityOwner } from "SquadcastSDK/models";

let value: CommonV3EntityOwner = {
  id: "<id>",
  type: "<value>",
};
```

## Fields

| Field                                     | Type                                      | Required                                  | Description                               |
| ----------------------------------------- | ----------------------------------------- | ----------------------------------------- | ----------------------------------------- |
| `id`                                      | *string*                                  | :heavy_check_mark:                        | The ID of the owner.                      |
| `type`                                    | *string*                                  | :heavy_check_mark:                        | The type of the owner ( "user", "squad"). |