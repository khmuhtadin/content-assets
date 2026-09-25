# content-assets

Public host for social post images. Every file here is served straight from
`raw.githubusercontent.com` so schedulers (Repliz) and social platforms can fetch it.

## URL pattern

```
https://raw.githubusercontent.com/khmuhtadin/content-assets/main/<project>/<version>/<pack>/slide_N.png
```

## Layout

- `n8n-nodes-jev-classification/0.3.0/brand-en/` - English carousel, Khaisa Studio pack
- `n8n-nodes-jev-classification/0.3.0/personal-id/` - Indonesian carousel, khmuhtadin pack

Slides are 1080x1350. Add a new `<project>/<version>/` folder per release, never
overwrite an existing one, so a scheduled post never changes under the platform.
