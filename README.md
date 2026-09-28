# Shine My Ride — Premium Detailing Studio

Photography-led editorial site for **Shine My Ride**, a premium car spa / detailing studio in **Varanasi**.

**Services:** Ceramic coating · Teflon coating · Rubbing · Polishing · Deep interior cleaning · Premium detailing

**Contact:** [8299486539](tel:+918299486539) · [WhatsApp](https://wa.me/918299486539)

Static single-page site (`index.html` + `assets/`) for Cloudflare Pages. Dark premium aesthetic driven by real studio photography — not CSS orbs or generic icons.

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

HTML + CSS + light JS. Cormorant Garamond + Inter (Google Fonts). No build step.
