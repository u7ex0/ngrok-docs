<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2024-02-28T17:36:14Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.4jwxhdhhwwyvf465v.local-ngrok-cname.com",
			"created_at": "2024-02-28T17:36:13Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2d0OxLZbaquijgNpikOMfmoQDEE",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2d0OxLZbaquijgNpikOMfmoQDEE"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2d0OxIMZ8Zes1K1xHYRAxJwjrVo",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2d0OxIMZ8Zes1K1xHYRAxJwjrVo"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.4jwxhdhhwwyvf465v.local-ngrok-cname.com",
			"created_at": "2024-02-28T17:36:13Z",
			"domain": "myapp.mydomain.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2d0OxHaslQuapLpoWDrEr1tZB5f",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2d0OxHaslQuapLpoWDrEr1tZB5f"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
