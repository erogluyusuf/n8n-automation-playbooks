# Abandoned Cart Recovery

## Description
Automatically detects when a user abandons their shopping cart and triggers a multi-stage recovery sequence via email, potentially offering a discount code if the cart is not claimed within 24 hours.

## Features
- **Webhook Trigger:** Listens for "cart abandoned" events from the e-commerce platform (e.g., Shopify, WooCommerce).
- **Time Delays:** Waits 4 hours before the first reminder, and 24 hours before a final discount offer.
- **Dynamic Content:** Injects the user's name and cart items into the email template.
