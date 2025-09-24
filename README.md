# Sweet Delights Bakery - Website

This folder contains a complete, production-ready bakery website built with Tailwind CSS. It includes a homepage, menu with add-to-cart functionality, cart, checkout, about, and contact pages. All styling is done with Tailwind utilities (no external CSS files).

Files
- index.html: Home with hero, overview, and calls to action.
- menu.html: Bakery menu with items you can add to cart.
- cart.html: View and manage items added to cart, proceed to checkout.
- checkout.html: Collect customer details and process a mock order.
- about.html: Brand story and bakery background.
- contact.html: Contact form for inquiries.
- README.md: This file.

How to run locally
1) Open any of the HTML files directly in a browser. No server is required for this static site.
2) If you want to test cart functionality across pages, start from index.html and navigate to Menu, add items, then view the Cart.
3) Optional: serve locally to simulate a real environment (e.g., python -m http.server in the project root).

Key features
- Category-appropriate design for a bakery: warm colors, friendly typography, and cozy imagery.
- Complete navigation between pages with internal links.
- Menu with Add to Cart functionality using localStorage.
- Cart page showing items and total, with a checkout flow that simulates order placement.
- Responsive, accessible layout using semantic HTML elements (header, nav, main, section, article, footer).

Notes
- All images are placeholders using the template syntax https://images.unsplash.com/photo-1756758187555-711f3075e90f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHwzfHwuLi58ZW58MHwwfHx8MTc1ODcxOTUyNXww&ixlib=rb-4.1.0&q=80&w=1080. Replace with real image paths as needed.
- Font pairing follows the bakery design system: Dancing Script for headings and Lato for body text.
- Color palette for Bakery: Primary #D2691E, Accent #FFB6C1, Background #FFF8DC.
