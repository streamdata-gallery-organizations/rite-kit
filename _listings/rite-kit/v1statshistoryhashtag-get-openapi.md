---
swagger: "2.0"
x-collection-name: Rite Kit
x-complete: 0
info:
  title: Rite Kit Hashtag History
  description: Returns historical stats for a given hashtag from the last 30 days
  version: 1.0.0
host: api.ritekit.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/emoji/auto-emojify:
    get:
      summary: Auto-Emojify
      description: Returns text of the post with emoji added
      operationId: v1.emoji.auto_emojify.get
      x-api-path-slug: v1emojiautoemojify-get
      parameters:
      - in: query
        name: text
        description: Text of the post
      responses:
        200:
          description: OK
      tags:
      - ""
  /v1/emoji/suggestions:
    get:
      summary: Emoji Suggestions
      description: Returns list of emoji suggestions for a given text of the post
      operationId: v1.emoji.suggestions.get
      x-api-path-slug: v1emojisuggestions-get
      parameters:
      - in: query
        name: text
        description: Text of the post
      responses:
        200:
          description: OK
      tags:
      - ""
  /v1/images/animate:
    get:
      summary: Animate Image
      description: Returns URL of an animated GIF.
      operationId: v1.images.animate.get
      x-api-path-slug: v1imagesanimate-get
      parameters:
      - in: query
        name: type
        description: URL of the company
      - in: query
        name: url
        description: URL of the company
      responses:
        200:
          description: OK
      tags:
      - ""
  /v1/images/logo:
    get:
      summary: Company Logo
      description: Returns a company logo based on website domain. If the logo is
        not in our database yet, it will be extracted from the site on the fly. White
        logo background is automatically removed to make the logo look better on color
        backgrounds.
      operationId: v1.images.logo.get
      x-api-path-slug: v1imageslogo-get
      parameters:
      - in: query
        name: domain
        description: URL of the company
      responses:
        200:
          description: OK
      tags:
      - ""
  /v1/images/quote:
    get:
      summary: Text to Image
      description: Returns URL of an image created from text according to given style
        parameters
      operationId: v1.images.quote.get
      x-api-path-slug: v1imagesquote-get
      parameters:
      - in: query
        name: author
        description: Name of the author/source
      - in: query
        name: authorFont
        description: Font-family used for author name
      - in: query
        name: authorFontColor
        description: Font color of the author
      - in: query
        name: backgroundColor
        description: Background color for solid background type
      - in: query
        name: bgType
        description: Background type (gradient/solid)
      - in: query
        name: brandLogo
        description: URL of the brand logo
      - in: query
        name: enableHighlight
        description: Enable highlight on quote text
      - in: query
        name: fontSize
        description: Font size for the quote (author font size is calculated automatically)
      - in: query
        name: gradientColor1
        description: First color for gradient background type
      - in: query
        name: gradientColor2
        description: Second color for gradient background type
      - in: query
        name: gradientType
        description: Type of gradient background (linear/radial)
      - in: query
        name: highlightColor
        description: Color used for highlight
      - in: query
        name: quote
        description: Text of the quote
      - in: query
        name: quoteFont
        description: Font-family used for quote text
      - in: query
        name: quoteFontColor
        description: Font color of the quote text
      responses:
        200:
          description: OK
      tags:
      - ""
  /v1/influencers/hashtag/{hashtag}:
    get:
      summary: Influencers for a Hashtag
      description: Returns list of Twitter influencers for a given hashtag
      operationId: v1.influencers.hashtag.hashtag.get
      x-api-path-slug: v1influencershashtaghashtag-get
      parameters:
      - in: path
        name: hashtag
        description: 'Hashtag without # mark'
      responses:
        200:
          description: OK
      tags:
      - ""
  /v1/link/cta:
    get:
      summary: List of CTAs
      description: Returns list of available CTA for current user. Requires each user
        to authenticate with RiteKit
      operationId: v1.link.cta.get
      x-api-path-slug: v1linkcta-get
      responses:
        200:
          description: OK
      tags:
      - ""
  /v1/link/short-link:
    get:
      summary: Shorten Link
      description: Returns a shorten link with a given CTA.
      operationId: v1.link.short_link.get
      x-api-path-slug: v1linkshortlink-get
      parameters:
      - in: query
        name: cta
        description: cta id
      - in: query
        name: url
        description: URL
      responses:
        200:
          description: OK
      tags:
      - ""
  /v1/search/trending:
    get:
      summary: Trending Hashtags
      description: Returns list of hashtags currently trending on Twitter
      operationId: v1.search.trending.get
      x-api-path-slug: v1searchtrending-get
      parameters:
      - in: query
        name: green
        description: Restrict results only to green hashtags
      - in: query
        name: latin
        description: Restrict results only to hashtags with latin characters
      responses:
        200:
          description: OK
      tags:
      - ""
  /v1/stats/auto-hashtag?post={post}:
    get:
      summary: Auto-Hashtag
      description: Returns auto-hashtagged text of the post.
      operationId: v1.stats.auto_hashtag_post_post.get
      x-api-path-slug: v1statsautohashtagpostpost-get
      parameters:
      - in: path
        name: post
        description: Text of the post
      responses:
        200:
          description: OK
      tags:
      - ""
  /v1/stats/hashtag-suggestions/{topic}:
    get:
      summary: Hashtag Suggestions
      description: Returns list of hashtag suggestions and their real-time stats for
        a given topic
      operationId: v1.stats.hashtag_suggestions.topic.get
      x-api-path-slug: v1statshashtagsuggestionstopic-get
      parameters:
      - in: path
        name: topic
        description: Topic
      responses:
        200:
          description: OK
      tags:
      - ""
  /v1/stats/history/{hashtag}:
    get:
      summary: Hashtag History
      description: Returns historical stats for a given hashtag from the last 30 days
      operationId: v1.stats.history.hashtag.get
      x-api-path-slug: v1statshistoryhashtag-get
      parameters:
      - in: path
        name: hashtag
        description: 'Hashtag without # mark'
      responses:
        200:
          description: OK
      tags:
      - ""
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---