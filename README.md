# Location App Backend

Backend API for the location-based mobile application built with Node.js, featuring PostgreSQL with PostGIS extension and real-time location services.

## 🚀 Technology Stack

- **Runtime**: Node.js
- **Framework**: Express.js/NestJS
- **Database**: PostgreSQL with PostGIS extension
- **Authentication**: JWT-based authentication
- **Real-time**: WebSocket support
- **File Upload**: Multer for file handling
- **Logging**: Comprehensive logging system

## 🏗️ Project Structure

```
backend/
├── src/
│   ├── config/          # Configuration files
│   ├── controllers/     # Route controllers
│   ├── middleware/      # Custom middleware
│   ├── models/          # Database models
│   ├── routes/          # API routes
│   ├── services/        # Business logic
│   └── utils/           # Utility functions
├── tests/
│   ├── integration/     # Integration tests
│   └── unit/           # Unit tests
├── logs/               # Application logs
└── uploads/            # File uploads directory
```

## 🔧 Features

- RESTful API endpoints
- PostgreSQL database with spatial data support
- Authentication and authorization
- Real-time communication capabilities
- File upload handling
- Comprehensive logging
- Error handling middleware
- Input validation
- API documentation

## 🛠️ Development Setup

### Prerequisites

- Node.js (v16 or higher)
- PostgreSQL with PostGIS extension
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/pranjal255/location-app-backend.git
cd location-app-backend
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
```bash
cp .env.example .env
# Edit .env with your configuration
```

4. Set up database
```bash
npm run db:migrate
npm run db:seed
```

5. Start development server
```bash
npm run dev
```

## 📚 API Documentation

API documentation is available at `/api/docs` when running the development server.

## 🧪 Testing

```bash
# Run unit tests
npm run test

# Run integration tests
npm run test:integration

# Run tests with coverage
npm run test:coverage
```

## 🚀 Deployment

```bash
# Build for production
npm run build

# Start production server
npm start
```

## 📄 License

This project is licensed under the MIT License.

## 🔗 Related Repositories

- [Mobile App](https://github.com/pranjal255/location-app-mobile) - React Native mobile application
