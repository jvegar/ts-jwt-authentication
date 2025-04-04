# TypeScript JWT Authentication

A robust authentication system built with TypeScript, Express, and JWT (JSON Web Tokens). This project provides a secure way to handle user authentication in your applications.

## Features

- User authentication with JWT
- Express.js backend
- TypeScript for type safety
- MongoDB database integration
- Docker support for easy deployment
- Environment variable configuration
- CORS enabled

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- Docker (optional)

## Installation

1. Clone the repository:

```bash
git clone <your-repository-url>
cd ts-jwt-authentication
```

2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file in the root directory with the following variables:

```
JWT_SECRET=your_jwt_secret_key
MONGODB_URI=your_mongodb_connection_string
```

## Running the Application

### Development Mode

```bash
npm run dev
```

### Using Docker

```bash
docker-compose up
```

## Project Structure

```
├── app.ts              # Main application file
├── models/            # Database models
├── .env              # Environment variables
├── docker-compose.yml # Docker configuration
├── package.json      # Project dependencies
└── tsconfig.json     # TypeScript configuration
```

## API Endpoints

- `POST /auth/register` - Register a new user
- `POST /auth/login` - Login user and receive JWT token
- `GET /auth/verify` - Verify JWT token

## Technologies Used

- TypeScript
- Express.js
- JSON Web Tokens (JWT)
- MongoDB with Mongoose
- Docker
- CORS

## Security

- JWT-based authentication
- Environment variables for sensitive data
- CORS protection
- Secure password handling

## License

ISC

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
