# V3AuditLogsListAuditLogsExportHistoryResponse

Response model for listing audit logs export history

## Example Usage

```typescript
import { V3AuditLogsListAuditLogsExportHistoryResponse } from "@solarwinds/squadcast-sdk-typescript/models";
import { RFCDate } from "@solarwinds/squadcast-sdk-typescript/types";

let value: V3AuditLogsListAuditLogsExportHistoryResponse = {
  data: [
    {
      id: "<id>",
      name: "<value>",
      description: "commandeer astride mask mismatch after beyond uh-huh oof",
      exportedAt: "<value>",
      requestedBy: {
        userID: "<id>",
        userName: "Rosemary58",
        userEmail: "<value>",
        fullName: "Hannah Toy",
      },
      downloadLink: "<value>",
      status: "<value>",
      filters: {
        startDate: new RFCDate("2023-11-24"),
        endDate: new RFCDate("2023-04-14"),
      },
    },
  ],
  metadata: {
    totalCount: 520452,
  },
};
```

## Fields

| Field                                                                                                                              | Type                                                                                                                               | Required                                                                                                                           | Description                                                                                                                        |
| ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| `data`                                                                                                                             | [models.V3AuditLogsAuditLogsExportHistoryResponse](../models/v3auditlogsauditlogsexporthistoryresponse.md)[]                       | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `metadata`                                                                                                                         | [models.V3AuditLogsListAuditLogsExportHistoryResponseMetadata](../models/v3auditlogslistauditlogsexporthistoryresponsemetadata.md) | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |