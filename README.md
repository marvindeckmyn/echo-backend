# Echo Backend

REST API backend for Echo social media platform. Handles data persistence, authentication, and business logic.

## 🚀 Features

- **RESTful API**: Full CRUD operations for posts and users
- **Authentication**: JWT-based authentication
- **Data Validation**: Input validation and sanitization
- **Real-time Features**: WebSocket support for live updates

## 💻 Tech Stack

- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: PostgreSQL with Prisma ORM
- **Authentication**: JSON Web Tokens (JWT)
- **WebSocket**: Socket.io for real-time features

## 🛠 Installation

1. Clone the repository:
```bash
git clone https://github.com/marvindeckmyn/echo-backend.git
cd echo-backend
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
```env
DATABASE_URL="postgresql://user:password@localhost:5432/echo"
JWT_SECRET=your_jwt_secret
PORT=8000
```

4. Run database migrations:
```bash
npx prisma migrate dev
```

5. Start the server:
```bash
npm run dev
```

## 📁 Project Structure

```
src/
├── controllers/   # Request handlers
├── models/       # Prisma models and types
├── routes/       # API route definitions
├── middleware/   # Custom middleware
└── utils/        # Helper functions
```

## 🔗 Related Projects

- [Echo Frontend](https://github.com/marvindeckmyn/echo-frontend) - Next.js frontend application

## 👤 Author

Marvin Deckmyn
- GitHub: [@marvindeckmyn](https://github.com/marvindeckmyn)
