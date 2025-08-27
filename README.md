# QuickCash: A Full-Stack Peer-to-Peer Payments Application

A secure and robust full-stack web application that simulates a peer-to-peer (P2P) payment system, allowing users to create accounts, manage their wallets, and transfer funds to other users instantly.


---

## 🚀 Overview

This project is a complete MERN-stack implementation of a digital wallet application. It provides a seamless user experience for signing up, logging in, checking account balances, and performing secure transactions. The primary focus was on ensuring **transactional integrity** and **data security**, which are paramount in any financial application.

<img width="1919" height="523" alt="image" src="https://github.com/user-attachments/assets/c40222dd-fcf0-4b2b-952c-267745b18faf" />




---

## ✨ Key Features

-   **Secure User Authentication**: Robust user sign-up and sign-in functionality with password hashing using `bcrypt` and session management via JSON Web Tokens (JWT).
-   **Account Management**: Users get a dedicated wallet upon registration with a randomly assigned starting balance.
-   **Real-time User Search**: Instantly find and filter other users on the platform to initiate a transfer.
-   **ACID-Compliant Transactions**: Core fund transfer logic is built using Mongoose sessions to ensure atomic, consistent, isolated, and durable (ACID) transactions, preventing data corruption and loss of funds.
-   **Dynamic & Responsive UI**: A clean, modern, and intuitive user interface built with React and styled with Tailwind CSS for a seamless experience on all devices.
-   **RESTful API**: A well-structured and documented backend API to handle all application logic.

---

## 🛠️ Tech Stack

| Category      | Technology                                                                                             |
| ------------- | ------------------------------------------------------------------------------------------------------ |
| **Frontend** | React.js, React Router, Axios, Tailwind CSS                                                            |
| **Backend** | Node.js, Express.js                                                                                    |
| **Database** | MongoDB, Mongoose                                                                                      |
| **Security** | JSON Web Tokens (JWT), bcrypt                                                                          |
| **Validation**| Zod                                                                                                    |

---

## ⚙️ Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

-   Node.js and npm (or yarn) installed
-   MongoDB installed and running, or a MongoDB Atlas connection string

### Installation & Setup

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    cd your-repo-name
    ```

2.  **Backend Setup:**
    ```sh
    # Navigate to the backend directory
    cd backend

    # Install NPM packages
    npm install

    # Create a .env file in the /backend directory and add the following variables
    # MONGO_URL=your_mongodb_connection_string
    # JWT_SECRET=your_jwt_secret_key
    # PORT=3000

    # Start the backend server
    npm start
    ```

3.  **Frontend Setup:**
    ```sh
    # Navigate to the frontend directory from the root
    cd frontend

    # Install NPM packages
    npm install

    # Create a .env file in the /frontend directory and add the following variable
    # VITE_SERVER_URL=http://localhost:3000

    # Start the frontend development server
    npm run dev
    ```
The application should now be running on `http://localhost:5173` (or another port specified by Vite).

---


## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
