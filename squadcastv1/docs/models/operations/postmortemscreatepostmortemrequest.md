# PostmortemsCreatePostmortemRequest

## Example Usage

```typescript
import { PostmortemsCreatePostmortemRequest } from "SquadcastSDK/models/operations";

let value: PostmortemsCreatePostmortemRequest = {
  incidentID: "<id>",
  v3IncidentsPostmortemsCreatePostmortemRequest: {
    ownerId: "<id>",
    title: "<value>",
    postmortem: "<value>",
    status: "published",
    followUps: [],
    attachments: [
      {},
    ],
  },
};
```

## Fields

| Field                                                                                                                 | Type                                                                                                                  | Required                                                                                                              | Description                                                                                                           |
| --------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| `incidentID`                                                                                                          | *string*                                                                                                              | :heavy_check_mark:                                                                                                    | N/A                                                                                                                   |
| `v3IncidentsPostmortemsCreatePostmortemRequest`                                                                       | [models.V3IncidentsPostmortemsCreatePostmortemRequest](../../models/v3incidentspostmortemscreatepostmortemrequest.md) | :heavy_check_mark:                                                                                                    | N/A                                                                                                                   |