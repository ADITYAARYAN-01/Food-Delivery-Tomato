# 🍅 Tomato - Food Delivery App

<div align="center">
  <h3>A modern and responsive food delivery web application built with React</h3>
  
  [![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-brightgreen?style=for-the-badge&logo=vercel)](https://food-delivery-tomato-ql6k.onrender.com/)
  [![React](https://img.shields.io/badge/React-18.0+-blue?style=for-the-badge&logo=react)](https://reactjs.org/)
  [![Vite](https://img.shields.io/badge/Vite-Latest-purple?style=for-the-badge&logo=vite)](https://vitejs.dev/)
  
  <p>Browse menus • Add to cart • Place orders • Enjoy delicious food! 🚀</p>
</div>

---

## 📸 Showcase

<table>
  <tr>
    <td align="center"><strong>🏠 Homepage</strong></td>
    <td align="center"><strong>🍽️ Menu & Food Display</strong></td>
  </tr>
  <tr>
    <td><img src="./screenshots/homepage.jpg" alt="Homepage view of the Tomato app showing a header with a large food image and a call to action." width="100%"></td>
    <td><img src="./screenshots/menu.jpg" alt="Menu section showing categories like Salad, Rolls, and Deserts, with a grid of top dishes below." width="100%"></td>
  </tr>
  <tr>
    <td align="center"><strong>🛒 Shopping Cart</strong></td>
    <td align="center"><strong>💳 Checkout Page</strong></td>
  </tr>
  <tr>
    <td><img src="./screenshots/cart.png" alt="Shopping cart view showing a table of items with their title, price, quantity, and total." width="100%"></td>
    <td><img src="./screenshots/checkout.png" alt="Checkout screen with a form for delivery information on the left and cart totals on the right." width="100%"></td>
  </tr>
</table>

---

## ✨ Features

- 🍽️ **Browse Menu**: Interactive and categorized menu to explore different food items
- 🛒 **Shopping Cart**: Fully functional cart to add, remove, and view selected items
- ⚡ **Dynamic UI**: Cart and total amount update instantly as items are added or removed
- 🎨 **Animated Navigation**: Sleek, animated navigation bar for a modern user experience
- 📊 **Order Summary Chart**: Dynamic pie chart on the cart page to visualize cost breakdown
- 📱 **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile
- 🏪 **Customer Showcase**: Stylish section to display trusted restaurant partners

---

## 🛠️ Technologies Used

<div align="center">

| Category | Technology |
|----------|------------|
| **Frontend** | ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white) |
| **State Management** | ![Context API](https://img.shields.io/badge/Context%20API-61DAFB?style=flat&logo=react&logoColor=black) |
| **Routing** | ![React Router](https://img.shields.io/badge/React%20Router-CA4245?style=flat&logo=react-router&logoColor=white) |
| **Animations** | ![Framer Motion](https://img.shields.io/badge/Framer%20Motion-0055FF?style=flat&logo=framer&logoColor=white) |
| **Charts** | ![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chart.js&logoColor=white) |
| **Styling** | ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) |
| **Deployment** | ![Render](https://img.shields.io/badge/Render-46E3B7?style=flat&logo=render&logoColor=white) |

</div>

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:
- ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white) **Node.js** (which includes npm)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ADITYAARYAN-01/Food-Delivery-Tomato.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd Food-Delivery-Tomato
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   
   The application will be available at `http://localhost:5173` 🎉

---

## 📁 Project Structure

```
📦 src/
├── 📁 assets/          # Static assets (images, data)
├── 📁 components/      # Reusable React components
│   ├── Navbar/
│   ├── Footer/
│   └── ...
├── 📁 context/         # Global state management
│   └── StoreContext.js
├── 📁 pages/           # Main application pages
│   ├── Home/
│   ├── Cart/
│   └── PlaceOrder/
├── 📄 App.jsx          # Main app component with routing
└── 📄 main.jsx         # Application entry point
```

---

## 🌐 Deployment

This application is deployed as a **Static Site** on [Render](https://render.com/), with automatic deployments from the `main` branch.

### Deployment Configuration:
- **Build Command**: `npm install && npm run build`
- **Publish Directory**: `dist`
- **Rewrite Rule**: `/* -> /index.html` (for client-side routing support)

> 🔄 **Auto-Deploy**: Any push to the main branch triggers automatic deployment!

---

<div align="center">
  
  ### 🎉 Enjoy your food delivery experience with Tomato!
  
  [![Live Demo](https://img.shields.io/badge/🚀%20Try%20Live%20Demo-Visit%20Now-success?style=for-the-badge)](https://food-delivery-tomato-ql6k.onrender.com/)
  
  ---
  
  **Made with ❤️ by [ADITYAARYAN-01](https://github.com/ADITYAARYAN-01)**
  
</div>