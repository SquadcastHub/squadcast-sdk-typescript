# SnoozeNotificationsUnsnoozeIncidentNotificationsResponse

The request has succeeded.

## Example Usage

```typescript
import { SnoozeNotificationsUnsnoozeIncidentNotificationsResponse } from "SquadcastSDK/models/operations";

let value: SnoozeNotificationsUnsnoozeIncidentNotificationsResponse = {
  data: {
    incidentId: "<id>",
    isSnoozed: true,
    reassignTo: {
      id: "<id>",
      type: "<value>",
    },
  },
};
```

## Fields

| Field                                                                                                                                   | Type                                                                                                                                    | Required                                                                                                                                | Description                                                                                                                             |
| --------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| `data`                                                                                                                                  | [models.V3IncidentsSnoozeNotificationsUnsnoozeIncidentResponse](../../models/v3incidentssnoozenotificationsunsnoozeincidentresponse.md) | :heavy_check_mark:                                                                                                                      | N/A                                                                                                                                     |