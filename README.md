# Paradise Nursery Shopping Application

**Paradise Nursery** is an online plant shop built with React, Vite and Redux Toolkit.

## Features

- **Landing page** – background image, company name, "Get Started" button and an About Us section.
- **Product listing page** – houseplants grouped into categories (Air Purifying, Aromatic Fragrant, Insect Repellent, Medicinal, Low Maintenance). Each plant shows a thumbnail, name, description and price, plus an "Add to Cart" button that is disabled once the plant is in the cart.
- **Navbar** – links to Home, Plants and Cart, with a cart icon showing the total number of items.
- **Shopping cart page** – thumbnail, name and unit price of each plant, per-item subtotal, total cart amount, increase/decrease quantity buttons, delete button, "Continue Shopping" and "Checkout" (Coming Soon).

## Tech stack

- React 18 + Vite
- Redux Toolkit / React Redux (cart state in `src/CartSlice.jsx`)

## Run locally

```bash
npm install
npm run dev
```
