# Food Order Web Application

## Overview
This project is a web application for ordering food online. It features a structured file system to ensure maintainability and scalability, with reusable components, static assets, utility functions, and a clear separation of concerns for layouts and pages.

---

## Project Structure

### Root Directory
- **public/**
  - `index.html`: The main HTML file that serves as the entry point of the application.

- **src/**
  - This directory contains the application's source code, organized for better readability and functionality.

### Folders and Files

#### **assets/**
- Contains static assets such as images, icons, and other media files used throughout the app.

#### **components/**
- Houses reusable UI components used across the application.

| File                 | Description                                     |
|----------------------|-------------------------------------------------|
| `CartItem.jsx`       | Component to display individual items in the cart. |
| `EmptyCart.jsx`      | Displays a message when the cart is empty.     |
| `Footer.jsx`         | Footer section of the app.                     |
| `Header.jsx`         | Header section, typically containing navigation.|
| `Hero.jsx`           | Hero section for the main landing page.        |
| `ItemCard.jsx`       | Card component to display individual food items. |
| `Login.jsx`          | Login form component for user authentication.  |
| `Menu.jsx`           | Displays a restaurant's menu.                  |
| `MenuCategory.jsx`   | Component for rendering menu categories.       |
| `PaymentSuccess.jsx` | Page or message for successful payments.       |
| `RestaurantCard.jsx` | Card component for displaying restaurant details. |
| `RestaurantInfo.jsx` | Displays detailed information about a restaurant. |
| `Restaurants.jsx`    | Lists all available restaurants.               |
| `Shimmer.jsx`        | Loading placeholder component.                 |
| `SortRadio.jsx`      | Radio button component for sorting options.    |

#### **layouts/**
- Contains components that structure the layout of the application.

| File       | Description                                    |
|------------|------------------------------------------------|
| `Main.jsx` | Main layout component for structuring pages.   |

#### **pages/**
- Contains components for the application's individual pages.

| File                  | Description                                   |
|-----------------------|-----------------------------------------------|
| `CartPage.jsx`        | Page displaying items in the user's cart.     |
| `Error.jsx`           | Error page for handling 404 or other issues.  |
| `Index.jsx`           | Home page component showcasing featured restaurants. |
| `Offline.jsx`         | Page displayed when the user is offline.      |
| `RestaurantMenu.jsx`  | Displays menu items for a selected restaurant.|

#### **utils/**
- Contains utility functions and helper files for shared logic.

| File         | Description                                    |
|--------------|------------------------------------------------|
| `helper.js`  | Helper functions for various operations.       |

#### Global Styles and Entry Points
- `App.css`: Global CSS styles.
- `App.jsx`: Main application component that ties all components together.
- `index.css`: Global CSS configuration file.
- `index.js`: Entry point of the app.
- `main.jsx`: Main render function.

---

## Getting Started

### Prerequisites
- Node.js (v14 or later)
- npm or yarn

### Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd food-order-web-app
   ```
3. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

### Running the App
1. Start the development server:
   ```bash
   npm start
   # or
   yarn start
   ```
2. Open the app in your browser:
   ```
   http://localhost:3000
   ```

---

## Key Features
- Browse and search for restaurants.
- View restaurant details and menus.
- Add food items to the cart and place orders.
- Responsive design for seamless usage on all devices.
- Dynamic routing and error handling.
- Offline mode for uninterrupted browsing.

---

## Contributing
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

##Screenshots

![Screenshot 2025-01-16 123426](https://github.com/user-attachments/assets/3e5ac444-c47f-492a-9814-4b585251ca85)





![Screenshot 2025-01-16 123444](https://github.com/user-attachments/assets/f683124f-8840-4d5b-981d-814beda8565f)


![Screenshot 2025-01-16 123513](https://github.com/user-attachments/assets/32bdce13-30ae-40ee-aaba-efa6e8c39aee)
![Screenshot 2025-01-16 123530](https://github.com/user-attachments/assets/386a7fb2-88e2-4939-aead-8f2440aee8a1)



## License
This project is licensed under the [MIT License](LICENSE).

