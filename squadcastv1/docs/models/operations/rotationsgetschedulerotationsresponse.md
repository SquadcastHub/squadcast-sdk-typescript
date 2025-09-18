# RotationsGetScheduleRotationsResponse

The request has succeeded.

## Example Usage

```typescript
import { RotationsGetScheduleRotationsResponse } from "@solarwinds/squadcast-sdk-typescript/models/operations";

let value: RotationsGetScheduleRotationsResponse = {
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
| `data`                                                            | [models.V4RotationResponse](../../models/v4rotationresponse.md)[] | :heavy_check_mark:                                                | N/A                                                               |
| `pageInfo`                                                        | [models.CommonV4PageInfo](../../models/commonv4pageinfo.md)       | :heavy_check_mark:                                                | N/A                                                               |