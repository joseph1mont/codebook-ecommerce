# Codebook - E-Commerce React Application

### Live Demo:

[Codebook Demo](https://codebook-sample-reactjs.netlify.app/)

## Overview:

Codebook is a full-fledged e-commerce web application built using **React**, **Tailwind CSS**, **Context API**, **JSON Server**, **JWT Authentication**, and deployed on **Netlify** and **Render**. This project simulates a real-world e-commerce platform with features like search functionality, order history, authentication (registration and login), and theme switching.

### Key Features:

- **JWT Authentication**: Secure login and registration using JSON Server Auth.
- **Search Functionality**: Search products by name with partial matching.
- **Order History**: Users can view past orders, providing a complete shopping experience.
- **Theme Controller**: Supports light/dark mode switching.
- **Fully Responsive**: Optimized for all screen sizes using Tailwind CSS.
- **Modular Structure**: Clean and maintainable code following best practices.

---

## Backend:

The backend for this project is maintained in a separate repository: [Codebook Node Backend](https://github.com/yourusername/codebook-node-backend).

It handles the mock API using **JSON Server** and provides authentication with **JSON Server Auth**. For local testing, the backend server can be run separately.

---

## Local Development Setup:

To test the application locally, you'll need to run both the frontend and the mock backend.

### JSON Server (Backend) Setup:

You can either clone the backend repository or run the JSON Server locally as follows.

1. **Run JSON Server with Auth** (Port 8000):

   Open a new terminal and run the following command to start the JSON server with authentication:

   ```bash
   npx json-server data/db.json -m ./node_modules/json-server-auth --port 8000
   ```

### Screenshot:

![Codebook](src/assets/images/sc.jpg "Codebook-courses store")
