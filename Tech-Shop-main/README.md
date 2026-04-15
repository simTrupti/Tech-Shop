#  Tech Shop Backend (MERN)

A backend-driven e-commerce system built using the MERN stack (MongoDB, Express, Node.js) with additional integrations like AI APIs and payment gateways.



##  Features

###  User Functionality

* User authentication (JWT-based)
* User profile management
* Order history tracking
* Wishlist management (Add / Remove products)
* Address management (Add / Edit / Delete)



###  Product & Order Management

* Product listing with search & pagination
* Product reviews and ratings (Add / Edit / Delete)
* Shopping cart & checkout flow
* Order creation and tracking



###  Admin Features

* Product management (Create / Update / Delete)
* User management (Update roles / Delete users)
* Order management (View details, mark as delivered)



###  Integrations

* PayPal / Credit Card payment integration
* AI chatbot integration (Gemini & Groq APIs)



###  Backend Highlights

* RESTful API design
* Layered architecture (Routes → Controllers → Models)
* MongoDB for data persistence
* API testing using Postman



##  Tech Stack

* Node.js
* Express.js
* MongoDB
* JWT Authentication
* REST APIs
* Postman



##  Setup & Installation

### 1. Clone the repository

```
git clone https://github.com/YOUR_USERNAME/REPO_NAME.git
cd REPO_NAME
```

---

### 2. Install dependencies

```
npm install
```

---

### 3. Configure environment variables

Create a `.env` file in root:

```
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret
PAYPAL_CLIENT_ID=your_paypal_id
API_KEY=your_gemini_key
GROQ_API_KEY=your_groq_key
```

---

### 4. Run the backend

```
npm run server
```

---

##  Database Seeder

```
# Import sample data
npm run data:import

# Destroy data
npm run data:destroy
```

---

##  API Testing

* All APIs tested using Postman
* Includes endpoints for users, products, orders, and authentication





