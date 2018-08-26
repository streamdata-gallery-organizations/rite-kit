{
  "info": {
    "name": "Rite Kit Influencers for a Hashtag",
    "_postman_id": "6b7d139b-55df-4bc6-87f5-4489402126fb",
    "description": "Returns list of Twitter influencers for a given hashtag",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "4d0103bf-337b-4aa5-9a47-cba60b89b5fd",
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
          "id": "92b5d753-fb8b-4e6e-b57d-528d630b600f"
        }
      ]
    },
    {
      "id": "05977202-7913-4edf-b5ce-596768790d24",
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
          "id": "23d6f53b-3f14-4048-a2fa-93195a189b73"
        }
      ]
    },
    {
      "id": "c2275afc-d223-4790-a46a-301822441559",
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
          "id": "415397f1-4ef2-450d-8129-e066c025a0ec"
        }
      ]
    },
    {
      "id": "4e683a72-c652-460d-bd99-772571c3063e",
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
          "id": "cc475709-8633-4321-8cea-9aa0d1971200"
        }
      ]
    },
    {
      "id": "a19908b8-94a5-4fd5-913b-3ddf0830eb32",
      "name": "v1.images.quote.get",
      "request": {
        "url": "http://api.ritekit.com/v1/images/quote?author=%7B%7D&authorFont=%7B%7D&authorFontColor=%7B%7D&backgroundColor=%7B%7D&bgType=%7B%7D&brandLogo=%7B%7D&enableHighlight=%7B%7D&fontSize=%7B%7D&gradientColor1=%7B%7D&gradientColor2=%7B%7D&gradientType=%7B%7D&highlightColor=%7B%7D&quote=%7B%7D&quoteFont=%7B%7D&quoteFontColor=%7B%7D",
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
        "description": "Returns URL of an image created from text according to given style parameters"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "95809517-b67b-46ad-afce-4fb9fe89f10c"
        }
      ]
    },
    {
      "id": "89075a3d-9fbb-4bcf-a4b0-54c4b0d101e6",
      "name": "v1.influencers.hashtag.hashtag.get",
      "request": {
        "url": {
          "protocol": "http",
          "host": "api.ritekit.com",
          "path": [
            "v1/influencers/hashtag/:hashtag"
          ],
          "variable": [
            {
              "id": "hashtag",
              "value": "{}",
              "type": "string"
            }
          ]
        },
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
        "description": "Returns list of Twitter influencers for a given hashtag"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "504a135c-e2ce-4481-8726-940217a7bdb4"
        }
      ]
    }
  ]
}