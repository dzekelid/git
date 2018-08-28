swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
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