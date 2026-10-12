# aaronudho.com

This is the built site. Every file here goes in the root of the GitHub repo.

## Adding images

Upload straight into the repo, no folders:

- Product covers: `product-1.jpg`, `product-2.jpg`, `product-3.jpg`, then `product-4.jpg` and so on
- Photos of me: `photo-1.jpg`, then `photo-2.jpg` and so on

No gaps in the numbers. If you skip 4 and upload 5, the site stops looking at 4.
jpg, jpeg, png and webp all work.

## Changing words

Words live in the source project (`src/data.js`), not here. Edit there, run
`npm run build`, upload the new `index.html`.

## Do not delete

`CNAME` keeps aaronudho.com pointed at this repo.
