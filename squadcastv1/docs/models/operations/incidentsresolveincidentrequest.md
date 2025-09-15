# IncidentsResolveIncidentRequest

## Example Usage

```typescript
import { IncidentsResolveIncidentRequest } from "SquadcastSDK/models/operations";

let value: IncidentsResolveIncidentRequest = {
  incidentID: "<id>",
  v3IncidentsResolveIncidentRequest: {
    resolutionReason: {
      message: "<value>",
    },
  },
};
```

## Fields

| Field                                                                                         | Type                                                                                          | Required                                                                                      | Description                                                                                   |
| --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| `incidentID`                                                                                  | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `v3IncidentsResolveIncidentRequest`                                                           | [models.V3IncidentsResolveIncidentRequest](../../models/v3incidentsresolveincidentrequest.md) | :heavy_check_mark:                                                                            | N/A                                                                                           |