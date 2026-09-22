# Demo media (per project)

Public assets for pitch demos. **No shared root media** — each project owns its folder.

## Layout

```
{project}/
  videos/                    web-tuned H.264 (~1080p CRF 20 +faststart)
    trailer-{id}.mp4
    vertical/{id}.mp4        portrait snippets
  backdrops/                 web-tuned JPEGs (~1280 max edge)
  thumbs/featured/           landscape featured thumbs
  thumbs/upcoming/           posters / vertical stills (~600–900)
  masters/                   full-quality originals (not referenced by app)
```

App URLs always point at the web-tuned paths, never `masters/`.

## URLs

```
https://raw.githubusercontent.com/studiobrain/sancte-narratio-demo-media/<sha>/{project}/<path>
```

Pin the commit SHA in each app project’s `media.ts` after uploads.
