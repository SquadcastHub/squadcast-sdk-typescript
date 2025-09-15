# GlobalEventRulesListGlobalEventRulesResponse

The request has succeeded.

## Example Usage

```typescript
import { GlobalEventRulesListGlobalEventRulesResponse } from "SquadcastSDK/models/operations";

let value: GlobalEventRulesListGlobalEventRulesResponse = {
  data: [],
  meta: {
    totalCount: 297097,
  },
};
```

## Fields

| Field                                                                                                                      | Type                                                                                                                       | Required                                                                                                                   | Description                                                                                                                |
| -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| `data`                                                                                                                     | [models.V3GlobalEventRulesGlobalEventRuleInList](../../models/v3globaleventrulesglobaleventruleinlist.md)[]                | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `meta`                                                                                                                     | [operations.GlobalEventRulesListGlobalEventRulesMeta](../../models/operations/globaleventruleslistglobaleventrulesmeta.md) | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |