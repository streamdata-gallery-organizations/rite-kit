{
  "info": {
    "name": "Rite Kit Animate Image",
    "_postman_id": "45a50c10-b354-44ba-8039-05ae9a44caed",
    "description": "Returns URL of an animated GIF.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "9fbe0dfc-f499-4fb5-be0b-d9b0ad2a84b4",
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
          "id": "fca9d6fd-de46-453a-86c6-36b9e5b3b04e"
        }
      ]
    },
    {
      "id": "f9414c64-dca8-41cf-9d0d-7666683401dd",
      "name": "v1.emoji.suggestions.get",
      "request": {
        "url": "http://api.ritekit.com/v1/emoji/suggestions?text=%7B%7D",
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
        "description": "Returns list of emoji suggestions for a given text of the post"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "b3a2af82-7618-444f-b1b9-df7ce8c0ea9b"
        }
      ]
    },
    {
      "id": "7319286b-0525-4506-b826-1f2b05a97e50",
      "name": "v1.images.animate.get",
      "request": {
        "url": "http://api.ritekit.com/v1/images/animate?type=%7B%7D&url=%7B%7D",
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
        "description": "Returns URL of an animated GIF."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "18d5e85d-609c-4e64-a3af-096c8b6e8337"
        }
      ]
    }
  ]
}