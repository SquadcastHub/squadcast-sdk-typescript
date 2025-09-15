# V4StatusPagesMaintenancesCreateMaintenanceRequest

## Example Usage

```typescript
import { V4StatusPagesMaintenancesCreateMaintenanceRequest } from "SquadcastSDK/models";

let value: V4StatusPagesMaintenancesCreateMaintenanceRequest = {
  title: "<value>",
  note: "<value>",
  components: [
    782734,
    139121,
  ],
  startTime: new Date("2024-10-11T12:59:43.849Z"),
  endTime: new Date("2024-07-16T23:52:37.002Z"),
};
```

## Fields

| Field                                                                                         | Type                                                                                          | Required                                                                                      | Description                                                                                   |
| --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| `title`                                                                                       | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `note`                                                                                        | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `components`                                                                                  | *number*[]                                                                                    | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `startTime`                                                                                   | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `endTime`                                                                                     | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_check_mark:                                                                            | N/A                                                                                           |