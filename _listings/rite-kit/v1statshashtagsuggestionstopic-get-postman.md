{
  "info": {
    "name": "Rite Kit Hashtag Suggestions",
    "_postman_id": "183eb0bc-1ce3-4b33-abae-b530abac52b9",
    "description": "Returns list of hashtag suggestions and their real-time stats for a given topic",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "0a24ef5d-b199-465e-a908-0037940382f2",
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
          "id": "2eba689e-9db1-40a8-9e95-ffa5a7b69a2a"
        }
      ]
    },
    {
      "id": "ff8d220a-1182-4b78-b6b4-8b25327325cd",
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
          "id": "2c73fb09-62c7-43dc-902e-6d6bcc666cea"
        }
      ]
    },
    {
      "id": "ad22167b-b4bc-46dd-836c-954c5f08963c",
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
          "id": "733b4565-dfa2-4c2d-a4db-a6ae4a957893"
        }
      ]
    },
    {
      "id": "e2c99256-fc40-42ed-8bdb-f4a4b7c01d81",
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
          "id": "a5c38b75-dc4d-4db8-a54d-bd2e5a4d5a5a"
        }
      ]
    },
    {
      "id": "dc7e2ca3-bf30-48c3-a304-2bbd785ac9ee",
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
          "id": "9b88d90a-cc6b-4422-9ac3-625b9c7b3690"
        }
      ]
    },
    {
      "id": "8d20dfa1-c34f-4891-bdcf-1637bddbaab6",
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
          "id": "7e0bb0c5-0142-476b-a15c-f92a3883f65d"
        }
      ]
    },
    {
      "id": "f29d574f-b0cd-4456-97ef-371e33adfad6",
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
          "id": "df9fb608-0050-4fdd-83f6-ce954b4eef7c"
        }
      ]
    },
    {
      "id": "e1601ec3-c85a-4e19-b0e4-f80d342fa973",
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
          "id": "360ac79b-8b20-4da4-bc82-8d4ed173d610"
        }
      ]
    },
    {
      "id": "51829d1c-7381-421c-8ea0-ed13fd174dfc",
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
          "id": "196ed79a-2bb7-4987-9104-d5eb8d3e4eb7"
        }
      ]
    },
    {
      "id": "af9a107c-52db-4c12-8435-925a40ec46f4",
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
          "id": "382e16e1-111f-48f1-8a07-e5f66749bcda"
        }
      ]
    },
    {
      "id": "1df53256-2058-4081-9938-273e78cffee6",
      "name": "v1.stats.hashtag_suggestions.topic.get",
      "request": {
        "url": {
          "protocol": "http",
          "host": "api.ritekit.com",
          "path": [
            "v1/stats/hashtag-suggestions/:topic"
          ],
          "variable": [
            {
              "id": "topic",
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
        "description": "Returns list of hashtag suggestions and their real-time stats for a given topic"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "b6ac6ccd-6d9b-4861-8048-043428f650c4"
        }
      ]
    }
  ]
}