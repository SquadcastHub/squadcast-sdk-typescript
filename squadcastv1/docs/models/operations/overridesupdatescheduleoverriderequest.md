# OverridesUpdateScheduleOverrideRequest

## Example Usage

```typescript
import { OverridesUpdateScheduleOverrideRequest } from "SquadcastSDK/models/operations";

let value: OverridesUpdateScheduleOverrideRequest = {
  scheduleID: "<id>",
  overrideID: "<id>",
  v4UpdateScheduleOverrideRequest: {
    startTime: "<value>",
    endTime: "<value>",
    reason: "<value>",
    overriddenParticipant: {
      group: [
        {
          id: "<id>",
          type: "<value>",
        },
      ],
    },
    overrideWith: {
      group: [
        {
          id: "<id>",
          type: "<value>",
        },
      ],
    },
  },
};
```

## Fields

| Field                                                                                     | Type                                                                                      | Required                                                                                  | Description                                                                               |
| ----------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| `scheduleID`                                                                              | *string*                                                                                  | :heavy_check_mark:                                                                        | N/A                                                                                       |
| `overrideID`                                                                              | *string*                                                                                  | :heavy_check_mark:                                                                        | N/A                                                                                       |
| `v4UpdateScheduleOverrideRequest`                                                         | [models.V4UpdateScheduleOverrideRequest](../../models/v4updatescheduleoverriderequest.md) | :heavy_check_mark:                                                                        | N/A                                                                                       |