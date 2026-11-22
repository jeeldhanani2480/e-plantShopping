# e-plantShopping — Paradise Nursery

**e-plantShopping** is the front end of **Paradise Nursery**, an online houseplant shop built with React, Redux Toolkit and Vite.

## Overview

Paradise Nursery lets users browse a catalog of houseplants, add them to a shopping cart, and manage the cart before checkout.

- **Landing page**: background image, the company name, a paragraph about the company, and a **Get Started** button that opens the product listing.
- **Product listing page**: houseplants grouped into categories (Air Purifying, Aromatic Fragrant, Insect Repellent, Medicinal and Low Maintenance), each with a thumbnail, name, description and price. **Add to Cart** adds the plant and then disables the button.
- **Shopping cart page**: every plant in the cart with its thumbnail, name, unit price and subtotal; buttons to increase, decrease or delete each plant; the total number of plants and the total cost; plus **Continue Shopping** and **Checkout** (Coming Soon) buttons.
- **Navbar**: shown on the product listing and cart pages, with links to Home, Plants and the Cart, and a cart icon that updates with the number of items in the cart.

## Tech stack

- React (function components and hooks: `useState`, `useEffect`)
- Redux Toolkit and React Redux (`CartSlice.jsx`, `store.js`)
- Vite
- GitHub Pages (via `gh-pages`)

## Run locally

```bash
npm install
npm run dev       # development server
npm run preview   # production build served on port 4173
```

## Deploy

```bash
npm run deploy
```

This builds the app and publishes the `dist` folder to the `gh-pages` branch of the e-plantShopping repository.
