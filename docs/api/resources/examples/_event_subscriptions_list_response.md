<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "event_subscriptions": [
    {
      "created_at": "2025-09-10T10:08:14Z",
      "description": "ip policy creations",
      "destinations": [
        {
          "id": "ed_32VHc1oq3h721dWZKoqtSS3i2Eo",
          "uri": "https://api.ngrok.com/event_destinations/ed_32VHc1oq3h721dWZKoqtSS3i2Eo"
        }
      ],
      "id": "esb_32VHbyrOG7DuaEoE1pRzOoJG8gW",
      "metadata": "{\"environment\": \"staging\"}",
      "sources": [
        {
          "type": "ip_policy_created.v0",
          "uri": "https://api.ngrok.com/event_subscriptions/esb_32VHbyrOG7DuaEoE1pRzOoJG8gW/sources/ip_policy_created.v0"
        }
      ],
      "uri": "https://api.ngrok.com/event_subscriptions/esb_32VHbyrOG7DuaEoE1pRzOoJG8gW"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/event_subscriptions"
}
```
