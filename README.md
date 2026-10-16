# Phone-Catalog

## Overview
Phone Catalog is a modern, responsive e-commerce web platform created strictly following pixel-perfect Figma specifications. The application provides an intuitive browsing experience for various tech devices (Phones, Tablets, and Accessories). Built with performance and usability in mind, it features real-time search, category filtering, dynamic pagination, multi-language support, and persistent state management for cart and favorites across sessions.

## Demo
Explore the live site here: [DEMO](https://lishvets.github.io/Phone-Catalog).

## Key Features
- **Hero Image Slider:** Interactive top-banner carousel with automatic switching and navigation controls.
- **Product Highlights Carousel:** Dedicated horizontal sliders showcasing hot deals and discounted items.
- **Category Navigation:** Direct links and product count indicators for Phones, Tablets, and Accessories.
- **New Arrivals Showcase:** Filtered view highlighting the latest gadgets ordered by release and price.
- **Dynamic Catalog Controls:** Customizable dropdowns for sorting (age, title, price) alongside responsive page size limits and pagination controls.
- **Detailed Item View:** Comprehensive product specifications, image gallery picker, color/capacity options, and breadcrumb navigation (`/product/:productId`).
- **Interactive Shopping Cart:** Full cart workflow including item quantity adjustments, total calculations, persistent storage via `localStorage`, and an interactive checkout modal.
- **Favorites & Wishlist:** Instant item bookmarking with local storage persistence to save items for later.
- **Localization & Themes:** Dark/Light theme switching and English/Ukrainian language toggle with saved user preferences.
- **Robust Routing & Error Pages:** Custom `NotFoundPage` handling for invalid URLs, empty search results, and missing product data.

## Challenges
Building this catalog required solving multiple front-end engineering hurdles to ensure a flawless user journey and reliable application architecture.

### Key Challenges
- **Seamless Data Integration:** Orchestrating dynamic components like custom sliders, multi-criteria filters, search queries, and breadcrumbs into a unified data flow.
- **State Persistence & Synchronization:** Building a reliable global state architecture using React Context API to synchronize cart counts, wishlist status, theme, and language across multiple tabs and pages.
- **Adaptive Layouts:** Crafting custom SCSS layouts and mobile-first navigation menus that deliver a consistent experience across smartphones, tablets, and desktop displays.
- **Graceful Error Recovery:** Implementing fallback states, skeleton loaders, and non-blocking notifications during API calls or network delays.
- **UI/UX Refinement:** Fine-tuning UI interactions, smooth modal transitions, dynamic image galleries, and pagination feedback for an engaging shopping experience.
- **Codebase Maintainability:** Structuring code cleanly with TypeScript interfaces and modular BEM-style SCSS to keep components scalable and easy to extend.

Through continuous refactoring and strict adherence to component-driven design, these challenges were successfully resolved to create a polished, production-ready product.

## Technologies Used
- **React:** UI library for building modular, declarative interface components.
- **TypeScript:** Enforces type safety, interface structures, and better developer feedback.
- **Vite:** High-performance build tool offering instant Hot Module Replacement (HMR).
- **React Router DOM (v6):** Client-side navigation, nested routes, and location tracking.
- **React Context API:** Light-weight global state management solution for theme, language, cart, and wishlist.
- **Sass (SCSS):** Preprocessor enabling structured BEM methodology, variables, and mixins.

## Installation & Setup

To install the project and run it locally, follow these steps:

1. **Clone the repository:**
git clone https://github.com/lishvets/Phone-Catalog.git

2. **Navigate to the project directory:**
cd Phone-Catalog

3. **Install dependencies:**
npm install

4. **Run the project locally:**
npm start

5. **Build & deploy:**

npm run build
npm run deploy

