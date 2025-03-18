# Deno Subhost

## Compiler Options

## The hono/jsx runtime

### Options

docType: string The doctype to use in the generated HTML. Default is
`<!DOCTYPE html>`

`stream`

## The hono/jsx/dom runtime

There is a small JSX Runtime for Client Components. Using this will result in
smaller bundled results than using hono/jsx. Specify hono/jsx/dom in
tsconfig.json, or for Deno modify the deno.json:

```json
"compilerOptions": {
"jsx": "react-jsx",
    "jsxImportSource": "hono/jsx/dom"
}
```
