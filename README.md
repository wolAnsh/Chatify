# Real-Time Chat Website (MERN + Socket.io + Redux Toolkit + Tailwind CSS)

This is a **real-time chat website** built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js) along with **Socket.io**, **Redux Toolkit**, and **Tailwind CSS**. It enables users to chat in real-time, create groups, send emojis, and receive notifications.
---
## 🚀 Features

✅ **Real-Time Messaging:** Chat with others instantly using WebSockets.
✅ **User Authentication:** Sign up, log in, and log out securely with JWT & Google Auth.
✅ **Profile Management:** Update avatar and display name.
✅ **Search Functionality:** Find messages and users easily.
✅ **Responsive UI:** Optimized for different screen sizes.

---

## 🛠️ Technologies Used

- **MERN Stack**: MongoDB, Express.js, React.js, Node.js
- **Socket.io**: Real-time bidirectional event-based communication
- **Redux Toolkit**: Efficient state management
- **Tailwind CSS**: Modern, responsive UI styling
- **JWT & Google OAuth**: Secure authentication

---

## 🔧 Setup & Installation

### 1️⃣ Clone the Repository
```bash
git clone <repository-url>
cd Realtime-Chat
```

### 2️⃣ Install Dependencies
#### Client (Frontend)
```bash
cd client
npm install
```

#### Server (Backend)
```bash
cd server
npm install
```

### 3️⃣ Setup Environment Variables
#### Client (`client/.env`)
```env
REACT_APP_GOOGLE_CLIENT_ID=your-google-client-id
REACT_APP_SERVER_URL=http://localhost:8000
```

#### Server (`server/.env`)
```env
PORT=8000
URL=mongodb_connection_url
SECRET=your_jwt_secret
CLIENT_ID=your_google_client_id
BASE_URL=http://localhost:3000
```

### 4️⃣ Start the Application
#### Run Frontend
```bash
npm start
```

#### Run Backend
```bash
npm start
```

🚀 Your application will be live at `http://localhost:3000`.

---

## 🛠️ Authentication Setup (Google OAuth)
1. Go to the **[Google Cloud Console](https://console.cloud.google.com/apis/credentials)**.
2. Create a new project.
3. Navigate to **Credentials** → **Create Credentials** → **OAuth Client ID**.
4. Select **Web Application** and provide the necessary details:
   - Authorized JavaScript origins: `http://localhost:3000`
   - Authorized Redirect URIs: `http://localhost:3000/login`
5. Copy the generated **Client ID** and paste it into `REACT_APP_GOOGLE_CLIENT_ID` in `.env`.

---

Happy Coding! 🚀🎉

