# ResponseBody1

## Example Usage

```typescript
import { ResponseBody1 } from "SquadcastSDK/models/operations";

let value: ResponseBody1 = {
  data: {
    createdAt: new Date("2025-04-20T08:01:13.081Z"),
    updatedAt: new Date("2024-02-22T06:50:30.061Z"),
    deletedAt: new Date("2025-12-13T23:43:26.735Z"),
    orgId: "<id>",
    serviceId: "<id>",
    alertSourceVersion: "<value>",
    alertSourceShortname: "<value>",
    overlayTemplateType: "dedup_key",
    overlay: {
      template: "<value>",
      duration: 519447,
    },
    createdBy: "<value>",
    updatedBy: "<value>",
    alertSourceType: "<value>",
  },
};
```

## Fields

| Field                                                                                       | Type                                                                                        | Required                                                                                    | Description                                                                                 |
| ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| `data`                                                                                      | [models.V3ServicesOverlayOverlayResponse](../../models/v3servicesoverlayoverlayresponse.md) | :heavy_check_mark:                                                                          | N/A                                                                                         |