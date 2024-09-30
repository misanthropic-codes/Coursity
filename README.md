# Coursity
Here’s a sample `README.md` file for your course-selling app project. This file will explain how to set up the project, what technologies are used, and how to run the app locally.

```markdown
# Course Selling App Backend

This is the backend code for a course-selling platform built using **Node.js**, **Express**, and **MongoDB**. The app provides an API for managing users, admins, and courses. It is designed to be the backend of a full-fledged course-selling platform.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [License](#license)

## Technologies Used
- **Node.js**: JavaScript runtime for server-side programming.
- **Express**: Web framework for Node.js.
- **MongoDB**: NoSQL database for storing users, courses, and admin data.
- **Mongoose**: Object Data Modeling (ODM) library for MongoDB and Node.js.
- **dotenv**: For loading environment variables from a `.env` file.

## Getting Started

Follow these instructions to set up and run the backend locally on your machine.

### Prerequisites
Make sure you have the following installed on your machine:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [Git](https://git-scm.com/)

### Environment Variables
Create a `.env` file in the root directory of the project to store your environment variables.

```bash
touch .env
```

In the `.env` file, you should define the following variables:

```bash
MONGO_URL=your_mongodb_connection_string
```

Replace `your_mongodb_connection_string` with your actual MongoDB URI.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/misanthropic-codes/Coursity.git
   cd your-repo-name
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**:
   - Create a `.env` file in the project root and add your MongoDB connection string.

4. **Run MongoDB**:
   Make sure MongoDB is running on your local machine or via an online service like MongoDB Atlas.

## Usage

To start the backend server, use the following command:

```bash
npm start
```

By default, the server will start on port `3000`.

You should see:
```
listening on port 3000
```

### Available Scripts

- **`npm start`**: Runs the app in production mode.
- **`npm run dev`**: Runs the app in development mode with nodemon.

## API Endpoints

### User Routes (`/api/v1/user`)
- **GET** `/api/v1/user`: Get all users.
- **POST** `/api/v1/user`: Register a new user.

### Admin Routes (`/api/v1/admin`)
- **GET** `/api/v1/admin`: Get all admin information.
- **POST** `/api/v1/admin`: Register a new admin.

### Course Routes (`/api/v1/course`)
- **GET** `/api/v1/course`: Get all courses.
- **POST** `/api/v1/course`: Add a new course.




