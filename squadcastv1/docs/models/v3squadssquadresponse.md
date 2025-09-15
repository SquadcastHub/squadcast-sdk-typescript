# V3SquadsSquadResponse

## Example Usage

```typescript
import { V3SquadsSquadResponse } from "SquadcastSDK/models";

let value: V3SquadsSquadResponse = {
  id: "<id>",
  name: "<value>",
  slug: "<value>",
  members: [],
  organizationId: "<id>",
  owner: {
    id: "<id>",
    type: "<value>",
  },
  organization: {
    id: "<id>",
    name: "<value>",
    slug: "<value>",
  },
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `id`                                                                                       | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `name`                                                                                     | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `slug`                                                                                     | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `members`                                                                                  | *string*[]                                                                                 | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `organizationId`                                                                           | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `owner`                                                                                    | [models.Owner](../models/owner.md)                                                         | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `organization`                                                                             | [models.V3SquadsSquadResponseOrganization](../models/v3squadssquadresponseorganization.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |