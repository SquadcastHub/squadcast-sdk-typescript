<!-- Start SDK Example Usage [usage] -->
```typescript
import { SquadcastSDK } from "SquadcastSDK";

const squadcastSDK = new SquadcastSDK({
  bearerAuth: "<YOUR_BEARER_TOKEN_HERE>",
});

async function run() {
  const result = await squadcastSDK.analytics.getOrganization({
    from: "<value>",
    to: "<value>",
  });

  console.log(result);
}

run();

```
<!-- End SDK Example Usage [usage] -->