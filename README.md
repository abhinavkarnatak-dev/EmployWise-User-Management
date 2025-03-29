# User Management System

A React application for user management, built with React, TypeScript, and Tailwind CSS. This project demonstrates authentication, user listing, searching, and CRUD operations using the ReqRes API.

## 🚀 Live Demo

Check out the live application here:  
🔗 [https://employwise-usermanagement.vercel.app](https://employwise-usermanagement.vercel.app)

## Features

- 🔐 User Authentication
- 👥 User Management (Create, Read, Update, Delete)
- 🔍 Real-time Global Search
- 📱 Responsive Design
- 📄 Pagination
- 🎨 Modern UI with Tailwind CSS
- 🚀 TypeScript Support
- ⚡ Built with Vite

## Prerequisites

- Node.js (v18 or higher)
- npm (v9 or higher)

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/abhinavkarnatak-dev/EmployWise-User-Management.git
cd EmployWise-User-Management
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

## Build for Production

To create a production build:

```bash
npm run build
```

The built files will be in the `dist` directory.

## Project Structure

```
src/
├── components/        # Reusable components
├── pages/            # Page components
├── services/         # API services
├── types/            # TypeScript types
└── main.tsx         # Application entry point
```

## Authentication

The application uses the ReqRes API for authentication. Use the following credentials to log in:

- Email: eve.holt@reqres.in
- Password: cityslicka

## API Integration

This project integrates with the ReqRes API (https://reqres.in/) for all operations:

- Authentication: POST /api/login
- User List: GET /api/users
- Update User: PUT /api/users/{id}
- Delete User: DELETE /api/users/{id}

## Features in Detail

### Authentication
- Secure login system
- Token-based authentication
- Protected routes

### User Management
- View all users in a paginated list
- Edit user details in a modal overlay
- Delete users
- Global search across all users
- Responsive card layout for user information

### UI/UX Features
- Toast notifications for feedback
- Loading states
- Error handling
- Responsive design for mobile and desktop
- Modern and clean interface

## Technologies Used

- React 18
- TypeScript
- Tailwind CSS
- React Router DOM
- Axios
- React Hot Toast
- Lucide React (for icons)
- Vite (for build tooling)


## Development Considerations

- The application uses local storage for token management
- All API calls are centralized in the api service
- Protected routes redirect to login if no token is present
- Global search fetches all users for better search experience
- Real-time UI updates after CRUD operations

## Error Handling

The application includes comprehensive error handling:
- API error handling with user-friendly messages
- Form validation
- Authentication error handling
- Network error handling