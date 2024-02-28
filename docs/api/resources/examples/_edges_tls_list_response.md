<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-02-28T17:36:41Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2d0P0jy9KwMyk7CyqSGdG3KpKJQ",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2d0P0jy9KwMyk7CyqSGdG3KpKJQ"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2d0OzFuJCdDCASmuoCnNvs01IXi",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2d0OzFuJCdDCASmuoCnNvs01IXi"
				},
				"enabled": true
			},
			"created_at": "2024-02-28T17:36:29Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2d0OzDmrTwto3aOHG7iuK6hjpvi",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2d0OzDmrTwto3aOHG7iuK6hjpvi"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
