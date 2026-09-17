# GFI Everyday — motion landing page

Static site for Gurilla Finance Everyday (Smart Flex spearhead).

## Cloudflare Pages

1. Cloudflare Dashboard → **Workers & Pages** → **Create** → **Pages** → **Connect to Git**
2. Select repo **`radioplayinc/gfi-everyday-lp`**
3. Build settings:
   - **Framework preset:** None
   - **Build command:** *(leave empty)*
   - **Build output directory:** `/` (repo root)
4. Deploy. Add a custom domain under the project’s **Custom domains** tab.

## Local preview

```bash
python3 -m http.server 8080 --directory .
# open http://localhost:8080
```

## Leads

Form posts via FormSubmit → `financegurilla@gmail.com`.
Confirm the FormSubmit activation email in that inbox before paid traffic.

## Stack

HTML / CSS / JS · GSAP CDN · no build step

## Layout

```
index.html
gfi-brand/logo-dark.png
gfi-brand/scatter-cutouts/…
gfi-partner-hub/product-photos/…
```
