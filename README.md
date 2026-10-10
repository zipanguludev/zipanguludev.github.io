# zipanguludev.github.io

Showcase site for all Zipangulu mobile apps, published with GitHub Pages at https://zipanguludev.github.io/.

Each app has its own landing site in a separate repository; this page only links to them:

| App | Landing repo | Live site |
|-----|--------------|-----------|
| Counter | [counter-landing](https://github.com/zipanguludev/counter-landing) | https://counterautomate.com/ |
| Operandi | [numberpuzzle-landing](https://github.com/zipanguludev/numberpuzzle-landing) | https://zipanguludev.github.io/numberpuzzle-landing/ |
| WitsAgora | [witsagora-landing](https://github.com/zipanguludev/witsagora-landing) | https://witsagora.com/ |
| CartNap | [cartnap-landing](https://github.com/zipanguludev/cartnap-landing) | https://cartnap.com/ |
| Riviera Rush | [rivierarush-landing](https://github.com/zipanguludev/rivierarush-landing) | https://zipanguludev.github.io/rivierarush-landing/ |

Plain static HTML, no build step: edit `index.html` and push to `main`.

Assets: app icons and store badges in `assets/`, `og-image.png` is the social preview (1200x630).
`app-ads.txt` must stay at the root (used for ad network verification).

## Search Console

The Search Console property `https://zipanguludev.github.io/` (verified by `google391ba1064a62642f.html`, don't delete it) covers this page **and** every project site served under this host (`/numberpuzzle-landing/`, `/rivierarush-landing/`). GitHub Pages only reads `robots.txt` at the host root, so `robots.txt` and `sitemap.xml` here are the only ones for the whole host: when a page is added to one of those project sites, add it to `sitemap.xml` too. Apps on their own domain have their own property and sitemap.
