---
swagger: "2.0"
x-collection-name: Product Hunt
x-complete: 0
info:
  title: Product Hunt Get Categories
  version: 1.0.0
  description: Get categories.
host: api.producthunt.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{username}:
    get:
      summary: Get Users
      description: Get users.
      operationId: getUsersUsername
      x-api-path-slug: usersusername-get
      parameters:
      - in: path
        name: username
      responses:
        200:
          description: OK
      tags:
      - Users
  /categories/{category}/posts:
    get:
      summary: Get Categories
      description: Get categories.
      operationId: getCategoriesCategoryAdds
      x-api-path-slug: categoriescategoryposts-get
      parameters:
      - in: path
        name: category
      - in: query
        name: days_ago
      responses:
        200:
          description: OK
      tags:
      - Categories
x-streamrank:
  polling_total_time_average: "0"
  polling_size_download_average: "0"
  streaming_total_time_average: "0"
  streaming_size_download_average: "0"
  change_yes: "0"
  change_no: "0"
  time_percentage: "0"
  size_percentage: "0"
  change_percentage: "200"
  last_run: ~
  days_run: "0"
  minute_run: "0"
---