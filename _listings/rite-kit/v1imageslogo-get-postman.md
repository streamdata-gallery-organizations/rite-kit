{
  "info": {
    "name": "Rite Kit Company Logo",
    "_postman_id": "f005e5d0-03e6-45ef-8640-e3d178630a34",
    "description": "Returns a company logo based on website domain. If the logo is not in our database yet, it will be extracted from the site on the fly. White logo background is automatically removed to make the logo look better on color backgrounds.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "9db71061-026c-468d-b56a-765b5be44193",
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
          "id": "fd2f0f8a-9c89-4e13-bf38-4fca5cc415b2"
        }
      ]
    },
    {
      "id": "13011d43-d14c-4088-8c0f-dad8e8ee194b",
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
          "id": "c976d6d1-92ab-4266-9769-aaf95f926b86"
        }
      ]
    },
    {
      "id": "bdb024c5-b926-4b9f-ab69-7d4fc1161bc9",
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
          "id": "7a33a52a-7dad-4753-ac85-eb8e69b06546"
        }
      ]
    },
    {
      "id": "5cb55e70-a123-43b6-8cc0-03299663177a",
      "name": "v1.images.logo.get",
      "request": {
        "url": "http://api.ritekit.com/v1/images/logo?domain=%7B%7D",
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
        "description": "Returns a company logo based on website domain. If the logo is not in our database yet, it will be extracted from the site on the fly. White logo background is automatically removed to make the logo look better on color backgrounds."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "b41db085-d1f8-4464-b3e4-1448ecc1d047"
        }
      ]
    }
  ]
}