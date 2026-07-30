# CalcMyPay.co.za

South Africa's personal finance platform — salary, tax, affordability, wealth and career calculators, built on the SARS 2027 tax year.

## Structure
This is a static site — plain HTML/CSS/JS, no build step required.

- All calculator and content pages are top-level `.html` files
- Clean URLs are handled automatically by Cloudflare Pages (`.html` is stripped)
- `sitemap.xml`, `robots.txt`, `ads.txt` are served as-is

## Deployment
Connected to Cloudflare Pages. Every push to `main` triggers an automatic deploy — no build command needed (this is a static site, so leave the Cloudflare build command empty and set the output directory to `/`).
