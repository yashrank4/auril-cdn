# auril-cdn

Public image storage for the Auril storefront.

Files live at `product/<slug>/<nn>.<ext>`, e.g.

```
https://raw.githubusercontent.com/yashrank4/auril-cdn/main/product/<slug>/01.webp
https://cdn.jsdelivr.net/gh/yashrank4/auril-cdn@v1/product/<slug>/01.webp
```

Images are WebP (product max 1600px, banners max 2400px). Keep the repo under 50 MB — jsDelivr refuses larger GitHub repos. Tag a new version (v2, ...) after changes and bump the tag in storefront.
