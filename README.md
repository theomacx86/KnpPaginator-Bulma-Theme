# KnpPaginator-Bulma-Theme
A Twig form for Bulma for use with KnpPaginatorBundle  

## How to use
On a twig template, when rendering the pagination:
```TWIG
{{ knp_pagination_render(yourPaginator , 'path/to/KnpPaginator-Bulma.html.twig') }}
```

Or, when configuring KnpPaginationBundle, on paginator.yaml:\
```YAML
knp_paginator:
    template:
        pagination: 'forms/bulmaKNP.html.twig'    
```