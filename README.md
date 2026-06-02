# Flower Finder Image Packs

Hosted reference-photo packs for Flower Finder.

Production index:
`https://raw.githubusercontent.com/juleshaggard/FlowerFinderImagePacks/main/index.json`

## Published Files

- `index.json` lists all available regional packs.
- `<Region>/manifest.json` lists each region's image records, byte counts, and SHA-256 checksums.
- `<Region>/images/` contains the cached reference images used by the app.

## Image Profile

Pack images are optimized JPEG bytes stored with `.img` file names. The current
profile is max edge 640 px, JPEG quality 72. The app decodes images by byte
content, so the extension stays stable while download size stays much smaller.

## Current Packs

| Region | Photos | Size |
| --- | ---: | ---: |
| Africa | 17,983 | 670 MB |
| Asia | 10,273 | 387 MB |
| Australia | 10,789 | 382 MB |
| Europe | 8,504 | 333 MB |
| New Zealand | 2,463 | 103 MB |
| North America | 21,479 | 832 MB |
| Pacific Islands | 2,218 | 82 MB |
| South America | 16,053 | 592 MB |

These packs are WFO-matched iNaturalist reference photos with open-compatible
licenses (`cc0`, `cc-by`, or `cc-by-sa`) harvested for Flower Finder's regional
image-pack cache.
