{
  "info": {
    "name": "LiveChat Delete a webhook",
    "_postman_id": "7d153a58-9d67-4213-a5f6-49a86d7e5815",
    "description": "Deletes a webhook with the given ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Webhook",
      "item": [
        {
          "id": "73b65747-d78a-414a-9ecb-7c19a61c1335",
          "name": "Webhooks12345Delete",
          "request": {
            "url": "http://api.livechatinc.com/webhooks/12345",
            "method": "DELETE",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a webhook with the given ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8fd3cffa-8604-401c-a1c0-4fec027be739"
            }
          ]
        }
      ]
    }
  ]
}