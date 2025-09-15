# SLOCreateSLOResponse

The request has succeeded and a new resource has been created as a result.

## Example Usage

```typescript
import { SLOCreateSLOResponse } from "SquadcastSDK/models/operations";

let value: SLOCreateSLOResponse = {
  data: {
    slo: {
      id: 248379,
      name: "<value>",
      timeIntervalType: "rolling",
      serviceIds: [],
      slis: [],
      targetSlo: 3965.13,
      startTime: new Date("2024-08-13T10:00:09.724Z"),
      endTime: new Date("2023-03-03T19:29:41.624Z"),
      allocatedErrorBudget: 1979.85,
      isActive: true,
      ownerType: "<value>",
      ownerId: "<id>",
      orgId: "<id>",
    },
  },
};
```

## Fields

| Field                                                                      | Type                                                                       | Required                                                                   | Description                                                                |
| -------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| `data`                                                                     | [operations.SLOCreateSLOData](../../models/operations/slocreateslodata.md) | :heavy_check_mark:                                                         | N/A                                                                        |