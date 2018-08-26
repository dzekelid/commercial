---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
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
---