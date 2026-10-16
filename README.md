# 🛍️ Productly — Product Explorer

Productly is a modern, responsive product browsing application built using React and TypeScript. It allows users to explore products, search by name, filter by category, sort by price, and manage a shopping cart through a clean, user-friendly interface.

## ✨ Features

- **Product Listing:** Display products using reusable product cards.
- **Search Products:** Search products by name.
- **Category Filtering:** Filter products by category.
- **Price Sorting:** Sort products from lowest to highest price.
- **Shopping Cart:** Add products to the cart and view the total price.
- **Buy Now:** Display a demo checkout confirmation.
- **Empty State:** Show a message when no products match the selected filters.
- **Responsive Design:** Support desktop, tablet, and mobile screens.
- **Modern UI:** Clean interface with lavender and pink styling.
- **Reusable Components:** Maintainable React component structure.

## 🛠️ Technologies Used

- React
- TypeScript
- JavaScript (ES6+)
- HTML5
- CSS3
- React Hooks (`useState`, `useMemo`)
- npm

## 📋 Prerequisites

Before running this project, install:

- [Node.js](https://nodejs.org/) — LTS version recommended.
- npm — Included with Node.js.
- [Visual Studio Code](https://code.visualstudio.com/) — Recommended code editor.

## 🚀 Setup Instructions

### 1. Download the project

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual GitHub repository URL.

Alternatively, download the repository as a ZIP file and extract it.

### 2. Open the project folder

Navigate to the project directory:

```bash
cd product-explorer
```

Replace `product-explorer` with your actual folder name if it differs.

### 3. Install dependencies

Open a terminal in the project directory and run:

```bash
npm install
```

This installs the dependencies listed in `package.json`.

### 4. Start the development server

For a Create React App project, run:

```bash
npm start
```

For a Vite project, run:

```bash
npm run dev
```

Use the command configured in your project's `package.json`.

### 5. Open the application

Open the local URL displayed in your terminal.

Common development URLs:

- Create React App: `http://localhost:3000`
- Vite: `http://localhost:5173`

## 📁 Project Structure

```text
product-explorer/
├── public/
├── src/
│   ├── components/
│   │   ├── ProductCard.tsx
│   │   └── ProductFilters.tsx
│   ├── data/
│   │   └── products.ts
│   ├── App.tsx
│   ├── App.css
│   └── index.tsx
├── package.json
├── package-lock.json
└── README.md
```

The exact folder structure may vary depending on your project setup.

## 💻 How to Use

1. Launch the application.
2. Browse the available products.
3. Enter a product name in the search field.
4. Select a category to filter the products.
5. Enable price sorting to arrange products from lowest to highest price.
6. Click **Add to Cart** to add a product to your cart.
7. Click **Cart** to view the cart items and total price.
8. Click **Buy Now** to see the demo checkout confirmation.
9. Clear the filters to display all products again.

## 💰 Price Format

Product prices are displayed in Indian Rupees (INR), using the `₹` symbol and Indian number formatting.

## ⚠️ Limitations

- Cart data is stored in application state and resets when the page is refreshed.
- Checkout is for demonstration purposes only.
- No real payments are processed.
- Product data is stored locally in the project unless otherwise configured.

## 🔮 Future Improvements

- Persistent shopping cart using localStorage.
- Product detail pages.
- Product ratings and reviews.
- Quantity controls and item removal.
- Backend API integration.
- User authentication.
- Payment gateway integration.

## 👨‍💻 Author

Developed as a React and TypeScript Product Explorer project.

## 📄 License

This project is intended for educational and demonstration purposes. Add an appropriate open-source license if you plan to distribute it publicly.
