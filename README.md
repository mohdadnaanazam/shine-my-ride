# Shine My Ride — Premium Detailing Studio

Dark automotive luxury site for **Shine My Ride**, a premium car spa / detailing studio in **Varanasi**.

**Services:** Ceramic coating · Teflon coating · Rubbing · Polishing · Deep interior cleaning · Premium detailing

**Contact:** [8299486539](tel:+918299486539) · [WhatsApp](https://wa.me/918299486539)

Static single-page site (`index.html`) for Cloudflare Pages. Design uses layered depth, perspective hero, and soft CSS 3D accents.

## Local

Open `index.html` in a browser, or:

```bash
npx --yes serve .
```

## Deploy

```bash
git push origin main

export CLOUDFLARE_API_TOKEN=…   # from secrets; never commit
npx wrangler pages deploy . --project-name=shine-my-ride --commit-dirty=true
```

## Stack

HTML + CSS + light JS. Inter (Google Fonts). No build step.
