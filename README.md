# Learning-HTML-and-CSS

Course exercise coding and self learning codes

# HTML and CSS Burger Restaurant Project

## Project Overview

This project is a simple responsive website for a burger restaurant. It features a menu, a shopping cart, and detailed product descriptions. The project consists of HTML, CSS, and supporting files, organized for modularity and reusability.

### File Structure

- **cart.html**: The shopping cart page.
- **cart.css**: Styles for the shopping cart page.
- **Final6.html**: The main menu page with categories like Burgers, Sides, Beverages, and Desserts.
- **styles6.css**: Styles for the main menu page.

## Features

- **Responsive Design**: The website adjusts layout for smaller screens using media queries.
- **Tooltip Descriptions**: Hovering over images displays detailed product information.
- **Navigation Menu**: Links to different sections and the shopping cart.
- **Dynamic Content**: Predefined data for items in the menu and shopping cart.

---

## Comments Added to Code

### **cart.css**

```css
/* General reset for body, headings, and tables */
body,
h1,
p,
table {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
}

/* Container styling for central alignment */
.container {
  max-width: 800px;
  margin: 20px auto;
  padding: 20px;
  background: #fff;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

/* Responsive styling for mobile views */
@media (max-width: 600px) {
  .cart-table th,
  .cart-table td {
    font-size: 0.9rem;
    padding: 8px;
  }
}
```

### **cart.html**

```html
<!-- HTML structure for the shopping cart -->
<main>
  <table class="cart-table">
    <thead>
      <tr>
        <th>Item</th>
        <th>Quantity</th>
        <th>Price</th>
        <th>Total</th>
      </tr>
    </thead>
    <tbody>
      <!-- Static values for demonstration purposes -->
    </tbody>
  </table>
</main>
```

### **Final6.html**

```html
<!-- Main page with categories for Burgers, Sides, Beverages, and Desserts -->
<header>
  <div class="logo">Burger Restaurant</div>
  <nav>
    <ul>
      <li><a href="#burgers">Burgers</a></li>
      <li><a href="#sides">Sides</a></li>
      <li><a href="#beverages">Beverages</a></li>
      <li><a href="#desserts">Desserts</a></li>
      <li><a href="cart.html">Cart(3)</a></li>
    </ul>
  </nav>
</header>
```

### **styles6.css**

```css
/* Tooltip styling for detailed information */
.tooltip .tooltiptext {
  visibility: hidden;
  width: 100px;
  color: #271de3;
  text-align: left;
  position: absolute;
  bottom: -25px;
  left: 25%;
  transform: translateX(-50%);
  opacity: 0;
  transition: opacity 0.3s;
}
.tooltip:hover .tooltiptext {
  visibility: visible;
  opacity: 1;
}
```

## How to Run

1. Open `Final6.html` in a web browser to view the main menu.
2. Navigate to `cart.html` for the shopping cart.

---

## Enhancements

- Add JavaScript for interactive cart functionality.
- Dynamic price calculations.
- Database integration for real-time data updates.

---

## Author

Amila Iresh
