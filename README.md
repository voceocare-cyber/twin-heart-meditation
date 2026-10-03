# Arahant Meditation Centre — website

A single-page static website. No build step, no dependencies, no `npm install`.
Files: `index.html`, `styles.css`.

## Preview it locally

```bash
cd arahant-meditation-centre
python3 -m http.server 8080   # then open http://localhost:8080
```

## Deploy

**Vercel (drag and drop)** — vercel.com → Add New → Project → drag this folder in.
No framework preset and no build command.

Netlify, Cloudflare Pages and GitHub Pages work the same way.

## Page structure

Header, full-bleed hero, About, Twin Heart Meditation, Why people come, Your guide, footer.

There is no contact or address section (removed on request). Worth adding one before go-live.

## Design direction

Light pastel pinks. Fraunces + Outfit. Soft gradient hero (no photo), editorial sections
without card grids or pill buttons. Colours live in `:root` in `styles.css`.

## Editorial rules

The copy deliberately avoids:

- Pranic Healing, research claims, the SAATHIYA programme, and trust affiliation
- spiritual and religious framing, including blessings
- medical claims (benefits are what practitioners report)
- long dashes, in favour of full stops and commas

## Please check the text

The descriptions of the practice and the four session stages were written for this site. Correct
anything that does not match how the sessions actually run.
