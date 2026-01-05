# 🛍️ MERN Ecommerce

> **A premium shopping experience powered by the MERN stack, Redux Toolkit, and Material UI**

[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Redux](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)](https://redux-toolkit.js.org/)
[![Material UI](https://img.shields.io/badge/Material_UI-0081CB?style=for-the-badge&logo=material-ui&logoColor=white)](https://mui.com/)


## 🚀 Features

### 👤 For Users

| Feature | Description |
|---------|-------------|
| 💬 **Product Reviews** | Write, edit, and delete reviews with real-time rating updates |
| ❤️ **Wishlist** | Add products with personalized notes for future purchase |
| 📦 **Order Management** | Create orders and access comprehensive order history |
| 👤 **Profile Dashboard** | Manage personal details including multiple delivery addresses |
| 🛒 **Shopping Cart** | Add products, modify quantities, view itemized subtotals |

### 👑 For Admins

| Feature | Description |
|---------|-------------|
| 📝 **Product Management** | Full CRUD operations with soft-delete functionality |
| 📊 **Inventory Control** | Manage stock levels and product attributes |
| 📋 **Order Processing** | View and update order status through an intuitive dashboard |

### 🛡️ Security & Experience

- **Authentication Suite**: Login, signup, OTP verification, password reset
- **Material UI**: Sleek, responsive interface with intuitive user flows
- **Scalable Architecture**: Built for growth and increasing user demand

## 🛠️ Project Setup

### Prerequisites

- Node.js (v21.1.0+)
- MongoDB (installed and running)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/abhishekgurjarin/ecommerce.git
   cd mern-ecommerce
   ```

2. **Install dependencies** (Pro tip: Use split terminals for efficiency)
   ```bash
   # For frontend
   cd frontend
   npm install
   
   # For backend
   cd backend
   npm install
   ```

### ⚙️ Environment Configuration

#### Backend (.env file in backend directory)
```
# Database connection
MONGO_URI="mongodb://localhost:27017/ecommerce"

# Frontend URL
ORIGIN="http://localhost:3000"

# Email configuration for notifications
EMAIL="your-email@example.com"
PASSWORD="your-email-password"

# Security settings
LOGIN_TOKEN_EXPIRATION="30d"
OTP_EXPIRATION_TIME="120000"
PASSWORD_RESET_TOKEN_EXPIRATION="2m"
COOKIE_EXPIRATION_DAYS="30"
SECRET_KEY="your-strong-secret-key"

# Environment
PRODUCTION="false"
```

#### Frontend (.env file in frontend directory)
```
REACT_APP_BASE_URL="http://localhost:8000"
```

> ⚠️ **Important**: Replace placeholders with actual values and never commit .env files to version control

### 🌱 Data Seeding

Jumpstart your development with sample data:

```bash
cd backend
npm run seed
```

This populates your database with users, products, reviews, and carts for immediate testing.

### 🏃‍♂️ Development Servers

**Start backend**:
```bash
cd backend
npm run dev  # requires nodemon, or use npm start
```

**Start frontend**:
```bash
cd frontend
npm start
```

Access your application at:
- Frontend: http://localhost:3000
- Backend API: http://localhost:8000

## 📷 Project Showcase
![Ecommerce Homepage](https://github.com/user-attachments/assets/c4d1b28a-caf0-43f9-849f-251f1661b2e1)
![Ecommerce Banner](https://github.com/user-attachments/assets/d6b9a9c7-fd1b-4bd4-802b-64e143ba4e73)



> **Note**: The demo account uses a non-functional email address. For testing password reset and OTP verification features, create an account with a valid email.

## 🧪 Testing

```bash
# Run backend tests
cd backend
npm test

# Run frontend tests
cd frontend
npm test
```

## 📋 Future Roadmap

- Payment gateway integration
- Advanced search and filtering
- Admin analytics dashboard
- Mobile app development

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add some amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a pull request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📬 Contact

- **GitHub**: [@abhishekgurjarin](https://github.com/abhishekgurjarin)
- **Project Link**: [https://github.com/abhishekboadgurjar/Ecommerce](https://github.com/abhishekgurjarin/Ecommerce)
---

⭐ **Don't forget to star this repository if you found it useful!** ⭐
