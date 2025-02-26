---
title: GitHub Actions Variables
allowTitleToDifferFromFilename: true
shortTitle: Variables
intro: 'Use the REST API to interact with variables in {% data variables.product.prodname_actions %}.'
topics:
  - API
versions:
  fpt: '*'
  ghes: '>=3.8'
  ghec: '*'
---

## About variables in {% data variables.product.prodname_actions %}

You can use the REST API to create, update, delete, and retrieve information about variables that can be used in workflows in {% data variables.product.prodname_actions %}. {% data reusables.actions.about-variables %}

{% data reusables.actions.actions-authentication %} {% data variables.product.prodname_github_apps %} must have the `actions_variables/environments/organization_actions_variables` permission to use these endpoints. Authenticated users must have collaborator access to a repository to create, update, or read variables.
