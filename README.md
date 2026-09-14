# Webflow Cinematic Assets

A centralized library of generated cinematic assets and frame sequences used by our Webflow client websites.

## Folder convention

Organize assets by client, then by animation:

```
client-name/
    hero/
    other-animation-name/
```

Use lowercase kebab-case for future client folder names. Place frame files directly inside their animation folder and preserve their original filenames, format, dimensions, and quality.

## JP Elite Services

`jp-elite-services/hero/` contains 301 original WebP frames, from `frame_0001.webp` through `frame_0301.webp`.

jsDelivr base URL:

```
https://cdn.jsdelivr.net/gh/mackuha/webflow-cinematic-assets@main/jp-elite-services/hero/
```
