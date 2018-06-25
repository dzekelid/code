---
name: GitHub
x-slug: github
description: GitHub brings together the worlds largest community of developers to
  discover, share, and build better software. From open source projects to private
  team repositories, were your all-in-one platform for collaborative development.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
x-kinRank: "10"
x-alexaRank: "64"
tags: Code
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/apis.md
specificationVersion: "0.14"
apis:
- name: Github Get Repos Owner Repo Commits Shacode
  x-api-slug: github
  description: Get a single commit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/commits/{shaCode}
  tags: Repos, Owner, Repo, Commits, Shacode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/reposownerrepocommitsshacode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/reposownerrepocommitsshacode-get-openapi.md
- name: Github Get Repos Owner Repo Commits Shacode Comments
  x-api-slug: github
  description: List comments for a single commitList comments for a single commit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/commits/{shaCode}/comments
  tags: Repos, Owner, Repo, Commits, Shacode, Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/reposownerrepocommitsshacodecomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/reposownerrepocommitsshacodecomments-get-openapi.md
- name: Github Add Repos Owner Repo Commits Shacode Comments
  x-api-slug: github
  description: Create a commit comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/commits/{shaCode}/comments
  tags: Repos, Owner, Repo, Commits, Shacode, Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/reposownerrepocommitsshacodecomments-post-openapi.md
- name: Github Get Repos Owner Repo Git Blobs Shacode
  x-api-slug: github
  description: |-
    Get a Blob.
    Since blobs can be any arbitrary binary data, the input and responses for
    the blob API takes an encoding parameter that can be either utf-8 or
    base64. If your data cannot be losslessly sent as a UTF-8 string, you can
    base64 encode it.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/blobs/{shaCode}
  tags: Repos, Owner, Repo, Git, Blobs, Shacode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/reposownerrepogitblobsshacode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/reposownerrepogitblobsshacode-get-openapi.md
- name: Github Get Repos Owner Repo Git Commits Shacode
  x-api-slug: github
  description: Get a Commit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/commits/{shaCode}
  tags: Repos, Owner, Repo, Git, Commits, Shacode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/reposownerrepogitcommitsshacode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/reposownerrepogitcommitsshacode-get-openapi.md
- name: Github Get Repos Owner Repo Git Tags Shacode
  x-api-slug: github
  description: Get a Tag.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/tags/{shaCode}
  tags: Repos, Owner, Repo, Git, Tags, Shacode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/reposownerrepogittagsshacode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/reposownerrepogittagsshacode-get-openapi.md
- name: Github Get Repos Owner Repo Git Trees Shacode
  x-api-slug: github
  description: Get a Tree.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/trees/{shaCode}
  tags: Repos, Owner, Repo, Git, Trees, Shacode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/reposownerrepogittreesshacode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/reposownerrepogittreesshacode-get-openapi.md
- name: Github Get Repos Owner Repo Stats Code Frequency
  x-api-slug: github
  description: |-
    Get the number of additions and deletions per week.
    Returns a weekly aggregate of the number of additions and deletions pushed
    to a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/stats/code_frequency
  tags: Repos, Owner, Repo, Stats, Code, Frequency,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/reposownerrepostatscode-frequency-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/reposownerrepostatscode-frequency-get-openapi.md
- name: Github Get Search Code
  x-api-slug: github
  description: Search code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////search/code
  tags: Search, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/searchcode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/searchcode-get-openapi.md
- name: Github
  x-api-slug: github
  description: GitHub brings together the worlds largest community of developers to
    discover, share, and build better software. From open source projects to private
    team repositories, were your all-in-one platform for collaborative development.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/github/openapi.md
x-common:
- type: x--net-library
  url: https://github.com/octokit/octokit.net
- type: x-base
  url: https://api.github.com
- type: x-blog
  url: http://github.com/blog
- type: x-blog-rss
  url: https://github.com/blog/subscribe
- type: x-change-log
  url: https://developer.github.com/changes/
- type: x-contact-form
  url: https://github.com/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/github
- type: x-crunchbase
  url: https://crunchbase.com/organization/github
- type: x-developer
  url: https://developer.github.com/
- type: x-github
  url: https://github.com/github
- type: x-guides
  url: https://developer.github.com/guides/
- type: x-ios-sdk
  url: https://github.com/octokit/octokit.objc
- type: x-pricing
  url: https://github.com/pricing
- type: x-privacy
  url: http://help.github.com/privacy-policy/
- type: x-ruby-library
  url: https://github.com/octokit/octokit.rb
- type: x-security
  url: http://help.github.com/security/
- type: x-status
  url: https://status.github.com/
- type: x-terms-of-service
  url: http://help.github.com/terms-of-service/
- type: x-transparency-report
  url: https://github.com/blog/1987-github-s-2014-transparency-report
- type: x-twitter
  url: https://twitter.com/github
- type: x-webhooks
  url: https://developer.github.com/webhooks/
- type: x-website
  url: https://github.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---