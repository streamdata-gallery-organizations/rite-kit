{
  "info": {
    "name": "Rite Kit Emoji Suggestions",
    "_postman_id": "cf4a7098-c7e0-4061-bb89-007b2e337ef3",
    "description": "Returns list of emoji suggestions for a given text of the post",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "050ff303-95ac-4472-ad69-6498bab62be1",
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
          "id": "d6cdb4da-b6c4-40d6-a315-83bc39f061a6"
        }
      ]
    },
    {
      "id": "7de2ddda-2858-4d1a-89b4-87cf076e562b",
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
          "id": "9d7f1d01-812e-433b-bf47-895116685341"
        }
      ]
    }
  ]
}