# SquadsCreateSquadResponse

The request has succeeded and a new resource has been created as a result.

## Example Usage

```typescript
import { SquadsCreateSquadResponse } from "SquadcastSDK/models/operations";

let value: SquadsCreateSquadResponse = {
  data: {
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
  },
};
```

## Fields

| Field                                                                 | Type                                                                  | Required                                                              | Description                                                           |
| --------------------------------------------------------------------- | --------------------------------------------------------------------- | --------------------------------------------------------------------- | --------------------------------------------------------------------- |
| `data`                                                                | [models.V3SquadsSquadResponse](../../models/v3squadssquadresponse.md) | :heavy_check_mark:                                                    | N/A                                                                   |