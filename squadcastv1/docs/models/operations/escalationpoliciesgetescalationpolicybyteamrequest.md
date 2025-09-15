# EscalationPoliciesGetEscalationPolicyByTeamRequest

## Example Usage

```typescript
import { EscalationPoliciesGetEscalationPolicyByTeamRequest } from "SquadcastSDK/models/operations";

let value: EscalationPoliciesGetEscalationPolicyByTeamRequest = {};
```

## Fields

| Field                                                                                                           | Type                                                                                                            | Required                                                                                                        | Description                                                                                                     |
| --------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| `ownerId`                                                                                                       | *string*                                                                                                        | :heavy_minus_sign:                                                                                              | here owner_id represents team_id, if  team_id is not provided, it will return escalation policies of all teams. |
| `pageNumber`                                                                                                    | *string*                                                                                                        | :heavy_minus_sign:                                                                                              | N/A                                                                                                             |
| `pageSize`                                                                                                      | *string*                                                                                                        | :heavy_minus_sign:                                                                                              | N/A                                                                                                             |