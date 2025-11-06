# 📧 Node.js Contact Form Webpage

[![GitHub Language Count](https://img.shields.io/github/languages/count/Fabio-Menjivar/nodejs-contact-form-webpage)](https://github.com/Fabio-Menjivar/nodejs-contact-form-webpage)
[![GitHub Top Language](https://img.shields.io/github/languages/top/Fabio-Menjivar/nodejs-contact-form-webpage)](https://github.com/Fabio-Menjivar/nodejs-contact-form-webpage)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/Fabio-Menjivar/nodejs-contact-form-webpage)](https://github.com/Fabio-Menjivar/nodejs-contact-form-webpage/commits)

This project provides a **robust server-side solution** for a contact form on a webpage. Built with **Node.js and Express**, it securely handles user submissions and manages the process of sending form data via email, making it a reliable backend for connecting with your audience.

---

## 🚀 Features

* **Server-Side Processing:** Securely handles form data submissions using a dedicated backend server.
* **Email Integration:** Uses a Node.js library (like Nodemailer) to send submitted messages to a specified email address.
* **Input Validation:** Ensures data integrity by validating user inputs before processing.
* **Simple Web Interface:** Includes a basic HTML/CSS frontend for the contact form itself.
* **Environment Variables:** Uses `.env` files to manage sensitive credentials (like email passwords/API keys).

---

## 💻 Technologies Used

| Category | Technology | Purpose |
| :--- | :--- | :--- |
| **Backend** | **Node.js** | The runtime environment for the server-side application. |
| **Framework** | **Express.js** | Provides routing and middleware for handling HTTP requests (form submissions). |
| **Email Service** | **Nodemailer** (Likely) | Library used to facilitate email sending via SMTP or other services. |
| **Configuration** | **Dotenv (`.env`)** | Manages environment variables for configuration flexibility and security. |
| **Frontend** | **HTML & CSS** | Defines the structure and style of the contact form interface. |

---

## ⚙️ Installation and Setup

Follow these steps to get the contact form running locally and connected to your email service.

### Prerequisites

* **Node.js** (LTS version recommended)
* A **code editor** (e.g., VS Code)
* An **email service account** (e.g., Gmail, SendGrid, etc.) and its relevant SMTP credentials.

### Detailed Steps

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/Fabio-Menjivar/nodejs-contact-form-webpage.git](https://github.com/Fabio-Menjivar/nodejs-contact-form-webpage.git)
    cd nodejs-contact-form-webpage
    ```

2.  **Install Dependencies:**
    ```bash
    npm install
    npm i -D nodemon
    npm run dev    
    ```

3.  **Configure Environment Variables:**
    * Create a file named **`.env`** in the root directory of the project.
    * Add your email service credentials to this file (structure may vary based on the specific email library, but typically includes):

        ```env
        # Example for Gmail or similar SMTP
        EMAIL_USER=your_email@example.com
        EMAIL_PASS=your_app_password
        ```
    > **Note:** For services like Gmail, you may need to generate an **"App Password"** instead of using your main account password.

4.  **Start the Server:**
    ```bash
    npm start
    ```
    The application should now be running, point your browser to `http://localhost:3000`.
