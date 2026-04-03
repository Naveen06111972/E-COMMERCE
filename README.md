# E-COMMERCE
📋 Project Overview
Tech Stack:
•	Frontend: React.js with React Router
•	Backend: Node.js + Express.js
•	Database: MySQL
•	Payment: Stripe API
•	Authentication: JWT (JSON Web Tokens)
•	File Upload: Multer
•	State Management: React Context API
PROJECT STRUCTURE
ecommerce-platform/
├── backend/
│   ├── config/
│   │   └── db.js
│   ├── controllers/
│   │   ├── authController.js
│   │   ├── productController.js
│   │   ├── cartController.js
│   │   └── orderController.js
│   ├── middleware/
│   │   └── auth.js
│   ├── routes/
│   │   ├── auth.js
│   │   ├── products.js
│   │   ├── cart.js
│   │   └── orders.js
│   ├── uploads/
│   ├── .env
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Navbar.js
│   │   │   ├── ProductCard.js
│   │   │   ├── Cart.js
│   │   │   └── AdminPanel.js
│   │   ├── pages/
│   │   │   ├── Home.js
│   │   │   ├── ProductDetail.js
│   │   │   ├── Login.js
│   │   │   ├── Register.js
│   │   │   └── Checkout.js
│   │   ├── context/
│   │   │   └── AuthContext.js
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
