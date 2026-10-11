# Phone Catalog

A responsive web application for browsing a catalog of smartphones, tablets, and accessories. The project showcases an online store interface: users can review product specifications, select model options, save devices they like, and manage their shopping cart.

## Demo

[Open Phone Catalog](https://freelinex.github.io/react_phone-catalog_project/)

## Technologies Used

- **React 18 and TypeScript** — component-based interface and data typing.
- **React Router 6** — navigation between pages and storing catalog parameters in the URL.
- **React Context API and useReducer** — managing the state of the shopping cart and favorites.
- **SCSS and CSS Modules** — responsive styling and component style isolation.
- **Swiper and React Swipeable** — sliders and gesture-based photo switching.
- **Fetch API** — loading the catalog from static JSON files.
- **localStorage** — saving the shopping cart and favorites between visits.
- **Vite and Mate Scripts** — development and build tools.
- **ESLint, Stylelint, and Prettier** — code validation and formatting.
- **GitHub Pages** — hosting the demo.

## Running Locally

To run the application, you'll need **Node.js 20** and **npm**.

1. Clone the repository and navigate to the project folder:

   ```bash
   git clone https://github.com/freelinex/react_phone-catalog_project.git
   cd react_phone-catalog_project
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Run the application:

   ```bash
   npm start
   ```

4. Open the local URL displayed in the terminal after startup.

To create a production build, run:

```bash
npm run build
```

## Features

- **Responsive interface** for smartphones, tablets, and computers, including a mobile menu.
- **Three product categories:** smartphones, tablets, and accessories.
- **Catalog sorting** by newest, title, and price.
- **Pagination** with a choice of items per page: 4, 8, 16, or all. Sorting and page settings are saved in the URL.
- **Detailed product page** with a photo gallery, description, technical specifications, and a selection of available colors and storage capacities.
- **Favorites** with a separate page and the ability to save selected items to localStorage.
- **Shopping Cart** with the ability to change quantities, remove items, and automatically calculate the total cost. The contents are saved after the page is reloaded.
- **Sliders on the home page:** promotional banners, new models, and discounted products. The product page includes a “You may also like” section.
- **Loading and error states:** card placeholders, error messages, and the option to reload the catalog.
- **Convenient navigation:** breadcrumbs and a page for unknown routes.

The **Checkout** button opens a pop-up window prompting the user to clear the cart. Order placement and payment are not yet implemented.
