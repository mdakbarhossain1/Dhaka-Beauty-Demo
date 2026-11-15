# Dhaka Beauty — Mobile-polished demo v5.0

A Bangla-language, client-facing static storefront demonstration built with HTML, CSS, and vanilla JavaScript.

## What's in the demo
- Homepage, categories, searchable catalog, product detail gallery, and responsive product cards
- Add-to-cart, quantity controls (including Bangla digit handling), persistent cart, cart totals
- Coupon `S10` or `A20` for 10% off, delivery fees, checkout and demonstration order confirmation
- Payment *selection* UI (bKash, Nagad, bank, card, cash on delivery). **No live payment processing**
- Mobile bottom navigation, gallery thumbnails and fixed purchase button

## Local preview
Open `index.html` with VS Code Live Server, or run a local static server in this folder:

```bash
python -m http.server 5500
```

Then visit http://localhost:5500.

## GitHub
Create an empty repository, then in this directory:

```bash
git init
git add .
git commit -m "Dhaka Beauty mobile-polished demo v5"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/dhaka-beauty-demo.git
git push -u origin main
```

If the repo already exists, simply copy the updated files over and run `git add . && git commit -m "Polish mobile product page" && git push`.

## Vercel
Import the GitHub repository at https://vercel.com/new . Set the framework preset to **Other**, root directory **./**, and leave the build command empty. The included `vercel.json` supports static deployment. Update the site by pushing new commits to the connected branch.

## Testing (v5)
- Browser automated checks on **320 / 375 / 390 / 768 / 1440 px** viewport widths.
- Checked product thumbnails no longer overlap stock status/title, product image framing, mobile fixed bottom navigation and sticky purchase alignment.
- Checked quantity `+`, cart update, coupon `S10`, and checkout page navigation.
- Checked home, catalog, both categories, product detail, cart and checkout for horizontal overflow, visible `NaN`, and JavaScript runtime errors.
- These are automated local tests; check the final deployed URL on a physical phone before sharing with a client.

## Demo disclaimer
All product images and information are illustrative. Orders are not sent to a server and real payments are not charged. Actual medicine sales may require legal/regulatory compliance and merchant/payment integrations.
