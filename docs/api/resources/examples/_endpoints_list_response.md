<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-10T10:08:12Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_32VHb2HASdZAcKPMDmLUNjecWeV",
        "uri": "https://api.ngrok.com/reserved_domains/rd_32VHb2HASdZAcKPMDmLUNjecWeV"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_32VHbhhJO14rl6KQkasyntuHwOC",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-09-10T10:08:12Z",
      "uri": "https://api.ngrok.com/endpoints/ep_32VHbhhJO14rl6KQkasyntuHwOC",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-10T10:08:10Z",
      "hostport": "d02cfced2529.ngrok.paid:443",
      "id": "ep_32VHbWtEiMXo7IrHCEQEeFmlNA5",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_32VHUy9nnsaBL2fEh3SdvT5yMLU",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://d02cfced2529.ngrok.paid",
      "tunnel": {
        "id": "tn_32VHbWtEiMXo7IrHCEQEeFmlNA5",
        "uri": "https://api.ngrok.com/tunnels/tn_32VHbWtEiMXo7IrHCEQEeFmlNA5"
      },
      "tunnel_session": {
        "id": "ts_32VHbUBMCRIxPYvW6O5BYce2WSt",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_32VHbUBMCRIxPYvW6O5BYce2WSt"
      },
      "type": "ephemeral",
      "updated_at": "2025-09-10T10:08:10Z",
      "upstream_url": "http://localhost:80",
      "url": "https://d02cfced2529.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-10T10:08:07Z",
      "domain": {
        "id": "rd_32VHb2HASdZAcKPMDmLUNjecWeV",
        "uri": "https://api.ngrok.com/reserved_domains/rd_32VHb2HASdZAcKPMDmLUNjecWeV"
      },
      "edge": {
        "id": "edgtls_32VHb2VuaOr3SLf2bIYb2f5U4NU",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_32VHb2VuaOr3SLf2bIYb2f5U4NU"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_32VHb6tZlxu7dLokAGc4e0xllvW",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-09-10T10:08:07Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
