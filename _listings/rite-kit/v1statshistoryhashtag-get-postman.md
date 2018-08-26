{
  "info": {
    "name": "Rite Kit Hashtag History",
    "_postman_id": "4b0bc319-f3fb-4b4d-9d65-9ecdfb081301",
    "description": "Returns historical stats for a given hashtag from the last 30 days",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "d455d8a1-2d6c-4389-913c-b96e14e8b2b5",
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
          "id": "1a950762-54e6-4590-be65-6bddbb16f8b0"
        }
      ]
    },
    {
      "id": "a11e6118-f30f-491a-8fc8-4d0ff30fb8dc",
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
          "id": "0f6806a6-9abb-494f-836f-6859caef292f"
        }
      ]
    },
    {
      "id": "34a0c99e-f84e-486a-a615-888ca328ca1e",
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
          "id": "eb98687a-aa7b-467f-8ae9-38d110a220bc"
        }
      ]
    },
    {
      "id": "7e1519bd-dd56-4343-b982-834c0a0e6a00",
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
          "id": "d01b4572-dc01-4357-8300-b845d0f8113f"
        }
      ]
    },
    {
      "id": "6e6136f2-f2d0-4d73-b581-974dcf1fd4e9",
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
          "id": "7e63daee-0e81-44a3-9dd8-8f1b3eafbed6"
        }
      ]
    },
    {
      "id": "798f4844-247c-4608-814d-e0d9499ae030",
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
          "id": "cc6e81bf-1237-451b-90b6-3c478b2ab734"
        }
      ]
    },
    {
      "id": "b20c0268-9297-4ef1-8bc2-2e5a20a3997c",
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
          "id": "e3be6c4e-1879-4d32-8a72-b8e37de49e5f"
        }
      ]
    },
    {
      "id": "861e9c0d-abf3-4c10-a339-8181c28241be",
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
          "id": "703a69a8-a877-4d59-8c05-cfd82eee847d"
        }
      ]
    },
    {
      "id": "67a29b2b-18ca-4eb9-96e5-fc94778b3f18",
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
          "id": "b6b0badd-fac6-4e00-9239-85bcf168baa7"
        }
      ]
    },
    {
      "id": "9bca4dfe-8e79-4708-b4d8-006ed4442661",
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
          "id": "2672ac45-cf97-40e1-ad9a-27e41b6171c9"
        }
      ]
    },
    {
      "id": "e513498b-86e5-411e-bdae-4fa94526793b",
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
          "id": "755a65b2-184f-497b-b2e6-1c38cf6bba72"
        }
      ]
    },
    {
      "id": "96260654-13d5-4f3a-aca8-5b7b195b63fd",
      "name": "v1.stats.history.hashtag.get",
      "request": {
        "url": {
          "protocol": "http",
          "host": "api.ritekit.com",
          "path": [
            "v1/stats/history/:hashtag"
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
        "description": "Returns historical stats for a given hashtag from the last 30 days"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "f8f617f2-1f97-4d43-8dc2-d72648bde287"
        }
      ]
    }
  ]
}