Newlife Impex Stock · สต็อกยา Newlife Impex
https://nanobotco.github.io/newlife-stock/

One page listing the medicines Newlife Impex (Newlife Pharmacy, Nagpur, India) shows on its
IndiaMART site, with the seller's prices in baht, rupees and dollars, in Thai and English.
Not the seller's site.

Search: names, brands, ingredients, makers; near spellings; brand names map to ingredients
(Viagra → sildenafil). Filters: category, ingredient, form, price. Sort: best match, name,
price, ingredient, category. The address bar keeps the search, so a link reopens it.
docs/newlife-stock.csv is the same list as a spreadsheet file.

Built by the private catalog-pipeline:
    node crawl.mjs https://www.newlifeimpex.com
    node indiamart-minisite-extract.mjs cache/www.newlifeimpex.com
    python3 build_site.py data/www.newlifeimpex.com.products.json [prior.json] --out=<this repo>/docs

Coverage: each category page on the seller's site shows its first 40 products; the rest load
only in a browser after "View More". This page holds what those first pages show.

Terms: NOTICE.txt.
