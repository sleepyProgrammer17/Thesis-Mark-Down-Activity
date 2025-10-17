# 🏘️ SmartBarangay: Integrated Document, Announcement, and Certificate Issuance System

**SmartBarangay** is a **web-based management platform** designed to modernize barangay operations by digitizing document processing, automating certificate issuance, and providing a secure communication channel for verified announcements.  
This system enhances **efficiency**, **accessibility**, and **transparency** in local public service.

---

## 📋 Overview

Barangay offices often face challenges such as slow document processing, lack of transparency, and difficulty in managing official announcements.  
**SmartBarangay** addresses these issues by integrating document management, notification, and communication tools into a unified platform that improves operational efficiency and strengthens public trust.

---

## 🚀 Key Features

### 📑 Streamlined Document Management
- Digitized processing and tracking of requests such as certificates. 
- Automated issuance and verification of barangay documents  

### ⏱️ Real-Time Updates
- Users can monitor the **real-time status** of their document requests  
- Barangay officials can update request progress directly through the system

### 🔔 Notifications
- Instant notifications to residents for request updates and announcements  
- Automated reminders for pending requests or approvals

### 🏠 Barangay Dashboard
- Centralized dashboard showing the **real-time operational status** of the barangay  
- Displays insights such as request volume, processing efficiency, and document issuance history

### 📢 Facebook Integration
- Seamless integration with **Facebook** to post official announcements and updates directly from the system  
- Ensures wider reach and verified communication with residents

---

# ⚙️ Installation Guide

Follow the steps below to set up and run the **SmartBarangay** system locally.
This system is under development features and installation can be change base on the clients needs.

---

## 🧩 1. Clone the Repository

Clone this repository to your local machine:

```bash
git clone https://github.com/<github-username>/<repo-name>.git
```

Then navigate into the project folder:

```bash
cd <repo-name>
```

---

## 🖥️ 2. Backend Setup (Express.js)

Go to the backend directory:

```bash
cd backend
```

Install the required dependencies:

```bash
npm install
```

Create a `.env` file in the backend folder and add your configuration values:

```
PORT=5000
DATABASE_URL=your_database_connection_url
# Example: postgresql://user:password@host:port/database
```

Start the Express server:

```bash
npm start
```

The backend should now run at:  
👉 **http://localhost:5000**

---

## 🌐 3. Frontend Setup (React + Vite)

Open a new terminal and navigate to the frontend directory:

```bash
cd ../frontend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file in the frontend directory and add your backend API endpoint:

```
VITE_API_URL=http://localhost:5000
```

Run the development server:

```bash
npm run dev
```

The frontend should now be available at:  
👉 **http://localhost:5173**

---

## 🔗 4. Connect Frontend and Backend

Ensure both servers (**frontend** and **backend**) are running.  
The React frontend communicates with the Express backend through the environment variable:

```
VITE_API_URL=http://localhost:5000
```

---

## 🧱 5. Build for Production (Optional)

To create a production-ready build of the frontend:

```bash
npm run build
```

Then serve the `build` folder using your backend or deploy it to any static hosting provider.

---

## ✅ 6. Done!

You now have **SmartBarangay** running locally with:

- 📡 **Express backend**  
- ⚛️ **React frontend**  
- 🔒 **Configurable `.env` environment**



![Finding Client Of the Systsem](./assets/images/image1.jpg)

## Group Members

1. Jhon Brayn Rafer – Project Lead  
2. Mac Larrie Tamayo – Developer 
3. John Andrew Valencia Manuebo –  Developer  
4. Mark Santiago – Developer  
5. Patrick Arevalo – Developer  

