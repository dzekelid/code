---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Repos Owner Repo Stats Code Frequency
  description: |-
    Get the number of additions and deletions per week.
    Returns a weekly aggregate of the number of additions and deletions pushed
    to a repository.
  termsOfService: https://help.github.com/articles/github-terms-of-service/#b-api-terms
  version: 1.0.0
host: api.github.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /repos/{owner}/{repo}/commits/{shaCode}:
    get:
      summary: Get Repos Owner Repo Commits Shacode
      description: Get a single commit.
      operationId: get-a-single-commit
      x-api-path-slug: reposownerrepocommitsshacode-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      - in: path
        name: shaCode
        description: SHA-1 code of the commit
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Commits
      - Shacode
  /repos/{owner}/{repo}/commits/{shaCode}/comments:
    get:
      summary: Get Repos Owner Repo Commits Shacode Comments
      description: List comments for a single commitList comments for a single commit.
      operationId: list-comments-for-a-single-commitlist-comments-for-a-single-commit
      x-api-path-slug: reposownerrepocommitsshacodecomments-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      - in: path
        name: shaCode
        description: SHA-1 code of the commit
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Commits
      - Shacode
      - Comments
    post:
      summary: Add Repos Owner Repo Commits Shacode Comments
      description: Create a commit comment.
      operationId: create-a-commit-comment
      x-api-path-slug: reposownerrepocommitsshacodecomments-post
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      - in: path
        name: shaCode
        description: SHA-1 code of the commit
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Commits
      - Shacode
      - Comments
  /repos/{owner}/{repo}/git/blobs/{shaCode}:
    get:
      summary: Get Repos Owner Repo Git Blobs Shacode
      description: |-
        Get a Blob.
        Since blobs can be any arbitrary binary data, the input and responses for
        the blob API takes an encoding parameter that can be either utf-8 or
        base64. If your data cannot be losslessly sent as a UTF-8 string, you can
        base64 encode it.
      operationId: get-a-blobsince-blobs-can-be-any-arbitrary-binary-data-the-input-and-responses-forthe-blob-api-takes
      x-api-path-slug: reposownerrepogitblobsshacode-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      - in: path
        name: shaCode
        description: SHA-1 code
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Git
      - Blobs
      - Shacode
  /repos/{owner}/{repo}/git/commits/{shaCode}:
    get:
      summary: Get Repos Owner Repo Git Commits Shacode
      description: Get a Commit.
      operationId: get-a-commit
      x-api-path-slug: reposownerrepogitcommitsshacode-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      - in: path
        name: shaCode
        description: SHA-1 code
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Git
      - Commits
      - Shacode
  /repos/{owner}/{repo}/git/tags/{shaCode}:
    get:
      summary: Get Repos Owner Repo Git Tags Shacode
      description: Get a Tag.
      operationId: get-a-tag
      x-api-path-slug: reposownerrepogittagsshacode-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      - in: path
        name: shaCode
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Git
      - Tags
      - Shacode
  /repos/{owner}/{repo}/git/trees/{shaCode}:
    get:
      summary: Get Repos Owner Repo Git Trees Shacode
      description: Get a Tree.
      operationId: get-a-tree
      x-api-path-slug: reposownerrepogittreesshacode-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: owner
        description: Name of repository owner
      - in: query
        name: recursive
        description: Get a Tree Recursively
      - in: path
        name: repo
        description: Name of repository
      - in: path
        name: shaCode
        description: Tree SHA
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Git
      - Trees
      - Shacode
  /repos/{owner}/{repo}/stats/code_frequency:
    get:
      summary: Get Repos Owner Repo Stats Code Frequency
      description: |-
        Get the number of additions and deletions per week.
        Returns a weekly aggregate of the number of additions and deletions pushed
        to a repository.
      operationId: get-the-number-of-additions-and-deletions-per-weekreturns-a-weekly-aggregate-of-the-number-of-additi
      x-api-path-slug: reposownerrepostatscode-frequency-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Stats
      - Code
      - Frequency
      - Aggregation
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