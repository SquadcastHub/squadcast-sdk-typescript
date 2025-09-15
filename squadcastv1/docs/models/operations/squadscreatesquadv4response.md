# SquadsCreateSquadV4Response

The request has succeeded and a new resource has been created as a result.

## Example Usage

```typescript
import { SquadsCreateSquadV4Response } from "SquadcastSDK/models/operations";

let value: SquadsCreateSquadV4Response = {
  data: {
    organizationId: "<id>",
    ownerId: "<id>",
    id: "<id>",
    name: "<value>",
    slug: "<value>",
    members: [
      {
        userId: "<id>",
      },
    ],
    createdAt: "1708362786336",
    createdBy: "<value>",
  },
};
```

## Fields

| Field                                                                             | Type                                                                              | Required                                                                          | Description                                                                       |
| --------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| `data`                                                                            | [models.V4SquadsCreateSquadResponse](../../models/v4squadscreatesquadresponse.md) | :heavy_check_mark:                                                                | N/A                                                                               |