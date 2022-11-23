## API Report File for "@backstage/plugin-events-backend-module-bitbucket-cloud"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
import { BackendFeature } from '@backstage/backend-plugin-api';
import { EventParams } from '@backstage/plugin-events-node';
import { SubTopicEventRouter } from '@backstage/plugin-events-node';

// @public
export class BitbucketCloudEventRouter extends SubTopicEventRouter {
  constructor();
  // (undocumented)
  protected determineSubTopic(params: EventParams): string | undefined;
}

// @alpha
export const bitbucketCloudEventRouterEventsModule: (
  options?: undefined,
) => BackendFeature;
```