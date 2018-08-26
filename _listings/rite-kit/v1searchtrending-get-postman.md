{
  "info": {
    "name": "Rite Kit Trending Hashtags",
    "_postman_id": "b5a7e828-1654-4006-a789-0055ef33e3d8",
    "description": "Returns list of hashtags currently trending on Twitter",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "056ac788-3101-421c-91cf-d0c320271247",
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
          "id": "e4506d3c-9db9-4c22-86ce-2aac55be0606"
        }
      ]
    },
    {
      "id": "e788f9cb-3b30-4108-a3b0-edd681145727",
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
          "id": "764efdd8-865d-49eb-82ad-dd7a718571c8"
        }
      ]
    },
    {
      "id": "a2bc15a4-3af7-4c56-b314-12c40be0c985",
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
          "id": "40702110-ea93-4f3f-accf-e0d39dcadae6"
        }
      ]
    },
    {
      "id": "487c2d32-761d-4ae4-8f4b-2b6f4413290c",
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
          "id": "bfe9bdbb-d135-47ef-be79-de65c2e58e2e"
        }
      ]
    },
    {
      "id": "500d4b33-5bdf-4f9c-aabc-e5506d005086",
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
          "id": "2e5cced1-00f3-44d4-b9e6-dfc506dac5ec"
        }
      ]
    },
    {
      "id": "eb06408f-d0f7-4b42-974b-72d812f8dd6c",
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
          "id": "e39f1403-cc52-4b87-9303-dd8b1d8be336"
        }
      ]
    },
    {
      "id": "1a098f08-425a-4572-8c94-3e5dabdc9d5f",
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
          "id": "e32e7e02-b258-49e2-9a6c-dc93cf8e8d27"
        }
      ]
    },
    {
      "id": "e82bc482-4ef3-4f16-9add-653df4badc61",
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
          "id": "5e16dd3a-6a14-4d4f-8fac-b9c3670daf33"
        }
      ]
    },
    {
      "id": "9b7ce276-2d29-4cd2-b4cf-58b4c7e85421",
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
          "id": "e8aaeb67-ad8d-4afd-9547-1273cc460774"
        }
      ]
    }
  ]
}