# WebChat Application Using MERN-Stack.


## Project Overview

_A real-time **Chat application** built using the MERN stack (MongoDB, Express, React, Node.js) and styled with Tailwind CSS. It supports user authentication, group chats, and instant messaging with real-time updates via Socket.IO. The application is fully responsive and provides smooth communication with features like notifications and state management using Redux._

## Technologies & Packages Used

-   **MongoDB**: NoSQL database for flexible and scalable data storage.
-   **Express.js**: Web application framework for Node.js, providing robust features for web and mobile applications.
-   **Node.js**: JavaScript runtime for server-side development.
-   **React.js**: A JavaScript library for building reusable UI components and efficient single-page application views.
-   **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
-   **Socket.IO**: Enables real-time, bidirectional and event-based communication.
-   **JWT (JSON Web Tokens)**: Securely transmits information between parties as a JSON object.
-   **Redux**: A Predictable State Container for JavaScript Apps.
-   **React-Toastify**: A JavaScript library for providing toast notifications in React.

## Key Features

-   **User Authentication:** SignIn, SignUp, and Logout functionality.
-   **Real-time Chat:** Users can send and receive messages in real-time.
-   **Group Chat:** Create and participate in group chats.
-   **Message Notifications:** Get notified of new messages with sound and visual alerts.
-   **State Management:** Manage application state efficiently using Redux.
-   **Responsive Design:** Tailwind CSS for a responsive and modern user interface.


## How to Install

Follow these steps to set up and run the project locally:

1.  **Clone the Repository:**

    ```bash
    git clone https://github.com/Aniket52kr/WebChat-App.git
    cd WebChat-App
    ```

2.  **Install Dependencies:**
    Frontend Folder :

    ```bash
    cd frontend
    npm install
    ```

    Backend Folder :

    ```bash
    cd backend
    npm install
    ```

3.  **Set Up Environment Variables:**

    Configure the following environment variables by creating a .env file in the root of Forntend and Backend Folder:

    Frontend Folder :

    ```bash
    VITE_BACKEND_URL=
    ```

    Backend Folder :

    ```bash
    FRONTEND_URL=
    MONGODB_URI=
    PORT=
    JWT_SECRET=
    ```

    Replace the values with your specific configurations.

4.  **Run the Application:**

    Frontend Folder :

    ```bash
    npm run dev
    ```

    Backend Folder :

    ```bash
    nodemon server.js
    ```

5.  **Open in Your Browser:**

Open `http://localhost:5173` in your web browser.



## Project ScreenShot