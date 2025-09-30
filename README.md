# eCommerce App

A comprehensive online store application built with modern full-stack technologies, offering a complete shopping experience from product browsing to secure checkout.

## Overview

This full-featured eCommerce platform allows users to browse products, manage shopping carts, place orders, and process payments securely. The application includes an admin panel for product and order management, making it a complete end-to-end solution for online retail.

## Key Features

- **Product Catalog**: Browse products with filtering, sorting, and search functionality
- **Product Reviews & Ratings**: Customer reviews and star ratings for products
- **Shopping Cart**: Add, update, and remove items with real-time total calculation
- **User Authentication**: Secure registration, login, and profile management
- **Checkout Process**: Multi-step checkout with shipping and payment information
- **Payment Integration**: Stripe integration for secure payment processing
- **Order Management**: Track order history and status
- **Admin Dashboard**: Full CRUD operations for products, users, and orders
- **Responsive Design**: Mobile-friendly interface with modern UI/UX
- **Image Upload**: Product image management with cloud storage

## Technologies Used

### Frontend
- **React**: Component-based UI development
- **Redux**: Global state management for cart and user data
- **React Router**: Client-side routing and navigation
- **Axios**: API communication
- **Bootstrap/Material-UI**: Responsive styling and components

### Backend
- **Node.js**: Server-side JavaScript runtime
- **Express**: Web application framework
- **MongoDB**: NoSQL database for flexible data storage
- **Mongoose**: ODM for MongoDB
- **JWT**: Secure authentication tokens
- **bcrypt**: Password encryption
- **Stripe API**: Payment processing integration

## Project Structure

```
ecommerce-app/
├── client/                # React frontend
│   ├── src/
│   │   ├── components/   # Reusable UI components
│   │   ├── pages/        # Page-level components
│   │   ├── redux/        # State management
│   │   ├── services/     # API service functions
│   │   └── utils/        # Helper utilities
│   └── public/
├── server/               # Node.js backend
│   ├── controllers/      # Business logic handlers
│   ├── models/           # Database schemas
│   ├── routes/           # API endpoints
│   ├── middleware/       # Auth and validation
│   ├── config/           # Configuration files
│   └── utils/            # Server utilities
└── docs/                 # Documentation
```

## My Contributions

- **Backend Architecture**: Led the design and implementation of RESTful API with comprehensive error handling
- **UI/UX Design**: Created intuitive shopping experience with modern design principles
- **Payment Integration**: Implemented Stripe payment gateway with secure transaction handling
- **Database Design**: Architected schemas for products, users, orders, and reviews with optimal relationships
- **Admin Panel**: Built complete admin dashboard with advanced filtering and management capabilities
- **State Management**: Implemented Redux for efficient cart and authentication state handling

## Installation & Setup

1. Clone the repository
2. Install dependencies for client and server
3. Configure environment variables (MongoDB URI, Stripe keys, JWT secret)
4. Set up MongoDB database
5. Run both frontend and backend development servers

## Features in Detail

### User Features
- Product search with multiple filters (category, price range, ratings)
- Detailed product pages with image gallery
- Shopping cart with quantity management
- Wishlist functionality
- Order tracking and history
- User profile management

### Admin Features
- Product management (create, update, delete)
- Order processing and status updates
- User management
- Sales analytics and reporting
- Inventory tracking

## Future Enhancements

- Multiple payment gateway options
- Real-time inventory updates
- Product recommendation engine
- Email notifications for orders
- Advanced analytics dashboard
- Multi-currency support
- Social media integration

---

*This project showcases expertise in full-stack development with focus on eCommerce solutions and secure payment processing.*
