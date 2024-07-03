# prouction_nodejs_ecommerce_app
 
The **E-Commerce App** is a Node.js-based platform developed using the Express.js framework, with MongoDB as the chosen database. This application manages information related to products and user orders. It exposes specific endpoints to handle CRUD (Create, Read, Update, Delete) operations for both products and orders, ensuring a seamless shopping experience for users.

## Endpoints

### User
- **Register User:**
  - Endpoint: `POST /api/v1/user/register`
  - Description: Adds a user to the system with details such as name, email, etc.

- **Login User:**
  - Endpoint: `POST /api/v1/user/rlogin`
  - Description: Retrieves a user from the system.

- **Get User Profile:**
  - Endpoint: `GET /api/v1/user/profile`
  - Description: Retrieves a list of all users in the system.

- **Logout User:**
  - Endpoint: `GET /api/v1/user/logout`
  - Description: Terminates current user session.

- **Update Profile:**
  - Endpoint: `PUT /api/v1/user/profile-update`
  - Description: Updates a user's profile from the system based on their ID.

- **Update Password:**
  - Endpoint: `PUT /api/v1/user/update-password`
  - Description: Updates a user's profile password from the system based on their ID.

- **Update Profile Pic:**
  - Endpoint: `PUT /api/v1/user/update-picture`
  - Description: Updates a user's profile picture from the system based on their ID.

- **Forgot Password:**
  - Endpoint: `POST /api/v1/user/reset-password`
  - Description: Resets current password of user to new one.

### Product
- **Get All Products:**
  - Endpoint: `GET /api/v1/product/get-all`
  - Description: Retrieves a list of all product items from the system with details such as name, rating, etc.

- **Get Top Products:**
  - Endpoint: `GET /api/v1/product/top`
  - Description: Retrieves a list of top product items from the system.

- **Get Single Product:**
  - Endpoint: `GET /api/v1/product/:id`
  - Description: Retrieves a single product item from the system.

- **Create Product:**
  - Endpoint: `POST /api/v1/product/create`
  - Description: Adds a new product item in the system.

- **Update Product:**
  - Endpoint: `PUT /api/v1/product/:id`
  - Description: Updates an existing product item from the system based on its ID.

- **Update Product Image:**
  - Endpoint: `PUT /api/v1/product/image/:id`
  - Description: Updates an existing product's image from the system based on its ID.

- **Delete Product Image:**
  - Endpoint: `DELETE /api/v1/product/delete-image/:id`
  - Description: Removes an existing product's image from the system based on its ID.

- **Delete Product:**
  - Endpoint: `DELETE /api/v1/product/delete/:id`
  - Description: Removes an existing product item's from the system based on its ID.

- **Review Product:**
  - Endpoint: `PUT /api/v1/product/:id/review`
  - Description: Review an existing product item's from the system based on its ID.

### Order
- **Create Orders:**
  - Endpoint: `POST /api/v1/order/create`
  - Description: Adds users order in the system to buy products.

- **Get All Orders:**
  - Endpoint: `GET /api/v1/order/my-orders`
  - Description: Retrieves all orders from the system.

- **Get Single Order Details:**
  - Endpoint: `GET /api/v1/order/my-orders/:id`
  - Description: Retrieves single order from the system.

- *Accept Payments:**
  - Endpoint: `POST /api/v1/order/payments`
  - Description: Accepts order payments from users.

- **Get All Orders (Admin):**
  - Endpoint: `GET /api/v1/order/admin/get-all-orders`
  - Description: Retrieves all order details (by admin).

- **Change Order Status (Admin):**
  - Endpoint: `PUT /api/v1/order/admin/order/:id`
  - Description: Changes order status based on it's delivery to user.

### Category
- **Create Category:**
  - Endpoint: `POST /api/v1/cat/create`
  - Description: Adds a new category in the system.

- **Get All Category:**
  - Endpoint: `GET /api/v1/cat/get-all`
  - Description: Retrieves all categories from the system.

- **Delete Category:**
  - Endpoint: `DELETE /api/v1/cat/delete/:id`
  - Description: Deletes a particular category from the system.

- **Update Category:**
  - Endpoint: `PUT /api/v1/cat/update/:id`
  - Description: Updates a particular category from the system.

### Test
- **Test Category:**
  - Endpoint: `GET /api/v1`
  - Description: Used to test any particular existing category from the system.

## Data Models

### User
The `User` data model represents information about clients of e-commerce app.

### Product
The `Product` data model represents information about products available in app.

### Category
The `Category` data model represents product's category from the system.

### Order
The `Order` data model represent orders placed by users from the system.

## Usage

1. **Install Dependencies:**
   ```bash
   npm install
   and others all



