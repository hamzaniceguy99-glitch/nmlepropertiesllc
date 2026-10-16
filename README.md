# NMLE Properties — nmle properties llc

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `nmlepropertiesllc.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/nmlepropertiesllc.mjs`).
> To change the content, edit that file and run `node build.mjs nmlepropertiesllc` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@nmlepropertiesllc.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Direct / $Per parcel / $No) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
NMLE Properties LLC, a limited liability company authorised to transact business in Florida (document number M20000005028), buys and sells vacant land and residential lots for its own account: acquiring parcels directly from owners who want a straightforward sale, researching access, zoning, utilities and flood designation on the parcels it holds, disclosing those findings to buyers rather than leaving them to discover them, and selling with clear title. The company deals as principal and is not a real estate broker. Buyers are expected to carry out their own due diligence before purchase. Site: nmlepropertiesllc.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
