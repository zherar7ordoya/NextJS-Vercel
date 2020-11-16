# NextJS v10

1. [GitHub](https://github.com/zherar7ordoya/ZeroNextJS.git)
2. [Vercel](https://zero-next-js.vercel.app/)

## Paquetes

### date-fns

Provides the most comprehensive, yet simple and consistent toolset for
manipulating **JavaScript dates** in **a browser** & **Node.js**.

### gray-matter

Parse front-matter from a string or file. Fast, reliable and easy to use. Parses
YAML front matter by default, but also has support for YAML, JSON, TOML or
Coffee Front-Matter, with options to set custom delimiters. Used by metalsmith,
assemble, verb and many other projects.

> **[Reference:](https://nextjs.org/learn/basics/data-fetching/blog-data)** You
> might have noticed that each markdown file has a metadata section at the top
> containing `title` and `date`. This is called YAML Front Matter, which can be
> parsed using a library called
> [gray-matter](https://github.com/jonschlinkert/gray-matter).

**YAML Front Matter:** _YFM is an_ **optional** _section of valid YAML that is
placed at the top of a page and is used for maintaining metadata for the page
and its contents._

— Front matter

-   YAML can be used at the top of Markdown documents to add more structured
    data.
-   Surround the YAML with two lines of consecutive dashes.

```yaml
---
name: "Venus"
discoverer: "Galileo Galilei"
---

**Venus** is the second planet from the Sun, orbiting it every 224.7 Earth days.
```

**YAML** es un formato para guardar objetos de datos con estructura de árbol.
Sus siglas significan _YAML Ain’t Markup Language_ (YAML no es otro lenguaje de
marcado).

Este lenguaje es muy legible para las personas, más legible que un **JSON** y
sobretodo que **XML**.

Se utiliza normalmente para:

-   Archivos de configuración
-   Traducciones
-   Representar información

¿Por que utilizar un YAML en vez de un JSON/XML ?

-   Un formato mucho más amigable
-   Fácil de entender rápidamente
-   Facilita el mapeo de estructuras de datos complejas.

Un dato importante es que no se usa para Web Services o APIs Rest, ya que como
se menciona antes, normalmente es utilizado como archivo de configuración.

### remark

[Unified](https://github.com/unifiedjs/unified) processor to parse and serialize
Markdown. Built on [micromark](https://github.com/micromark/micromark). Powered
by [plugins](https://github.com/remarkjs/remark/blob/main/doc/plugins.md). Part
of the [unified](https://github.com/unifiedjs/unified) collective.

> **[Reference:](https://nextjs.org/learn/basics/dynamic-routes/render-markdown)**
> To render markdown content, we’ll use the
> [`remark`](https://github.com/remarkjs/remark) library.

### remark-html

[**remark**](https://github.com/remarkjs/remark) plugin to serialize Markdown as
HTML.

---

#### What is the difference between .ts and .tsx extensions?

Use .ts for pure Typescript files.

Use .tsx for files which contain JSX.

> For example, a React component would be .tsx but a file containing helper
> functions would be .ts
