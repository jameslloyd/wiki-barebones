# wiki-barebones
Barebones Wiki based on [mkdocs-material](https://squidfunk.github.io/mkdocs-material/)

# example mkdocs.yml
```
site_name: !ENV SITE_NAME
#site_url: ${SITE_URL}
site_description: >-
  Some long description

theme:
  name: material
  palette:
    scheme: preference
  features:
    - navigation.instant
    - navigation.sections
    - navigation.tabs

plugins:
  - search
markdown_extensions:
  - def_list
  - pymdownx.tasklist:
      custom_checkbox: true
```
