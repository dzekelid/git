---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Install a git plugin into a set
  description: Installs a git plugin into a set. Response content will be in the form
    ['gitPluginInstalled' => 'true' / 'false'].
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/plugin_sets/{setId}/plugins/{pluginId}/install_git_plugin:
    post:
      summary: Install a git plugin into a set
      description: Installs a git plugin into a set. Response content will be in the
        form ['gitPluginInstalled' => 'true' / 'false'].
      operationId: postRestPluginSetsSetPluginsPluginInstallGitPlugin
      x-api-path-slug: restplugin-setssetidpluginspluginidinstall-git-plugin-post
      parameters:
      - in: path
        name: pluginId
      - in: path
        name: setId
      responses:
        200:
          description: OK
      tags:
      - Install
      - Git
      - Plugin
      - Into
      - Set
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