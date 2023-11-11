# SOA-Subscription
Sub Service

Unzip Membership

-- Start Discovery, API gateway

-- path for calling 
  subscribe -- "http://localhost:8082/membership-service/subscription/subscribe"
  unsubscibed -- "http://localhost:8082/membership-service/subscription/unsubscribe"
  channelGetTotalSubscribe -- "http://localhost:8082/membership-service/subscription/getChannelSubscriptionTotal"


every api is post method with Body/raw/JSON example

{
  "channelId": "somechannelId/Object_id from MongoDB of artist table"
}
