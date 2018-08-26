{
  "info": {
    "name": "Rite Kit Auto-Hashtag",
    "_postman_id": "f7a26f0f-4031-4e19-ae09-8fb4b744a44c",
    "description": "Returns auto-hashtagged text of the post.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "c3046ce3-4303-4dc3-b2e1-a98c7801b3fc",
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
          "id": "402f9b12-790f-48b9-bd5d-6296be44ec33"
        }
      ]
    },
    {
      "id": "eb5d737d-7fea-4d43-8a7c-ec8ead9b55d0",
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
          "id": "48412776-0cbe-4ba4-b33c-26faf9df4143"
        }
      ]
    },
    {
      "id": "a6401740-1e2a-4e19-971d-9aa9dc371700",
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
          "id": "3160294a-9364-492b-977d-43e2140e45cb"
        }
      ]
    },
    {
      "id": "e4da2961-fbc1-4958-9d68-5d77ae2c9e68",
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
          "id": "b7f3cf68-c2af-4ad9-bb8d-ac8171eea3be"
        }
      ]
    },
    {
      "id": "106b714d-0774-46d7-b797-322cac8a6c07",
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
          "id": "faa3c22e-c7ca-467c-b4be-10353f5018de"
        }
      ]
    },
    {
      "id": "890dd462-9f98-4186-9be2-2a1a6eaa3b7a",
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
          "id": "2158870b-10b7-45c7-89d0-db488d1f489a"
        }
      ]
    },
    {
      "id": "8835940a-c225-4917-8e63-f3e239f9d547",
      "name": "v1.link.cta.get",
      "request": {
        "url": "http://api.ritekit.com/v1/link/cta",
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
        "description": "Returns list of available CTA for current user. Requires each user to authenticate with RiteKit"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "4761f074-1652-446d-af7f-e658d2d67b6a"
        }
      ]
    },
    {
      "id": "4b0dd74c-b5ca-4ad8-93d1-037fb2de1281",
      "name": "v1.link.short_link.get",
      "request": {
        "url": "http://api.ritekit.com/v1/link/short-link?cta=%7B%7D&url=%7B%7D",
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
        "description": "Returns a shorten link with a given CTA."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "63d91145-6684-4052-b4d3-46c8b1b34d75"
        }
      ]
    },
    {
      "id": "6c84c22d-f108-4648-9639-95e184512190",
      "name": "v1.search.trending.get",
      "request": {
        "url": "http://api.ritekit.com/v1/search/trending?green=%7B%7D&latin=%7B%7D",
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
        "description": "Returns list of hashtags currently trending on Twitter"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "09e78b13-559c-4c45-9c47-71190bd28206"
        }
      ]
    },
    {
      "id": "d24d981c-93e0-4f95-b898-6cab4f05d09f",
      "name": "v1.stats.auto_hashtag_post_post.get",
      "request": {
        "url": {
          "protocol": "http",
          "host": "api.ritekit.com",
          "path": [
            "v1/stats/auto-hashtag?post=:post"
          ],
          "variable": [
            {
              "id": "post",
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
        "description": "Returns auto-hashtagged text of the post."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "69d953c2-10f9-49a7-a94c-8bae34e75ebb"
        }
      ]
    }
  ]
}