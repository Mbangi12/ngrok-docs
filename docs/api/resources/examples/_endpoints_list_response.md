<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-02-02T10:06:57Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2sTsHhYpmnyQlS2tjVz7zYhtTCS",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2sTsHhYpmnyQlS2tjVz7zYhtTCS"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2sTsIHXS2xAIoAKJ4ZhEgIFvjLX",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-02-02T10:06:57Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2sTsIHXS2xAIoAKJ4ZhEgIFvjLX",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-02T10:06:55Z",
			"hostport": "fd94d02f9ff9.ngrok.paid:443",
			"id": "ep_2sTsI35YxizjQbnH7VZmz65HLuj",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2sTsFgTXMwNWnHYyLTy8R1rssAZ",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://fd94d02f9ff9.ngrok.paid",
			"tunnel": {
				"id": "tn_2sTsI35YxizjQbnH7VZmz65HLuj",
				"uri": "https://api.ngrok.com/tunnels/tn_2sTsI35YxizjQbnH7VZmz65HLuj"
			},
			"tunnel_session": {
				"id": "ts_2sTsI6i7pAMLHuKoi6Kl9ekwF1z",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2sTsI6i7pAMLHuKoi6Kl9ekwF1z"
			},
			"type": "ephemeral",
			"updated_at": "2025-02-02T10:06:55Z",
			"upstream_url": "http://localhost:80",
			"url": "https://fd94d02f9ff9.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-02T10:06:53Z",
			"domain": {
				"id": "rd_2sTsHhYpmnyQlS2tjVz7zYhtTCS",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2sTsHhYpmnyQlS2tjVz7zYhtTCS"
			},
			"edge": {
				"id": "edgtls_2sTsHcZQMZJ5m4RU54loVr1x9dX",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2sTsHcZQMZJ5m4RU54loVr1x9dX"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2sTsHjXlDkxEGTDL7F1skcILaGT",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-02-02T10:06:53Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
