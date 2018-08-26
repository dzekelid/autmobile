---
swagger: "2.0"
x-collection-name: AWS Elastic Beanstalk
x-complete: 1
info:
  title: AWS Elastic Beanstalk API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=RebuildEnvironment:
    get:
      summary: Rebuild Environment
      description: |-
        Deletes and recreates all of the AWS resources (for example: the Auto Scaling group,
              load balancer, etc.
      operationId: rebuildEnvironment
      x-api-path-slug: actionrebuildenvironment-get
      parameters:
      - in: query
        name: EnvironmentId
        description: The ID of the environment to rebuild
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the environment to rebuild
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
---