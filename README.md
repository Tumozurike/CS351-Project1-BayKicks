# Bay Kicks — CS351 Project 1

React/Vite single-page storefront demo for CS351 Project 1.

## Run locally (Windows PowerShell)
1. Open THIS folder in VS Code (the folder that contains package.json).
2. Open Terminal > New Terminal.
3. Run: `npm.cmd install`
4. Run: `npm.cmd run dev`
5. Ctrl+click the localhost URL shown by Vite.

## Included
- 25 products loaded from `src/data/products.json`
- Local product images in `public/images` (no external image links)
- ProductList + ProductCard using props and `.map()`
- Product detail view with size, color, quantity, and Add to Cart validation
- Cart stored in React `useState`, with CartItem, quantity controls, remove, count, and subtotal
- Home, Shop, Product Detail, Account, Create Account, and Cart views
- Bootstrap 5 responsive navigation/layout
- Client-side Create Account validation

Do not upload `node_modules` to GitHub.
