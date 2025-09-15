# SchedulesGetScheduleByIdResponse

The request has succeeded.

## Example Usage

```typescript
import { SchedulesGetScheduleByIdResponse } from "SquadcastSDK/models/operations";

let value: SchedulesGetScheduleByIdResponse = {
  data: {
    id: 472399,
    name: "<value>",
    description: "monthly a lively valley esteemed righteously loose",
    orgID: "<id>",
    teamID: "<id>",
    timeZone: "Pacific/Auckland",
    paused: true,
    ownerID: "<id>",
    ownerType: "user",
    tags: [
      {
        key: "<key>",
        value: "<value>",
        color: "green",
      },
    ],
    createdAt: "1713572370410",
    updatedAt: "1735643517688",
  },
};
```

## Fields

| Field                                                           | Type                                                            | Required                                                        | Description                                                     |
| --------------------------------------------------------------- | --------------------------------------------------------------- | --------------------------------------------------------------- | --------------------------------------------------------------- |
| `data`                                                          | [models.V4ScheduleResponse](../../models/v4scheduleresponse.md) | :heavy_check_mark:                                              | N/A                                                             |