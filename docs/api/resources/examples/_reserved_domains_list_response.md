<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_32VHZ8QjSyLGjDjL9fVZVEzk7Ov",
        "uri": "https://api.ngrok.com/tls_certificates/cert_32VHZ8QjSyLGjDjL9fVZVEzk7Ov"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.dzkp7hn5cstyf13y.local-ngrok-cname.com",
      "created_at": "2025-09-10T10:07:51Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_32VHZ7XuO6JVatEs2COm5qW3dGS",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_32VHZ7XuO6JVatEs2COm5qW3dGS"
    },
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
          "started_at": "2025-09-10T10:07:51Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.dzkp7hn5cstyf13y.local-ngrok-cname.com",
      "created_at": "2025-09-10T10:07:51Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_32VHZ73OaI6jNPA92Iq5mRUqP3K",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_32VHZ73OaI6jNPA92Iq5mRUqP3K"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-09-10T10:07:21Z",
      "description": "Your dev domain",
      "domain": "trustful-unmeditatively-michaela.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_32VHVKrbmMHlkt3I0ZqAcRxVkVU",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_32VHVKrbmMHlkt3I0ZqAcRxVkVU"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
