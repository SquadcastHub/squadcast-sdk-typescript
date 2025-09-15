# EscalationPoliciesGetEscalationPolicyByTeamResponse

The request has succeeded.

## Example Usage

```typescript
import { EscalationPoliciesGetEscalationPolicyByTeamResponse } from "SquadcastSDK/models/operations";

let value: EscalationPoliciesGetEscalationPolicyByTeamResponse = {
  data: [
    {
      id: "<id>",
      name: "<value>",
      description:
        "duh which around collectivization fooey whoa gadzooks extroverted contractor",
      organizationId: "<id>",
      repetition: 816171,
      repeatAfter: 256108,
      rules: [],
      slug: "<value>",
      enableIncidentReminders: false,
      incidentReminderRules: [
        {
          via: [
            "<value 1>",
            "<value 2>",
          ],
          timeInterval: 836581,
          till: 503345,
        },
      ],
      enableIncidentRetrigger: false,
      retriggerAfter: 526033,
      entityOwner: {
        id: "<id>",
        type: "<value>",
      },
      owner: {
        id: "<id>",
        type: "team",
      },
      accessControl: [],
    },
  ],
  meta: {
    totalCount: 732642,
  },
};
```

## Fields

| Field                                                                                                                                    | Type                                                                                                                                     | Required                                                                                                                                 | Description                                                                                                                              |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| `data`                                                                                                                                   | [models.V3EscalationPoliciesEscalationPolicyResponse](../../models/v3escalationpoliciesescalationpolicyresponse.md)[]                    | :heavy_check_mark:                                                                                                                       | N/A                                                                                                                                      |
| `meta`                                                                                                                                   | [operations.EscalationPoliciesGetEscalationPolicyByTeamMeta](../../models/operations/escalationpoliciesgetescalationpolicybyteammeta.md) | :heavy_check_mark:                                                                                                                       | N/A                                                                                                                                      |