# V3IncidentsResolveIncidentRequest

Request body for resolving an incident.

## Example Usage

```typescript
import { V3IncidentsResolveIncidentRequest } from "SquadcastSDK/models";

let value: V3IncidentsResolveIncidentRequest = {
  resolutionReason: {
    message: "<value>",
  },
};
```

## Fields

| Field                                                    | Type                                                     | Required                                                 | Description                                              |
| -------------------------------------------------------- | -------------------------------------------------------- | -------------------------------------------------------- | -------------------------------------------------------- |
| `resolutionReason`                                       | [models.ResolutionReason](../models/resolutionreason.md) | :heavy_check_mark:                                       | N/A                                                      |