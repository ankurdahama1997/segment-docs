---
title: Userlens Destination
id: 678b412b643761937104abb2
---


[Userlens](https://userlens.io/?utm_source=segmentio&utm_medium=docs&utm_campaign=partners){:target="_blank"} is a product adoption tool for Customer Success. 

Userlens combines 
1. quantitative event-based data through Segment, Amplitude, Mixpanel, and Posthog, 
2. qualitative conversations from Intercom, Zendesk, Gong, and Fireflies
3. commercial information from Salesforce and Hubspot

to give you a full picture of how your accounts/customers/clients health score and adoption of your product.

This destination is maintained by Wudpecker. For any issues with the destination, [contact the Wudpecker Support team](mailto:ankur@wudpecker.io).


## Getting started


1. From your workspace's [Destination catalog page](https://app.segment.com/goto-my-workspace/destinations/catalog){:target="_blank"} search for *Userlens*.
2. Select *Userlens* and click **Add Destination**.
3. Select an existing Source to connect to the Userlens destination.
4. Go to the [Userlens settings](https://app.userlens.io/settings?tab=integrations&subtab=SEGMENT){:target="_blank"} in the Userlens app to copy the **API key**.
5. Enter the **API Key** in the Userlens destination settings in Segment.


## Supported methods

Userlens supports the following methods, as specified in the [Segment Spec](/docs/connections/spec).


### Identify

Send [Identify](/docs/connections/spec/identify) calls to identify users in Userlens. For example:

```js
analytics.identify('userId123', {
  email: 'john.doe@example.com'
});
```

Segment sends Identify calls to Userlens as an `identify` event.


### Track

Send [Track](/docs/connections/spec/track) calls to add events in Userlens. For example:

```js
analytics.track('Login Button Clicked')
```

Segment sends Track calls to Userlens as a `track` event.
