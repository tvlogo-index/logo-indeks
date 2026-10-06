# TV channel logo index

A weekly-generated JSON index that maps TV channel names to publicly hosted logo images.

* `indeks.json` — `k`: `"country|key"` → image id, `e`: EPG id → image id, `s`: image id → `prefix:path`,
  `baze`: prefix → base URL. Image URL = `baze[prefix] + path`.
* Most images **are re-hosted in this repository** under `r/` (prefix `r` in `baze`): logos selected from
  [tv-logo/tv-logos](https://github.com/tv-logo/tv-logos), [picons/picons](https://github.com/picons/picons),
  [iptv-org](https://github.com/iptv-org/database) and [Wikimedia Commons](https://commons.wikimedia.org)
  (Wikidata property P154) are downloaded once, normalized (256 px WebP) and stored as `r/<hash>.webp`.
  A tv-logos/picons image whose copy is not available yet is still referenced from its original repository
  (prefixes `t` and `p`, via jsDelivr).
* Also used: [hmlendea/tv-logos](https://github.com/hmlendea/tv-logos) (GPL-3.0, via jsDelivr) and channel lists
  published by [i.mjh.nz](https://i.mjh.nz) (logos re-hosted under `r/`).
* Logos are trademarks of their respective owners; licensing of each image follows its source.
