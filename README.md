# Echo & Ember

Hand-poured, small-batch candles and wax melts, made in South Africa.

**Shop:** https://sueshi789.github.io/EchoAndEmber.za/
**Instagram:** [@echoandember.za](https://instagram.com/echoandember.za)

## How ordering works

1. Browse the range and add items to your cart.
2. Open the cart and tap **Copy order & open Instagram**.
3. Paste the copied order into a DM to [@echoandember.za](https://instagram.com/echoandember.za) to confirm availability, colour, fragrance and delivery.

Free delivery on orders over R800.

## About this site

The whole shop is one file, `index.html`, with no build step and no dependencies. GitHub Pages publishes it straight from the `main` branch.

### Updating products

Products are listed in the `PRODUCTS` array near the bottom of `index.html`. Each product looks like this:

```js
{ id: 21, name: "Product name", tag: "Handmade Candle", desc: "Short description.", price: 300, img: "data:image/jpeg;base64,..." }
```

- `id` must be unique.
- `price` is in Rand (no `R` needed).
- `img` is the product photo. If you leave it out, the card shows an emoji instead (`emoji` and `bg`).

### Previewing locally

Open `index.html` in a browser, or run a local server from this folder:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.
