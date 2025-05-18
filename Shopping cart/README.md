# Interactive Shopping Cart Application

## Overview

This project is an **interactive shopping cart application** built with **React** that supports adding, removing, and updating items in real-time. It leverages advanced JavaScript array methods such as `filter`, `map`, `find`, and `reduce` to efficiently manage cart state and operations.

## Why This Matters

Replicating e-commerce functionality is a fundamental exercise for full-stack engineers. This project helped me deepen my understanding of:

- React props and hooks for state and component communication  
- Real-time UI updates reflecting user interactions  
- Applying advanced JavaScript methods for data manipulation  
- Managing complex UI states typical of product-based platforms  

These skills empower companies to build seamless, intuitive shopping experiences that drive higher conversion rates and enhance customer satisfaction.

## Technologies Used

- React  
- JavaScript (ES6+)  

## Features

- Add products to the shopping cart  
- Remove items from the cart  
- Update item quantities dynamically  
- Calculate total price using `reduce`  
- Real-time UI updates with React hooks  
- Clean and user-friendly interface  

## Getting Started

### Prerequisites

- Node.js and npm installed  
- Basic knowledge of React and JavaScript  

### Installation

1. Clone the repository:

git clone https://github.com/yourusername/react-shopping-cart.git

text

2. Navigate to the project directory:

cd react-shopping-cart

text

3. Install dependencies:

npm install

text

4. Start the development server:

npm start

text

5. Open your browser and visit `http://localhost:3000` to use the app.

## Usage

- Browse available products and click "Add to Cart" to include items.  
- Adjust quantities or remove items directly from the cart.  
- The total price updates automatically based on cart contents.

## Example Code Snippet

// Calculate total price using reduce
const totalPrice = cartItems.reduce((total, item) => total + item.price * item.quantity, 0);

// Remove item using filter
const removeItem = (id) => {
setCartItems(cartItems.filter(item => item.id !== id));
};

// Update quantity using map
const updateQuantity = (id, quantity) => {
setCartItems(cartItems.map(item =>
item.id === id ? { ...item, quantity } : item
));
};

text

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to enhance features or fix bugs.

## License

This project is licensed under the MIT License.

---

Developed by Ismail Cisse 
Building dynamic, user-friendly shopping experiences with React and modern JavaScript.
If you want, I can help you add payment integration or persistent cart storage features!
