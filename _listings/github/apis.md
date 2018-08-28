---
name: GitHub
x-slug: github
description: GitHub brings together the worlds largest community of developers to
  discover, share, and build better software. From open source projects to private
  team repositories, were your all-in-one platform for collaborative development.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
x-kinRank: "10"
x-alexaRank: "64"
tags: Git
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/apis.md
specificationVersion: "0.14"
apis:
- name: GitHub - Add Repos Owner Repo Git Blobs
  x-api-slug: reposownerrepogitblobs-post
  description: Create a Blob.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Social, Coding, Programming, Social, Jobs, Hacker Storytelling, Code, My API
    Stack, Management, Imports, Issues, Issue Management, Change Log Example, Stack
    Network, Stack, SaaS, Technology, Developers, API Provider, API Service Provider,
    Profiles, General Data, Relative Data, Pedestal, Historical Data API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitblobs-post-openapi.md
- name: GitHub - Get Repos Owner Repo Git Blobs Shacode
  x-api-slug: reposownerrepogitblobsshacode-get
  description: |-
    Get a Blob.
    Since blobs can be any arbitrary binary data, the input and responses for
    the blob API takes an encoding parameter that can be either utf-8 or
    base64. If your data cannot be losslessly sent as a UTF-8 string, you can
    base64 encode it.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Social, Coding, Programming, Social, Jobs, Hacker Storytelling, Code, My API
    Stack, Management, Imports, Issues, Issue Management, Change Log Example, Stack
    Network, Stack, SaaS, Technology, Developers, API Provider, API Service Provider,
    Profiles, General Data, Relative Data, Pedestal, Historical Data API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitblobsshacode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitblobsshacode-get-openapi.md
- name: GitHub - Add Repos Owner Repo Git Commits
  x-api-slug: reposownerrepogitcommits-post
  description: Create a Commit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Social, Coding, Programming, Social, Jobs, Hacker Storytelling, Code, My API
    Stack, Management, Imports, Issues, Issue Management, Change Log Example, Stack
    Network, Stack, SaaS, Technology, Developers, API Provider, API Service Provider,
    Profiles, General Data, Relative Data, Pedestal, Historical Data API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitcommits-post-openapi.md
- name: GitHub - Get Repos Owner Repo Git Commits Shacode
  x-api-slug: reposownerrepogitcommitsshacode-get
  description: Get a Commit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Social, Coding, Programming, Social, Jobs, Hacker Storytelling, Code, My API
    Stack, Management, Imports, Issues, Issue Management, Change Log Example, Stack
    Network, Stack, SaaS, Technology, Developers, API Provider, API Service Provider,
    Profiles, General Data, Relative Data, Pedestal, Historical Data API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitcommitsshacode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitcommitsshacode-get-openapi.md
- name: GitHub - Get Repos Owner Repo Git Refs
  x-api-slug: reposownerrepogitrefs-get
  description: Get all References
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Social, Coding, Programming, Social, Jobs, Hacker Storytelling, Code, My API
    Stack, Management, Imports, Issues, Issue Management, Change Log Example, Stack
    Network, Stack, SaaS, Technology, Developers, API Provider, API Service Provider,
    Profiles, General Data, Relative Data, Pedestal, Historical Data API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitrefs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitrefs-get-openapi.md
- name: GitHub - Add Repos Owner Repo Git Refs
  x-api-slug: reposownerrepogitrefs-post
  description: Create a Reference
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Social, Coding, Programming, Social, Jobs, Hacker Storytelling, Code, My API
    Stack, Management, Imports, Issues, Issue Management, Change Log Example, Stack
    Network, Stack, SaaS, Technology, Developers, API Provider, API Service Provider,
    Profiles, General Data, Relative Data, Pedestal, Historical Data API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitrefs-post-openapi.md
- name: GitHub - Delete Repos Owner Repo Git Refs Ref
  x-api-slug: reposownerrepogitrefsref-delete
  description: "Delete a Reference\nExample: Deleting a branch: DELETE /repos/octocat/Hello-World/git/refs/heads/feature-a
    \nExample: Deleting a tag:        DELETE /repos/octocat/Hello-World/git/refs/tags/v1.0"
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Social, Coding, Programming, Social, Jobs, Hacker Storytelling, Code, My API
    Stack, Management, Imports, Issues, Issue Management, Change Log Example, Stack
    Network, Stack, SaaS, Technology, Developers, API Provider, API Service Provider,
    Profiles, General Data, Relative Data, Pedestal, Historical Data API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitrefsref-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitrefsref-delete-openapi.md
