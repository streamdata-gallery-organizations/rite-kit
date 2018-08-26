---
swagger: "2.0"
x-collection-name: Rite Kit
x-complete: 0
info:
  title: Rite Kit Auto-Emojify
  description: Returns text of the post with emoji added
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