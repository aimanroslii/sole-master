# 👟 Shoe Marshall

Shoe Marshall is an e-commerce platform where you can explore and buy shoes online. It comes with an admin dashboard that lets you easily manage banners, store items, and product details. You can also analytics like total revenue and customer payments to track your store's performance. 

## 📦 Technologies

- `TypeScript`
- `Next.js`
- `Tailwind CSS`
- `Kinde Auth`
- `PostgreSQL`
- `Redis cache`
- `Stripe`
- `Vault`
- `Shadcn UI`

## 🦄 Features

- Browse and buy shoes online
- Admin dashboard to manage products, banners and store details
- Analytics dashboard with insights on customers and overall store performance with charts and graphs
- Add to cart and complete a smooth checkout flow
- Secure authentication using Oauth2, login and create an account safely
- Dashboard implemented with role-based access control

## 👨🏻‍🍳 The Process

I started by designing and building the API, the foundation for the entire platform. I focused on creating clear, consistent endpoints for managing products, banners, orders, analytics data, and products array at the storefront. Once the backend was running smoothly, I moved on to the front end.

The next step was creating the admin dashboard UI. I began with hardcoded values for all the pages, this helped me visualize the layout, structure, and flow before connecting it to real data. After finalizing the design and interactions, I integrated the dashboard with the API so that all data updates, analytics, and management features worked dynamically.

Then, I built the storefront, the customer-facing side. Just like with the dashboard, I started by setting up all the pages using static data to focus on layout, visuals, and user experience. Once everything looked and felt right, I connected it to the live API to make the store fully functional. 

After integration, I store the collections of product through dashboard, and ran a series of full "happy path" tests to make sure everything, from browsing products to completing a checkout, worked smoothy end to end.

## 💭 How can it be improved? 

- Added product filtering and sorting by price, category, size and popularity
- Added wishlist or favorites, let users save products for later
- Added product reviews and ratings
- Added pagination or infinite scroll, for smoother browsing with many items
- Added inventory management to monitor stock levels and automatically disable out-of-stock items

## 🍿 Video