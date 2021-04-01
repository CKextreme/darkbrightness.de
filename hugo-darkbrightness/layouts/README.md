
# GoHugo's Lookup Order

## Page Kinds

- Home (/index.html)
- Page (/posts/my-post/index.html)
- Section (/posts/index.html)
- Taxonomy (/tags/index.html)
- Term (/tags/awesome/index.html)

> Source: https://gohugo.io/templates/section-templates/#page-kinds

## Lookup Rules

### Lookup with Theme
"In Hugo, layouts can live in either the project’s or the themes' layout folders,
and the most specific layout will be chosen.
Hugo will interleave the lookups listed below,
finding the most specific one either in the project or themes."

> Source: https://gohugo.io/templates/lookup-order/#hugo-layouts-lookup-rules-with-theme

### Regular Page (Page Kind = page)

A single page with regular content like a blog article etc.

> Source: https://gohugo.io/templates/lookup-order/#examples-layout-lookup-for-regular-pages

### Home Page (Page Kind = home)

Also known as the `index` page which is first shown by entering the webpage.

> Source: https://gohugo.io/templates/lookup-order/#examples-layout-lookup-for-home-page

### Section Page (Page Kind = section)

Is the landing page of a given kind of section (e.g. `/posts` or `/blog` directory).
"A Section is a collection of pages that gets defined based on the organization structure under the `content/` directory."
(Source: https://gohugo.io/content-management/sections/)

> Source: https://gohugo.io/templates/lookup-order/#examples-layout-lookup-for-section-pages

#### Define a Section in a subfolder

"If a user needs to define a section foo at a deeper level, they need to create a directory named foo with an _index.md file [...]"

> Source: https://gohugo.io/content-management/sections/

### Taxonomy Page (Page Kind = taxonomy)

> Source: https://gohugo.io/templates/lookup-order/#examples-layout-lookup-for-taxonomy-pages

### Term Page (Page Kind = term)

> Source: https://gohugo.io/templates/lookup-order/#examples-layout-lookup-for-term-pages