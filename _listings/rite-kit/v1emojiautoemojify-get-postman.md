{
  "info": {
    "name": "Rite Kit Auto-Emojify",
    "_postman_id": "d2012b3b-9fa4-4e4e-96ec-f9e5ba312a24",
    "description": "Returns text of the post with emoji added",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "1e3d511e-d56f-43f7-91f6-e4f2bbedf68d",
      "name": "v1.emoji.auto_emojify.get",
      "request": {
        "url": "http://api.ritekit.com/v1/emoji/auto-emojify?text=%7B%7D",
        "method": "GET",
        "header": [
          {
            "key": "Accept",
            "value": "*/*",
            "disabled": false
          }
        ],
        "body": {
          "mode": "raw"
        },
        "description": "Returns text of the post with emoji added"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "7be5edb2-721a-454b-9d47-069f378c21a5"
        }
      ]
    }
  ]
}