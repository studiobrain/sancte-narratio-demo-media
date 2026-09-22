# Demo media (per project)

Public assets for pitch demos. **No shared root media** — each project owns its folder.

## Layout

```
1615/                   The 16:15 Project
  videos/
  backdrops/
  thumbs/featured/
  thumbs/upcoming/
  masters/              full-quality originals (optional)

sanctenarratio/         Sancte Narratio
  videos/
    trailer-{id}.mp4           landscape trailers
    vertical/{id}.mp4          portrait snippets
  backdrops/backdrop-{id}.jpg
  thumbs/featured/{id}.jpg     landscape featured thumbs
  thumbs/upcoming/poster-{id}.jpg
```

If a title has video but no still, extract a first frame into `backdrops/` + the matching thumb path (expo-image cannot use MP4 URLs).

## URLs

```
https://raw.githubusercontent.com/studiobrain/sancte-narratio-demo-media/<sha>/1615/<path>
https://raw.githubusercontent.com/studiobrain/sancte-narratio-demo-media/<sha>/sanctenarratio/<path>
```

Pin the commit SHA in each app project’s `media.ts` after uploads.
