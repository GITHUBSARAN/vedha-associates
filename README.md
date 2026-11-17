# Vedha Associates website

Builders in Chidambaram since 2010: multi-storied buildings, duplex houses and villas with amenities.

## Add photos to the gallery

1. Upload the photo into the `gallery` folder (Add file → Upload files). Keep it under about 1 MB.
2. Edit `gallery/photos.json` and add one entry per photo:

```json
[
  { "file": "duplex-slab.jpg", "caption": "First floor slab casting, duplex at Chidambaram", "category": "ongoing", "date": "2026-11-17" }
]
```

`category` is one of `ongoing`, `completed` or `materials`. The site updates about a minute after you commit.

Image credits for the representative renders are listed in the page footer.
