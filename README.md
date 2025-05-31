This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

# 🛒 Modern eCommerce Web App

A fully responsive and feature-rich eCommerce application built with the latest technologies including **Next.js 15**, **React 19**, **MongoDB**, **Tailwind CSS**, and **Shadcn UI**.

---

## 🚀 Tech Stack

- **Next.js 15** – App Router, Server Actions, SSR
- **React 19** – Leveraging the latest features
- **MongoDB** – NoSQL Database for storing users, products, and orders
- **Tailwind CSS** – Utility-first CSS framework for rapid UI styling
- **Shadcn UI** – Accessible and themeable UI components

---

## 🎬 Tutorial Reference

This project is based on the YouTube tutorial by **Code With Yousaf**. You can watch the full video here:

🔗 [Watch on YouTube](https://www.youtube.com/watch?v=s6bJbikLnKM&t=22852s)

---

## 🖼️ Screenshots

### 🏠 Homepage
![Homepage](./public/images/homepage.png)

---

### 🛍️ Product Listing
![Product Listing](./public/images/products.png)

---

### 💳 Checkout Page
![Checkout Page](./public/images/checkout.png)

---

## 📦 Features

- 🔐 User Authentication (Login/Signup)
- 🛍️ Product Browsing with Categories
- 🧺 Cart Management
- 💳 Checkout Flow

---

## 📁 Folder Structure
Folder PATH listing
Volume serial number is 3CD8-BBF1
E:.
|   auth.config.ts
|   auth.ts
|   middleware.ts
|   
+---app
|   |   favicon.ico
|   |   globals.css
|   |   layout.tsx
|   |   
|   +---(auth)
|   |   |   layout.tsx
|   |   |
|   |   +---sign-in
|   |   |       google-signin-form.tsx
|   |   |       page.tsx
|   |   |       signin-form.tsx
|   |   |
|   |   \---sign-up
|   |           page.tsx
|   |           signup-form.tsx
|   |
|   +---(home)
|   |       layout.tsx
|   |       page.tsx
|   |
|   +---(root)
|   |   |   layout.tsx
|   |   |
|   |   +---account
|   |   |   |   layout.tsx
|   |   |   |   page.tsx
|   |   |   |
|   |   |   +---manage
|   |   |   |   |   page.tsx
|   |   |   |   |
|   |   |   |   \---name
|   |   |   |           page.tsx
|   |   |   |           profile-form.tsx
|   |   |   |
|   |   |   \---orders
|   |   |       |   page.tsx
|   |   |       |
|   |   |       \---[id]
|   |   |               page.tsx
|   |   |
|   |   +---cart
|   |   |   |   page.tsx
|   |   |   |
|   |   |   \---[itemId]
|   |   |           add-item-to-cart.tsx
|   |   |           page.tsx
|   |   |
|   |   \---product
|   |       \---[slug]
|   |               page.tsx
|   |               review-list.tsx
|   |
|   +---api
|   |   +---auth
|   |   |   \---[...nextauth]
|   |   |           route.ts
|   |   |
|   |   +---products
|   |   |   \---browsing-history
|   |   |           route.ts
|   |   |
|   |   \---webhooks
|   |       \---stripe
|   |               route.tsx
|   |
|   \---checkout
|       |   checkout-footer.tsx
|       |   checkout-form.tsx
|       |   layout.tsx
|       |   page.tsx
|       |
|       \---[id]
|           \---stripe-payment-success
|                   page.tsx
|
+---components
|   +---shared
|   |   |   browsing-history-list.tsx
|   |   |   cart-sidebar.tsx
|   |   |   client-prividers.tsx
|   |   |   collapsible-on-mobile.tsx
|   |   |   footer.tsx
|   |   |   pagination.tsx
|   |   |   seprator-or.tsx
|   |   |
|   |   +---header
|   |   |       cart-button.tsx
|   |   |       index.tsx
|   |   |       menu.tsx
|   |   |       search.tsx
|   |   |       sidebar.tsx
|   |   |       user-button.tsx
|   |   |
|   |   +---home
|   |   |       home-carousal.tsx
|   |   |       HomeCard.tsx
|   |   |
|   |   +---order
|   |   |       order-details-form.tsx
|   |   |
|   |   \---product
|   |           add-to-browsing-history.tsx
|   |           add-to-cart.tsx
|   |           image-hover.tsx
|   |           product-card.tsx
|   |           product-gallery.tsx
|   |           product-price.tsx
|   |           product-slider.tsx
|   |           product-sort-selector.tsx
|   |           rating-summary.tsx
|   |           rating.tsx
|   |           select-variant.tsx
|   |
|   \---ui
|           badge.tsx
|           button.tsx
|           card.tsx
|           carousel.tsx
|           collapsible.tsx
|           dialog.tsx
|           drawer.tsx
|           dropdown-menu.tsx
|           form.tsx
|           input.tsx
|           label.tsx
|           popover.tsx
|           progress.tsx
|           radio-group.tsx
|           scroll-area.tsx
|           select.tsx
|           separator.tsx
|           sheet.tsx
|           sidebar.tsx
|           skeleton.tsx
|           sonner.tsx
|           table.tsx
|           textarea.tsx
|           toast.tsx
|           toaster.tsx
|           tooltip.tsx
|
+---hooks
|       use-browsing-history.tsx
|       use-cart-sidebar.ts
|       use-cart-store.ts
|       use-device-type.ts
|       use-is-mounted.ts
|       use-mobile.ts
|       use-toast.ts
|
+---lib
|   |   banner.ts
|   |   constant.ts
|   |   data.ts
|   |   menu.ts
|   |   paypal.ts
|   |   reviews.ts
|   |   user-data.ts
|   |   utils.ts
|   |   validator.ts
|   |
|   +---actions
|   |       order-action.ts
|   |       product.actions.ts
|   |       reviw-actions.ts
|   |       user-actions.ts
|   |
|   \---db
|       |   client.ts
|       |   index.ts
|       |   seed.ts
|       |
|       \---models
|               order.model.ts
|               product.model.ts
|               review.model.ts
|               user.model.ts
|
\---types
        index.ts

