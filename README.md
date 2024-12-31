
# Restaurant Ordering Web App

This is a Restaurant Ordering Web App built using React. The app allows users to browse restaurants, view menus, add items to the cart, and complete the payment process. The app features dynamic routing, responsive design, and real-time interactions.

## Features

- **Restaurant Browsing**: Browse and view restaurant details, menus, and categories.
- **Cart Management**: Add, remove, and update items in the cart.
- **Responsive Design**: The app is fully responsive and works on all devices.
- **Payment Success**: Displays a success message after completing the payment.
- **Shimmer Loading Effect**: Uses shimmer effect for loading states to enhance the user experience.
- **Error Handling**: Handles errors and displays a custom error page.
- **Offline Mode**: Displays an offline page if the user is not connected to the internet.

## Project Structure

```
- public/
    - index.html
- src/
    - assets/            # Static assets like images, icons, etc.
    - components/        # Reusable components used across the app
        - CartItem.jsx
        - EmptyCart.jsx
        - Footer.jsx
        - Header.jsx
        - Hero.jsx
        - ItemCard.jsx
        - Login.jsx
        - Menu.jsx
        - MenuCategory.jsx
        - PaymentSuccess.jsx
        - RestaurantCard.jsx
        - RestaurantInfo.jsx
        - Restaurants.jsx
        - Shimmer.jsx
        - SortRadio.jsx
    - layouts/           # Layout components to structure pages
        - Main.jsx
    - pages/             # Page-level components
        - CartPage.jsx
        - Error.jsx
        - Index.jsx
        - Offline.jsx
        - RestaurantMenu.jsx
    - utils/             # Utility functions and helper files
        - helper.js
    - App.css            # Global styles
    - App.jsx            # Main app component
    - index.css          # Global CSS
    - index.js           # Entry point of the app
    - main.jsx           # Main render function
```

## Installation

To get started with the project, clone the repository and install the dependencies:

```bash
git clone <repository-url>
cd <project-directory>
npm install
```

## Running the App

To run the app locally in development mode, use the following command:

```bash
npm start
```

This will start the development server and open the app in your browser at `http://localhost:3000`.

## Building for Production

To create a production build of the app, use the following command:

```bash
npm run build
```

This will generate a `build/` folder containing the optimized production files.

## Linting

The project uses ESLint for code linting. To check for linting errors, run:

```bash
npm run lint
```

## Contributing

Feel free to fork the project, make changes, and submit a pull request. Please ensure that your code follows the existing coding style and includes relevant tests.

## License

This project is open-source and available under the [MIT License](LICENSE).
