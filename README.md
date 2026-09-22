# Sancte Narratio — demo media

Public assets for pitch demos. Two **projects** share this repo; each has its own top-level folder.

## Layout

```
1615/                   The 16:15 Project (live demo)
  videos/               H.264 ~1080p CRF 20 (+faststart)
  backdrops/            web-tuned JPEGs (hero / details) — app URLs
  thumbs/               web-tuned posters / featured
  masters/              full-quality JPEG originals (not referenced by app)

sanctenarratio/         Sancte Narratio (assets TBD)
  videos/
  backdrops/
  thumbs/
  masters/
```

**Legacy root** `videos/`, `backdrops/`, `thumbs/`, `masters/` remain for the currently deployed 1615 build (root-level URLs). Do not delete them until that subdomain is redeployed against `1615/` paths.

## URLs

```
https://raw.githubusercontent.com/studiobrain/sancte-narratio-demo-media/main/1615/<path>
https://raw.githubusercontent.com/studiobrain/sancte-narratio-demo-media/main/sanctenarratio/<path>
```

Legacy (live 1615 until cutover):

```
https://raw.githubusercontent.com/studiobrain/sancte-narratio-demo-media/main/<path>
```
