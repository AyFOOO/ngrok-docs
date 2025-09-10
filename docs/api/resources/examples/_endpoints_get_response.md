<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
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
}
```
