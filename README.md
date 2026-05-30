# 🛍️ EMART — React.js E-Commerce Storefront

A responsive e-commerce frontend built with **React.js**, bootstrapped with [Create React App](https://github.com/facebook/create-react-app). EMART provides customers with a clean, modern shopping experience — from browsing products to managing their cart.

> This is the **frontend (customer-facing)** application. It is designed to work alongside a MERN stack backend. See [E-Comm-MernStack](https://github.com/Mdmufid/E-Comm-MernStack) for the full backend + admin setup.

---

## 📸 Preview

> _Add a screenshot or GIF of the app here to help visitors understand what it looks like at a glance._

---

## ✨ Features

- 🏠 **Homepage** — Hero banner, featured products, and category highlights
- 🛒 **Product Listing** — Browse products with category filtering
- 📦 **Product Detail Page** — View images, descriptions, and pricing
- 🛍️ **Shopping Cart** — Add, remove, and update item quantities
- 👤 **User Authentication** — Register and log in to your account
- 📱 **Responsive Design** — Mobile-friendly layout with custom CSS

---

## 🛠️ Tech Stack

| Technology        | Role                              |
|-------------------|-----------------------------------|
| React.js          | UI library / component framework  |
| React Router DOM  | Client-side routing               |
| CSS               | Custom styling & responsive layout|
| Create React App  | Project scaffolding & build tools |

---

## 📁 Project Structure

```
EMART-React.js/
├── public/
│   ├── index.html          # HTML entry point
│   └── favicon.ico
├── src/
│   ├── components/         # Reusable UI components (Navbar, Footer, etc.)
│   ├── pages/              # Page-level components (Home, Products, Cart, etc.)
│   ├── App.js              # Root component with routing
│   ├── index.js            # React DOM entry point
│   └── index.css           # Global styles
├── .gitignore
├── package.json
└── README.md
```

> _Note: Update this structure to match your actual `src/` folder layout._

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher)
- [npm](https://www.npmjs.com/)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Mdmufid/EMART-React.js.git

# 2. Navigate into the project folder
cd EMART-React.js

# 3. Install dependencies
npm install
```

### Running the App

```bash
npm start
```

Opens the app at [http://localhost:3000](http://localhost:3000). The page will hot-reload whenever you make changes.

### Building for Production

```bash
npm run build
```

Creates an optimised production build in the `build/` folder, minified and ready for deployment.

---

## 🔗 Connecting to a Backend

If you are using this with the [E-Comm-MernStack](https://github.com/Mdmufid/E-Comm-MernStack) backend, create a `.env` file in the project root:

```env
REACT_APP_API_URL=http://localhost:5000/api
```

Then use `process.env.REACT_APP_API_URL` in your API calls across the app.

---

## 📜 Available Scripts

| Command           | Description                                      |
|-------------------|--------------------------------------------------|
| `npm start`       | Runs the app in development mode at port 3000    |
| `npm test`        | Launches the test runner in interactive mode     |
| `npm run build`   | Builds the app for production                    |
| `npm run eject`   | Ejects CRA config (one-way, use with caution)    |

---

## 🌐 Deployment

You can deploy the production build to any static hosting platform:

- **[Netlify](https://netlify.com)** — Drag and drop the `build/` folder or connect your GitHub repo
- **[Vercel](https://vercel.com)** — Import directly from GitHub and deploy in seconds
- **[GitHub Pages](https://pages.github.com)** — Install `gh-pages` and add a deploy script

Example deploy script for GitHub Pages (`package.json`):

```json
"homepage": "https://Mdmufid.github.io/EMART-React.js",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to your branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📄 License

This project is open source and free to use.

---

## 👤 Author

**Md Mufid**
GitHub: [@Mdmufid](https://github.com/Mdmufid)
