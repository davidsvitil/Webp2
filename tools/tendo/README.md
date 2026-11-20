# Aktualizace dat
```bash
python3 tools/tendo/fetch_pages.py urls.txt raw/pages
python3 tools/tendo/parse_shop.py jsonld raw/pages raw/parsed.json
python3 tools/tendo/build_catalog.py raw/parsed.json tendo tools/tendo/config.json
python3 tools/tendo/make_hero.py tendo <id produktu> ...
```
Potřeba: Python 3, Pillow, BeautifulSoup4, lxml, curl.
