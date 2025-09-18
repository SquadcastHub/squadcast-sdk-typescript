# SquadsGetSquadByIdResponse

The request has succeeded.

## Example Usage

```typescript
import { SquadsGetSquadByIdResponse } from "@solarwinds/squadcast-sdk-typescript/models/operations";

let value: SquadsGetSquadByIdResponse = {
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