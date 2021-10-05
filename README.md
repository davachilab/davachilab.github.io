# Welcome to the Davachi Lab Wiki!

## site.pages

<!-- prettier-ignore-start -->

| source          | link                                                           |
| --------------- | -------------------------------------------------------------- |
{% for page in site.pages -%}
| {{ page.path }} | [{{ page.url | relative_url }}]({{ page.url | relative_url }}) |
{% endfor %}

<!-- prettier-ignore-end -->

## Documents

https://jekyll-rtd-theme.rundocs.io

## Local debug

```sh
make
make server
```

## The license

The theme is available as open source under the terms of the MIT License
