# TV channel logo index

A weekly-generated JSON index that maps TV channel names to publicly hosted logo images.

* `indeks.json` — `k`: `"country|key"` → image id, `e`: EPG id → image id, `s`: image id → `prefix:path`,
  `baze`: prefix → base URL. Image URL = `baze[prefix] + path`.
* Images are **not stored here**. They are served by their original public sources:
  [tv-logo/tv-logos](https://github.com/tv-logo/tv-logos), [picons/picons](https://github.com/picons/picons)
  (both via jsDelivr), [iptv-org](https://github.com/iptv-org/database) and
  [Wikimedia Commons](https://commons.wikimedia.org) (via Wikidata, property P154).
* Logos are trademarks of their respective owners; licensing of each image follows its source.
