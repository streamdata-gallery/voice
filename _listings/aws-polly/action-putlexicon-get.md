---
swagger: "2.0"
info:
  title: AWS Polly API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=PutLexicon&k=1:
    get:
      summary: ' Put Lexicon '
      description: Stores a pronunciation lexicon in an AWS Region
      operationId: putLexicon
      parameters:
      - in: query
        name: Name
        description: Name of the lexicon
        type: string
      responses:
        200:
          description: OK
      tags:
      - lexicons
definitions: []
x-collection-name: AWS Polly
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