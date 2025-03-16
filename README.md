# MERN Stack E-commerce Platform

A full-featured e-commerce platform built with the MERN (MongoDB, Express.js, React.js, Node.js) stack. This application provides a complete solution for online shopping with both user and seller interfaces.

## 🌟 Features

### For Customers
- User authentication and authorization
- Product browsing and searching
- Shopping cart management
- Wishlist functionality
- Order tracking
- Secure payment processing
- Real-time chat with sellers
- Event/sale participation
- Profile management

### For Sellers
- Seller dashboard
- Product management (CRUD operations)
- Order management
- Event creation and management
- Coupon code generation
- Sales analytics
- Inventory management
- Withdrawal system
- Customer message handling

### For Admin
- Complete admin dashboard
- User management
- Seller verification
- Product oversight
- Order monitoring
- Withdrawal request processing
- System-wide analytics

## 🚀 Technology Stack

### Frontend
- React.js
- Redux for state management
- Tailwind CSS for styling
- Socket.io-client for real-time features

### Backend
- Node.js
- Express.js
- MongoDB
- Socket.io for real-time communication
- JWT for authentication

### DevOps
- Docker
- Docker Compose

## 📦 Installation and Setup

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- Docker (optional)

### Using Docker (Recommended)
1. Clone the repository:
```bash
git clone https://github.com/shahmeer3456/Ecommerce-MERN.git
cd Ecommerce-MERN
```

2. Start the application using Docker Compose:
```bash
docker-compose up
```

3. Access the application:
- Frontend: http://localhost:3000
- Backend API: http://localhost:8000
- Socket Server: http://localhost:4000

### Manual Setup

1. Clone the repository:
```bash
git clone https://github.com/shahmeer3456/Ecommerce-MERN.git
cd Ecommerce-MERN
```

2. Install dependencies for backend:
```bash
cd backend
npm install
```

3. Install dependencies for frontend:
```bash
cd frontend
npm install
```

4. Install dependencies for socket server:
```bash
cd socket
npm install
```

5. Set up environment variables:
- Create `.env` files in backend and socket directories
- Add necessary environment variables (refer to `.env.example` files)

6. Start the development servers:

Backend:
```bash
cd backend
npm run dev
```

Frontend:
```bash
cd frontend
npm start
```

Socket Server:
```bash
cd socket
npm start
```

## 🔧 Environment Variables

### Backend (.env)
```
PORT=8000
DB_URL=your_mongodb_url
JWT_SECRET=your_jwt_secret
JWT_EXPIRES=7d
ACTIVATION_SECRET=your_activation_secret
SMTP_HOST=your_smtp_host
SMTP_PORT=your_smtp_port
SMTP_MAIL=your_smtp_mail
SMTP_PASSWORD=your_smtp_password
```

### Socket Server (.env)
```
PORT=4000
```

## 📱 Application Structure

```
├── backend/             # Backend server
│   ├── controller/     # Route controllers
│   ├── middleware/     # Custom middleware
│   ├── model/         # Database models
│   ├── routes/        # API routes
│   └── utils/         # Utility functions
├── frontend/           # React frontend
│   ├── public/        # Static files
│   └── src/           # Source files
│       ├── components/# React components
│       ├── pages/     # Page components
│       ├── redux/     # Redux state management
│       └── routes/    # Route configurations
└── socket/            # Socket.io server
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Shahmeer Hussain**
- GitHub: [@shahmeer3456](https://github.com/shahmeer3456)
- Email: hussainshahmeer87@gmail.com

## 🙏 Acknowledgments

- Thanks to all contributors who have helped this project grow
- Special thanks to the MERN stack community for their excellent documentation
- Icons and animations provided by various open-source projects
