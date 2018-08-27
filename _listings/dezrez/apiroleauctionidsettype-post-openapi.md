---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Set the type of auction role (Commercial or Residential)
  version: 1.0.0
  description: Set the type of auction role (commercial or residential).
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/role/auction/{id}/settype:
    post:
      summary: Set the type of auction role (Commercial or Residential)
      description: Set the type of auction role (commercial or residential).
      operationId: AuctionRole_SetTypeByidByauctionRoleTypeSystemName
      x-api-path-slug: apiroleauctionidsettype-post
      parameters:
      - in: query
        name: auctionRoleTypeSystemName
        description: The auction role type
      - in: path
        name: id
        description: the id of the role
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Set
      - Type
      - Of
      - Auction
      - Role
      - (Commercial
      - Residential)
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