- name: GitHub - Get Repos Owner Repo Git Refs Ref
  x-api-slug: reposownerrepogitrefsref-get
  description: Get a Reference
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Social, Coding, Programming, Social, Jobs, Hacker Storytelling, Code, My API
    Stack, Management, Imports, Issues, Issue Management, Change Log Example, Stack
    Network, Stack, SaaS, Technology, Developers, API Provider, API Service Provider,
    Profiles, General Data, Relative Data, Pedestal, Historical Data API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitrefsref-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitrefsref-get-openapi.md
- name: GitHub - Patch Repos Owner Repo Git Refs Ref
  x-api-slug: reposownerrepogitrefsref-patch
  description: Update a Reference
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Social, Coding, Programming, Social, Jobs, Hacker Storytelling, Code, My API
    Stack, Management, Imports, Issues, Issue Management, Change Log Example, Stack
    Network, Stack, SaaS, Technology, Developers, API Provider, API Service Provider,
    Profiles, General Data, Relative Data, Pedestal, Historical Data API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitrefsref-patch-openapi.md
- name: GitHub - Add Repos Owner Repo Git Tags
  x-api-slug: reposownerrepogittags-post
  description: |-
    Create a Tag Object.
    Note that creating a tag object does not create the reference that makes a
    tag in Git. If you want to create an annotated tag in Git, you have to do
    this call to create the tag object, and then create the refs/tags/[tag]
    reference. If you want to create a lightweight tag, you only have to create
    the tag reference - this call would be unnecessary.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Social, Coding, Programming, Social, Jobs, Hacker Storytelling, Code, My API
    Stack, Management, Imports, Issues, Issue Management, Change Log Example, Stack
    Network, Stack, SaaS, Technology, Developers, API Provider, API Service Provider,
    Profiles, General Data, Relative Data, Pedestal, Historical Data API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogittags-post-openapi.md
- name: GitHub - Get Repos Owner Repo Git Tags Shacode
  x-api-slug: reposownerrepogittagsshacode-get
  description: Get a Tag.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Social, Coding, Programming, Social, Jobs, Hacker Storytelling, Code, My API
    Stack, Management, Imports, Issues, Issue Management, Change Log Example, Stack
    Network, Stack, SaaS, Technology, Developers, API Provider, API Service Provider,
    Profiles, General Data, Relative Data, Pedestal, Historical Data API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogittagsshacode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogittagsshacode-get-openapi.md
- name: GitHub - Add Repos Owner Repo Git Trees
  x-api-slug: reposownerrepogittrees-post
  description: |-
    Create a Tree.
    The tree creation API will take nested entries as well. If both a tree and
    a nested path modifying that tree are specified, it will overwrite the
    contents of that tree with the new path contents and write a new tree out.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Social, Coding, Programming, Social, Jobs, Hacker Storytelling, Code, My API
    Stack, Management, Imports, Issues, Issue Management, Change Log Example, Stack
    Network, Stack, SaaS, Technology, Developers, API Provider, API Service Provider,
    Profiles, General Data, Relative Data, Pedestal, Historical Data API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogittrees-post-openapi.md
- name: GitHub - Get Repos Owner Repo Git Trees Shacode
  x-api-slug: reposownerrepogittreesshacode-get
  description: Get a Tree.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Social, Coding, Programming, Social, Jobs, Hacker Storytelling, Code, My API
    Stack, Management, Imports, Issues, Issue Management, Change Log Example, Stack
    Network, Stack, SaaS, Technology, Developers, API Provider, API Service Provider,
    Profiles, General Data, Relative Data, Pedestal, Historical Data API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogittreesshacode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogittreesshacode-get-openapi.md
x-common:
- type: x--net-library
  url: https://github.com/octokit/octokit.net
- type: x-api-gallery
  url: http://giphy.api.gallery.streamdata.io
- type: x-api-stack
  url: http://github.stack.network
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