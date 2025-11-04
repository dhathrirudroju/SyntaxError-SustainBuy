Website link: https://dhathrirudroju.github.io/SyntaxError-SustainBuy/


SustainaBuy: Eco-Friendly E-Commerce Platform

Welcome to SustainaBuy, a conceptual e-commerce platform designed to promote sustainable and ethical shopping. This application uses a simple, front-end structure to showcase products, manage a shopping cart, and implement a unique SustainaPoints reward system based on the eco-friendliness of items purchased.

🌎 Core Mission

Our goal is to encourage conscious consumerism. Every product is assigned an Eco-Score (1-5), and high-scoring items help the user earn reward points faster, incentivizing planet-friendly purchases.

✨ Key Features

Based on the current index.html file, the application includes:

Product Catalog: A fixed list of mock eco-friendly products with prices (in Indian Rupees), categories, brands, and their Eco-Scores.

Filtering System: Users can filter the product list based on minimum Eco-Score, product category, and brand.

Shopping Cart: A functional modal where users can add items, adjust quantities, remove items, and include an optional donation at checkout.

Mock Checkout: A non-functional checkout button that triggers the points calculation and clears the cart.

SustainaPoints Rewards: A real-time balance of rewards that increases after a mock checkout. Users can locally "redeem" 500 points for a mock discount.

Responsive Design: The layout is designed using Tailwind CSS to look great on both mobile devices and desktops.

🛠️ How to Run Locally

Since this is a single, self-contained HTML file, running it is extremely easy:

Save the file: Ensure your code is saved as index.html on your computer.

Open in Browser: Locate the index.html file in your file explorer (Finder/File Explorer) and simply double-click it.

The file will open in your default web browser, and the entire application logic will run instantly.

⚠️ Important Note: Local Mode

This application currently runs entirely in Local Mode:

No Database: All shopping cart data and reward points are stored only in your browser's temporary memory for the current session.

No Persistence: If you close the browser tab or refresh the page, the cart and rewards are reset (unless you manually save your session using the "Reset Session" button which is included for testing).

No Firebase: The Firebase code was intentionally bypassed to make this a simple, shareable front-end demo.

🚀 Future Development Ideas

To turn this into a truly functioning app, you could integrate:

A Real Database (Firestore): To save cart history, user rewards, and product data persistently.

Payment Gateway Integration: To allow real purchases.

User Accounts: For personalized shopping and reward tracking.
