# XFetch social preview

1280 x 640 PNG used as the GitHub social preview for `xfetch-cli/xfetch`.

- `xfetch-social-preview.png` — final image (1280 x 640, under 1 MB).
- `xfetch-social-preview.svg` — editable source.
- `term.png` — terminal capture embedded by the SVG.

Regenerate the PNG:

```bash
rsvg-convert -w 1280 -h 640 -o xfetch-social-preview.png xfetch-social-preview.svg
```

GitHub does not expose a REST or GraphQL endpoint for this setting. Upload the
image manually from the repository page:

Settings -> Social preview -> Edit -> Upload an image.
