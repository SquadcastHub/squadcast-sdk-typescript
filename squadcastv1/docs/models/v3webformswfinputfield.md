# V3WebformsWFInputField

Input field definition for a webform

## Example Usage

```typescript
import { V3WebformsWFInputField } from "SquadcastSDK/models";

let value: V3WebformsWFInputField = {
  label: "<value>",
  options: [
    "<value 1>",
    "<value 2>",
  ],
};
```

## Fields

| Field                             | Type                              | Required                          | Description                       |
| --------------------------------- | --------------------------------- | --------------------------------- | --------------------------------- |
| `label`                           | *string*                          | :heavy_check_mark:                | Field label                       |
| `options`                         | *string*[]                        | :heavy_check_mark:                | Selectable options for this field |