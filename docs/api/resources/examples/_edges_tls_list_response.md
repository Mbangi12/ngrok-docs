<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-02-02T10:07:02Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2sTsIxn0p010yFtJu0Y2LjmZiwp",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2sTsIxn0p010yFtJu0Y2LjmZiwp"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2sTsHem4XXhWBEQ8ncIc0s8WqAs",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2sTsHem4XXhWBEQ8ncIc0s8WqAs"
				},
				"enabled": true
			},
			"created_at": "2025-02-02T10:06:52Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2sTsHcZQMZJ5m4RU54loVr1x9dX",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2sTsHcZQMZJ5m4RU54loVr1x9dX"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
