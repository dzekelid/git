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
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/apis.md
specificationVersion: "0.14"
apis:
- name: Github Get Gitignore Templates
  x-api-slug: github
  description: |-
    Listing available templates.
    List all templates available to pass as an option when creating a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gitignore/templates
  tags: Gitignore, Templates
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/gitignoretemplates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/gitignoretemplates-get-openapi.md
- name: Github Get Gitignore Templates Language
  x-api-slug: github
  description: Get a single template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gitignore/templates/{language}
  tags: Gitignore, Templates, Language
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/gitignoretemplateslanguage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/gitignoretemplateslanguage-get-openapi.md
- name: Github Add Repos Owner Repo Git Blobs
  x-api-slug: github
  description: Create a Blob.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/blobs
  tags: Repos, Owner, Repo, Git, Blobs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitblobs-post-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitblobsshacode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitblobsshacode-get-openapi.md
- name: Github Add Repos Owner Repo Git Commits
  x-api-slug: github
  description: Create a Commit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/commits
  tags: Repos, Owner, Repo, Git, Commits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitcommits-post-openapi.md
- name: Github Get Repos Owner Repo Git Commits Shacode
  x-api-slug: github
  description: Get a Commit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/commits/{shaCode}
  tags: Repos, Owner, Repo, Git, Commits, Shacode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitcommitsshacode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitcommitsshacode-get-openapi.md
- name: Github Get Repos Owner Repo Git Refs
  x-api-slug: github
  description: Get all References
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/refs
  tags: Repos, Owner, Repo, Git, Refs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitrefs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitrefs-get-openapi.md
- name: Github Add Repos Owner Repo Git Refs
  x-api-slug: github
  description: Create a Reference
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/refs
  tags: Repos, Owner, Repo, Git, Refs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitrefs-post-openapi.md
- name: Github Delete Repos Owner Repo Git Refs Ref
  x-api-slug: github
  description: "Delete a Reference\nExample: Deleting a branch: DELETE /repos/octocat/Hello-World/git/refs/heads/feature-a
    \nExample: Deleting a tag:        DELETE /repos/octocat/Hello-World/git/refs/tags/v1.0"
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/refs/{ref}
  tags: Repos, Owner, Repo, Git, Refs, Ref
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitrefsref-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitrefsref-delete-openapi.md
- name: Github Get Repos Owner Repo Git Refs Ref
  x-api-slug: github
  description: Get a Reference
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/refs/{ref}
  tags: Repos, Owner, Repo, Git, Refs, Ref
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitrefsref-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitrefsref-get-openapi.md
- name: Github Patch Repos Owner Repo Git Refs Ref
  x-api-slug: github
  description: Update a Reference
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/refs/{ref}
  tags: Repos, Owner, Repo, Git, Refs, Ref
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogitrefsref-patch-openapi.md
- name: Github Add Repos Owner Repo Git Tags
  x-api-slug: github
  description: |-
    Create a Tag Object.
    Note that creating a tag object does not create the reference that makes a
    tag in Git. If you want to create an annotated tag in Git, you have to do
    this call to create the tag object, and then create the refs/tags/[tag]
    reference. If you want to create a lightweight tag, you only have to create
    the tag reference - this call would be unnecessary.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/tags
  tags: Repos, Owner, Repo, Git, Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogittags-post-openapi.md
- name: Github Get Repos Owner Repo Git Tags Shacode
  x-api-slug: github
  description: Get a Tag.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/tags/{shaCode}
  tags: Repos, Owner, Repo, Git, Tags, Shacode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogittagsshacode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogittagsshacode-get-openapi.md
- name: Github Add Repos Owner Repo Git Trees
  x-api-slug: github
  description: |-
    Create a Tree.
    The tree creation API will take nested entries as well. If both a tree and
    a nested path modifying that tree are specified, it will overwrite the
    contents of that tree with the new path contents and write a new tree out.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/trees
  tags: Repos, Owner, Repo, Git, Trees
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogittrees-post-openapi.md
- name: Github Get Repos Owner Repo Git Trees Shacode
  x-api-slug: github
  description: Get a Tree.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/trees/{shaCode}
  tags: Repos, Owner, Repo, Git, Trees, Shacode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogittreesshacode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/reposownerrepogittreesshacode-get-openapi.md
- name: Github
  x-api-slug: github
  description: GitHub brings together the worlds largest community of developers to
    discover, share, and build better software. From open source projects to private
    team repositories, were your all-in-one platform for collaborative development.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Git
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/git/master/_listings/github/openapi.md
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