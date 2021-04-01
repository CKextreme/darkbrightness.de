# Partials

"Partials are smaller, context-aware components in your list and
page templates that can be used economically to keep your templating DRY."

> Source: https://gohugo.io/templates/partials/

## Lookup Order

1. `layouts/partials/*<PARTIALNAME>.html`
2. `themes/<THEME>/layouts/partials/*<PARTIALNAME>.html`

> Source: https://gohugo.io/templates/partials/#partial-template-lookup-order

## Return a value from a Partial

e.g. `{{/* return $value */}}` (remove the go template comments /* */)

## Cached Partials

"The partialCached template function can offer significant performance gains
for complex templates that don’t need to be re-rendered on every invocation."

> Source: https://gohugo.io/templates/partials/#cached-partials