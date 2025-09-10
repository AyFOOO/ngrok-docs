<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-09-10T10:08:18Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_32VHcVVcDfLntqhzDMFu3TCErlu",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_32VHcVVcDfLntqhzDMFu3TCErlu"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_32VHb2bAab3gT8sIzxMDyJy5Lql",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_32VHb2bAab3gT8sIzxMDyJy5Lql"
        },
        "enabled": true
      },
      "created_at": "2025-09-10T10:08:07Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_32VHb2VuaOr3SLf2bIYb2f5U4NU",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_32VHb2VuaOr3SLf2bIYb2f5U4NU"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
