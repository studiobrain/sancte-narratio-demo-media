# Demo media (per project)

Public assets for pitch demos. **No shared root media** — each project owns its folder.

## Layout

```
1615/                   The 16:15 Project
  videos/               H.264 ~1080p CRF 20 (+faststart)
  backdrops/            web-tuned JPEGs (hero / details)
  thumbs/featured/
  thumbs/upcoming/
  masters/              full-quality originals (not referenced by app)

sanctenarratio/         Sancte Narratio
  videos/
  backdrops/
  thumbs/featured/
  thumbs/upcoming/
  masters/
```

## URLs

```
https://raw.githubusercontent.com/studiobrain/sancte-narratio-demo-media/<sha>/1615/<path>
https://raw.githubusercontent.com/studiobrain/sancte-narratio-demo-media/<sha>/sanctenarratio/<path>
```

Pin the commit SHA in each app project’s `media.ts` after uploads so URLs stay cache-stable.
