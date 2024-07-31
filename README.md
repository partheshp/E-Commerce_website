# E-commerce Website

This project is a fully functional E-commerce website. It includes features such as user authentication, product browsing, shopping cart, checkout, and order management.

## Features

- User authentication (registration, login, logout)
- Browse products by category
- Search products
- View product details
- Add products to cart
- Update cart items
- Checkout process
- Order management for users
- Admin panel for managing products, categories, and orders

## Technologies

- Frontend: HTML, CSS, JavaScript, React
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT (JSON Web Tokens)
- Hosting: Heroku / AWS / Other

## Setup

To set up this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/partheshp/E-commerce_website.git
    cd E-commerce_website
    ```

2. **Install dependencies**:
    ```bash
    npm install
    cd client
    npm install
    cd ..
    ```

3. **Set up environment variables**:
    Create a `.env` file in the root directory and add the following variables:
    ```env
    NODE_ENV=development
    PORT=5000
    MONGO_URI=your_mongo_db_connection_string
    JWT_SECRET=your_jwt_secret
    ```

4. **Run the development server**:
    ```bash
    npm run dev
    ```

The frontend React app will run on `http://localhost:3000` and the backend server will run on `http://localhost:5000`.

## Usage

1. **Register an account** or **login** with an existing account.
2. **Browse products** by category or use the search feature.
3. **Add products to the cart** and **manage your cart**.
4. **Proceed to checkout** and place your order.
5. **Admin users** can manage products, categories, and orders through the admin panel.


