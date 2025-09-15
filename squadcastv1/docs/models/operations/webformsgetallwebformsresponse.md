# WebformsGetAllWebformsResponse

The request has succeeded.

## Example Usage

```typescript
import { WebformsGetAllWebformsResponse } from "SquadcastSDK/models/operations";

let value: WebformsGetAllWebformsResponse = {
  data: [
    {
      id: 320300,
      orgId: "<id>",
      ownerId: "<id>",
      name: "<value>",
      isCname: true,
      publicUrl: "https://heavenly-verve.name",
      tags: {},
      isCaptchaEnabled: false,
      captchaProvider: "<value>",
      captchaSecret: {
        siteKey: "<value>",
        secret: "<value>",
      },
      formOwnerType: "<value>",
      formOwnerId: "<id>",
      formOwnerName: "<value>",
      services: [
        {
          serviceId: "<id>",
          name: "<value>",
          alias: "<value>",
        },
      ],
      inputField: [
        {
          label: "<value>",
          options: [],
        },
      ],
      header: "<value>",
      title: "<value>",
      footerText: "<value>",
      footerLink: "<value>",
      emailOn: [
        "<value 1>",
        "<value 2>",
      ],
      incidentCount: 215432,
      mttr: 944.06,
      isDeleted: false,
      deletedAt: "<value>",
    },
  ],
  meta: {
    totalCount: 242175,
  },
};
```

## Fields

| Field                                                                                          | Type                                                                                           | Required                                                                                       | Description                                                                                    |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| `data`                                                                                         | [models.V3WebformsWebformResponse](../../models/v3webformswebformresponse.md)[]                | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `meta`                                                                                         | [operations.WebformsGetAllWebformsMeta](../../models/operations/webformsgetallwebformsmeta.md) | :heavy_check_mark:                                                                             | N/A                                                                                            |