# Axiom
Starting point for Ghost theme development

> An axiom is a statement that is so evident or well-established, that it is accepted without controversy or question. Thus, the axiom can be used as the premise or starting point for further reasoning or arguments. — [Wikipedia](https://en.wikipedia.org/wiki/Axiom)

## Features

- Modular
    - Author header
    - Blog header
    - Post header
    - Tag header
    - Posts Loop
    - Blog footer
    - Post footer
    - Post navigation
    - Navigation
    - Pagination
- No HTML classes
- No CSS
- No JS
- Google Analytics

## Runnning for development

```
docker run -v $(pwd)/src:/var/lib/ghost/themes/axiom -p 2368:2368 -d jameskolce/axiom
```