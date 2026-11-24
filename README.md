# Boucherie Olympe: one-page site (v1 draft)

Plain HTML, no build step, nothing to update. Open `index.html` in a browser to see it.

## Add photos
Put JPGs in `photos/` with these names (a striped placeholder shows until the file is there):

| File | Where it shows |
|---|---|
| `devanture.jpg` | Big header photo (shop front, landscape) |
| `boeuf.jpg`, `volaille.jpg`, `maison.jpg` | "Nos produits" cards |
| `noel-1.jpg` … `noel-6.jpg` | "Noël à la boucherie" gallery |

Resize to ~1600 px wide before adding (keeps the page fast). Ask the owner before using photos where staff or customers can be recognised.

## Fill in the details
Search `index.html` for `[` : every `[...]` is a placeholder (town, address, phone, hours, products, Noël order deadline). Also replace `q=Boucherie+Olympe` in the map with the real address.

## Publish (free)
Drag the folder onto Netlify Drop (app.netlify.com/drop) or Cloudflare Pages, or push it to a GitHub repo with Pages on. Then point a domain at it (e.g. boucherie-olympe.fr, ~10 €/year, registered in the shop's name).

## Also do
Add the Noël photos and hours to the shop's Google Business Profile.
