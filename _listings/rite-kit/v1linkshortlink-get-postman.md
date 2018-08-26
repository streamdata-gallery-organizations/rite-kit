{
  "info": {
    "name": "Rite Kit Shorten Link",
    "_postman_id": "fd1dd8a9-2037-4b5f-839e-5cdf202b497b",
    "description": "Returns a shorten link with a given CTA.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "0fdd84d5-56d3-40af-b987-82cf51e1cec6",
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
          "id": "9e2debb3-ec26-49c0-af0c-2d29d83ab571"
        }
      ]
    },
    {
      "id": "2f7e82ab-7a4f-4eb7-8cb0-5b0eb6763ccc",
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
          "id": "a57a9b64-fe30-4d10-a9ae-11953c52ae57"
        }
      ]
    },
    {
      "id": "b61e2af2-0618-457f-8916-27faa30b97e4",
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
          "id": "2656114f-f2d9-4635-8e58-3a81b72c4e53"
        }
      ]
    },
    {
      "id": "248727c1-942e-4522-b2b1-476e7d606c65",
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
          "id": "b93c9328-b194-47a6-8052-2611f7f9073c"
        }
      ]
    },
    {
      "id": "00deb927-9724-4971-a1d2-74e23dc5f34b",
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
          "id": "b4fe5ae9-8357-49e4-af71-2bbfbcc0470a"
        }
      ]
    },
    {
      "id": "a770c076-afc6-4936-9a39-409cf28ec04d",
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
          "id": "18cd4bf4-7955-4bad-921e-03ac90038faf"
        }
      ]
    },
    {
      "id": "64586f08-f9fe-4b6d-9481-5d910f7f41ea",
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
          "id": "7bcfdd26-7be1-40db-86d1-1c7780fd6d53"
        }
      ]
    },
    {
      "id": "1053b57d-8d09-4746-8fb7-c6b6d490d729",
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
          "id": "91517ba9-1eb3-4304-ab13-b4124359eee8"
        }
      ]
    }
  ]
}