# Eleventy playground

- [References](#references)
- [Steps](#steps)

## References

- https://www.11ty.dev/
  - https://www.11ty.dev/docs/
- https://github.com/11ty/eleventy/

## Steps

Refs: https://www.11ty.dev/docs/ and https://github.com/11ty/eleventy/

- `pnpm init`
- `pnpm install -D @11ty/eleventy` → it makes sense to use **-D/--dev** flag
  - https://www.11ty.dev/docs/ → `pnpm install @11ty/eleventy`
  - https://github.com/11ty/eleventy/ → `npm install @11ty/eleventy --save-dev`

Development:
```
$ pnpm exec eleventy --serve
```
Build to **_site** folder:
```
$ pnpm exec eleventy
```
