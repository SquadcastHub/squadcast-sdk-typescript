# SchedulesListSchedulesResponse

The request has succeeded.

## Example Usage

```typescript
import { SchedulesListSchedulesResponse } from "@solarwinds/squadcast-sdk-typescript/models/operations";

let value: SchedulesListSchedulesResponse = {
  data: [],
  pageInfo: {
    pageSize: 94168,
    hasNext: true,
    hasPrevious: true,
  },
};
```

## Fields

| Field                                                             | Type                                                              | Required                                                          | Description                                                       |
| ----------------------------------------------------------------- | ----------------------------------------------------------------- | ----------------------------------------------------------------- | ----------------------------------------------------------------- |
| `data`                                                            | [models.V4ScheduleResponse](../../models/v4scheduleresponse.md)[] | :heavy_check_mark:                                                | N/A                                                               |
| `pageInfo`                                                        | [models.CommonV4PageInfo](../../models/commonv4pageinfo.md)       | :heavy_check_mark:                                                | N/A                                                               |