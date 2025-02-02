<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2025-02-02T10:06:58Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2sTsITv5gSYRFQdXkRJWtCC6kDA",
					"uri": "https://api.ngrok.com/event_destinations/ed_2sTsITv5gSYRFQdXkRJWtCC6kDA"
				}
			],
			"id": "esb_2sTsIS7yMlGNPv8skAvN6FS7uKo",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2sTsIS7yMlGNPv8skAvN6FS7uKo/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2sTsIS7yMlGNPv8skAvN6FS7uKo"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
