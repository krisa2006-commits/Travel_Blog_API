# Travel Blog REST API

A RESTful backend API built with **Node.js, Express.js, MongoDB, and Mongoose** for managing travel blog records.

The application implements complete **CRUD operations** and follows a clean **MVC architecture**.

---

## Overview

The Travel Blog REST API allows users to manage travel blog records through RESTful API endpoints.

### Main Operations

- Add a new travel blog
- Get all travel blogs
- Get a travel blog by ID
- Update travel blog details
- Delete a travel blog

All travel blog data is stored in **MongoDB** and managed using **Mongoose**.

---

## Features

- RESTful API architecture
- Complete CRUD operations
- MongoDB integration
- Mongoose schema and validation
- MVC architecture
- Error handling middleware
- Request validation middleware
- Environment variable configuration
- JSON request and response handling
- Postman API testing

---

## Tech Stack

| Technology | Purpose                       |
| ---------- | ----------------------------- |
| Node.js    | JavaScript runtime            |
| Express.js | Backend framework             |
| MongoDB    | Database                      |
| Mongoose   | MongoDB ODM                   |
| Dotenv     | Environment variables         |
| CORS       | Cross-Origin Resource Sharing |
| Postman    | API testing                   |

---

## Project Structure

```text
Travel_Blog_API/
│
├── src/
│   │
│   ├── config/
│   │   └── database.js
│   │
│   ├── controllers/
│   │   └── blogController.js
│   │
│   ├── models/
│   │   └── blogModel.js
│   │
│   ├── routes/
│   │   └── blogRoutes.js
│   │
│   ├── middleware/
│   │   ├── errorMiddleware.js
│   │   └── validationMiddleware.js
│   │
│   └── server.js
│
├── .env
├── .env.example
├── .gitignore
├── package.json
├── package-lock.json
└── README.md
```

---

# Project Explanation Video

**Explanation Video**
**Link** [https://drive.google.com/file/d/1Y2aIPb2jHBrTO_TwE1Ejl9mFc4frb78S/view?usp=sharing]

---

**Thank you.**
