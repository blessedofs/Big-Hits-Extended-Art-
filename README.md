# Big Hit Society Extended Art Gallery

A static, mobile-friendly GitHub Pages website for browsing made-to-order Extended Art Cases and preparing collector requests.

## Publish with GitHub Pages
1. Create a public GitHub repository, e.g. `big-hit-society-gallery`.
2. Upload `index.html`, `style.css`, `script.js`, `cases.js`, and the `assets` folder to the repository root.
3. In repository **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then save.
4. Wait for GitHub to show your live URL.

## Add real cases
1. Upload a photo, e.g. `assets/gengar-001.jpg`.
2. Edit `cases.js` and add an object inside `window.CASES = [ ... ];`:

```js
{ id: 'gengar-001', pokemon: 'Gengar', set: 'Actual Set Name', image: 'assets/gengar-001.jpg', description: 'Holographic extended art' },
```

Only list designs you actually make. Each case is $30, made to order, without a Pokémon card. The gallery and set filters update automatically. A–Z directory uses the Pokémon field.

## Requests
The request button opens the visitor's own email app with a prepared message to `jerry143us@yahoo.com`. The visitor must send it. Instagram links to `@pokemon_tcgguy`, but Instagram messages are **not** sent automatically. For server-side submission and automatic email notifications, connect a form service later. No payments or checkout are processed.

## Pricing
$30 per case, $5 discount for each full group of 3 cases, shipping minimum $5 per order. The total shown is an estimate and may increase with shipping.

## First gallery batch
Ten actual case photos are included in `assets/` and listed in `cases.js`. Set labels marked “Set to confirm” should be verified before publishing a definitive expansion name. Every gallery listing is $30, case only, made to order.

## Exclusives & Promos
The **Exclusives & Promos** tab separates Japanese and Chinese designs. Each entry in `cases.js` may have a `collection` field set to `Japanese Exclusives & Promos` or `Chinese Exclusives & Promos`. This is a browsing category, separate from the original `set` field. The Japanese Tohoku Pikachu promo and Mew is initially included under Chinese Exclusives & Promos; Magikarp and Gardevoir belong to the 30th Celebration set. Language alone does not prove that a card was exclusive to a market, so confirm exclusivity before advertising it as an exclusive release.


Version 4: 20 designs. Added 10 photos including eight Pikachu variants, Mewtwo ex and Dark Tyranitar. The seven 30CE Pikachu cards and Pikachu ex are filed under 30th Celebration. Corrected Mew to 30th Celebration.


## Version 5: Pokémon collection pages
The main gallery shows one tile per Pokémon family. Select a tile to browse and request its individual photographed designs. Pikachu and Pikachu ex appear together, as do Mewtwo and Mewtwo ex. A back button returns to collections. All filters, discount calculations and email-draft requests are preserved.


## Latest upload (60 gallery entries)
Includes 20 previously cataloged designs plus 40 additional photographed entries. Some additional card names and set names require confirmation before publishing as definitive. The `Photo XX` identifiers make these entries easy to find in `cases.js`. No checkout is included.
