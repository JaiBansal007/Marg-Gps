## 🚩 PS: Swadeshi for Atmanirbhar Bharat - Transportation & Logistics (25138)

Submit your ideas to address the growing pressures on the city's resources, transport networks, and logistic infrastructure.

---

## 💡 Solution: MARG Unified GPS Platform


MARG is a unified GPS platform transforming government logistics with real-time tracking, predictive analytics, and seamless data integration, enabling smarter, more transparent operations. It offers multiple features like:

- **Smart Geofence Engine**
- **Historical Trail Playback**
- **Role-Based Access Control**
- **Bulk & Smart Utilities**
- **Smart Alerts**
- **Advanced Dashboards**
- **Comprehensive Reports & Export**
- **Email Notifications & Alerts**

## 📝 Project Overview

This project is a full-stack solution designed for real-time vehicle tracking, alert management, and logistics monitoring. It consists of:

- **Backend**: A Node.js/TypeScript API server that handles GPS data ingestion, alert processing (such as geofence, overspeeding, stoppage, and more), user and entity management, and database operations. It supports real-time data processing and provides RESTful APIs for the frontend.
- **Frontend**: A modern React/TypeScript web application (built with Vite and styled using Tailwind CSS) that provides dashboards, live tracking, alert visualization, and user management interfaces for logistics and fleet operations.

The system is designed for scalability, modularity, and ease of deployment, making it suitable for logistics companies, fleet operators, or any scenario requiring live vehicle monitoring and alerting.

---


## 🛠 Setup Instructions

### Backend

1. **Install Dependencies**
   ```bash
   cd backend
   npm install
   ```
2. **Create a `.env` file** in the `backend` directory and add:
   ```env
   DATABASE_URL=your-database-url-here
   JWT_SECRET=your-secret-key-here
   ```
   Replace with your actual values.

### Frontend

1. **Install Dependencies**
   ```bash
   cd ../Frontend
   npm install
   ```
2. **Configure Environment Variables**
   - Copy `.env.example` to `.env`:
     ```bash
     cp .env.example .env
     ```
   - Edit `.env` and set:
     ```env
     VITE_BACKEND_URL=your-backend-url-here
     ```

---

## 🚀 Running the Project

### Backend
Start the backend development server:
```bash
cd backend
npm run dev
```

### Frontend
Start the frontend development server:
```bash
cd Frontend
npm run dev
```
The app will be available at [http://localhost:5173](http://localhost:5173) (or as configured by Vite).

---

## 🔄 Database Schema Changes (Backend)
If you make changes to the backend database schema:
1. **Generate Migrations**:
   ```bash
   npx drizzle-kit generate
   ```
2. **Apply Migrations**:
   ```bash
   npx drizzle-kit migrate
   ```

---

## 🗂 Project Structure
- `backend/`: Node.js/TypeScript backend API
- `Frontend/`: React/TypeScript frontend app

---

## 🎨 Tech Stack
- **Backend**: Node.js, TypeScript, Drizzle ORM
- **Frontend**: React, TypeScript, Vite, Tailwind CSS

---

## ⚠️ Important Notes
- Do **not** modify the `drizzle` files in the backend.
- Never commit your actual `.env` files to version control.
- Tailwind CSS is pre-configured in the frontend.

---

## Team Details

**Team Name:** Tree.io

**Team Leader:** [@Dhruv](https://github.com/Dhruv-Tuteja)

**Team Members:**

- **MEMBER_1** - 2023UIN3332 - [@Dhruv](https://github.com/Dhruv-Tuteja)
- **MEMBER_2** - 2023UCS1548 - [@Nayan](https://github.com/NASA12345)
- **MEMBER_3** - 2023UCA1804 - [@Tushar](https://github.com/TusharSachdeva29)
- **MEMBER_4** - 2023UCA1869 - [@Jai](https://github.com/JaiBansal007)
- **MEMBER_5** - 2023UCA1728 - [@Yashaswini](https://github.com/Yashaswini-Sharma)
- **MEMBER_6** - 2023UCA1600 - [@Rohan](https://github.com/RohanJ26)

## Project Links

- **SIH Presentation:** [Final SIH Presentation](URL TO PPT UPLOADED TO GITHUB)
- **Video Demonstration:** [Watch Video](UNLISTED YOUTUBE LINK)
- **Live Deployment:** [View Deployment](DEPLOYED LINK IF ANY)
- **Source Code:** [GitHub Repository](https://github.com/TusharSachdeva29/sih-25)
- **Additional Resources:** [Other Relevant Links](ANY OTHER RELEVANT LINKS)