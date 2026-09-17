# Gurilla Finance — Everyday landing page

Static site for GFI Everyday (free Smart Flex path if you qualify).

## Cloudflare Pages setup

1. In Cloudflare Dashboard → **Workers & Pages** → **Create** → **Pages** → **Connect to Git**
2. Select this repo
3. Settings:
   - **Framework preset:** None
   - **Build command:** *(empty)*
   - **Build output directory:** `/` (leave as root)
4. Save and deploy

Custom domain: Pages → your project → Custom domains.

## Leads

`index.html` posts to [FormSubmit](https://formsubmit.co) → `financegurilla@gmail.com`.
**First production submit:** check that inbox and confirm the FormSubmit activation email.

## Local preview

```bash
python3 -m http.server 8080 --directory .
```

## Stack

- Static HTML / CSS / JS
- GSAP ScrollTrigger (CDN)
- No build step
