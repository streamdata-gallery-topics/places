---
swagger: "2.0"
x-collection-name: PredictHQ
x-complete: 0
info:
  title: PredictHQ Search Places
  description: |-
    Use the below parameters to search and filter all places. Places are sorted by relevance (location or text query proximity).

    A search requires at least one of the `q`, `id`, `country` or `location` parameters.
  version: 1.0.0
host: api.predicthq.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/places/:
    get:
      summary: Search Places
      description: |-
        Use the below parameters to search and filter all places. Places are sorted by relevance (location or text query proximity).

        A search requires at least one of the `q`, `id`, `country` or `location` parameters.
      operationId: V1PlacesGet
      x-api-path-slug: v1places-get
      responses:
        200:
          description: OK
      tags:
      - Places
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