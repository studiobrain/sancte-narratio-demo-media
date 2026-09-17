# Sancte Narratio — demo media

Public progressive assets for the 16:15 funding demo (not app source).

## Layout

```
videos/trailer-{id}.mp4          H.264 ~1080p CRF 20, +faststart
backdrops/backdrop-{id}.jpg      high-res hero / details
thumbs/upcoming/poster-{id}.jpg  poster rail
thumbs/featured/…                featured stills
```

## URLs

```
https://raw.githubusercontent.com/studiobrain/sancte-narratio-demo-media/main/<path>
```

App wiring: `src/catalog/1615-manifest.ts` → `demoMediaUrl(...)`.
