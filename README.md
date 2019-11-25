# The first Elevatika website
This is the first elevatika website in 2017. It uses Jekyll. You can preview it here: https://ckcreative.github.io/Elev. The main Elevatika website has since been updated from the ground up and now uses Gatsby.js.

# `_config.yml`

You can edit the `_config.yml` file accordingly. This is a nice landing page that you can host for free on https://netlify.com

```yml
name: Elevatika
title: Elevatika Enterprises
root: https://CkCreative.github.io/Elev/
baseurl: https://CkCreative.github.io/Elev/
permalink: pretty
excerpt_separator: <!--more-->
gems:
  - jekyll-paginate-v2
pagination:
  enabled: true
  per_page: 3
  permalink: '/page/:num/'
  title: ':title - page :num of :max'
  limit: 0
  sort_field: 'date'
  sort_reverse: true
exclude:
  - Gemfile
  - Gemfile.lock
```
