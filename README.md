# 🐑 Wool Monitoring Application

A modern, enterprise-grade **full-stack supply chain management platform** for tracking wool from **farm to fabric**.
This system provides role-based dashboards for Farmers, Inspectors, Mill Operators, Buyers, and Admins, enabling quality tracking, marketplace operations, and real-time monitoring.

---

## 📸 Preview

<img width="1913" height="1105" src="https://github.com/user-attachments/assets/e0453ddd-d00b-4969-b76c-6c27d3ee4814" />
<img width="1919" height="1103" src="https://github.com/user-attachments/assets/2cb18300-c73b-4de8-8e03-258e01c94c9e" />

---

## 🚀 Features

### 🔐 Role-Based Access Control (RBAC)

* Farmer Dashboard
* Quality Inspector Dashboard
* Mill Operator Dashboard
* Buyer Marketplace
* Admin Panel

### 📦 Wool Batch Tracking

Track wool batches through processing stages:

* Cleaning
* Carding
* Spinning
* Dyeing
* Packaging
* Shipping

Includes **visual timeline tracking** for each batch.

### 🧪 Quality Inspection System

Lab interface for recording:

* Micron
* Yield %
* Tensile Strength
* Quality grading
* Inspection reports

### 🛒 Marketplace & Orders

* Buy/Sell wool batches
* Order management
* Invoice generation
* Approved batch listing
* Buyer dashboard

### 🌡️ IoT Monitoring

* Warehouse temperature
* Humidity monitoring
* Storage conditions dashboard
* Real-time environmental data

### 🎨 Premium UI/UX

* Dark glassmorphism theme
* Smooth animations (Framer Motion)
* Responsive design
* Dashboard analytics
* Modern UI components

---

## 🛠️ Tech Stack

### Frontend

| Technology    | Purpose            |
| ------------- | ------------------ |
| React (Vite)  | Frontend framework |
| Tailwind CSS  | Styling            |
| Framer Motion | Animations         |
| Lucide React  | Icons              |
| Context API   | State management   |
| Axios         | API requests       |

### Backend

| Technology | Purpose           |
| ---------- | ----------------- |
| Node.js    | Runtime           |
| Express.js | Backend framework |
| MongoDB    | Database          |
| Mongoose   | ODM               |
| JWT        | Authentication    |
| Multer     | File uploads      |

---

## 📂 Project Structure

```
wool-monitoring-app/
├── client/                # React Frontend
│   ├── src/
│   │   ├── components/
│   │   ├── layouts/
│   │   ├── pages/
│   │   ├── context/
│   │   └── services/
│
├── server/                # Node.js Backend
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middleware/
│   │   └── config/
│
└── README.md
```

---

## ⚡ Getting Started

### Prerequisites

* Node.js (v16+)
* MongoDB (Local or Atlas)
* npm

---

### Installation

#### 1. Clone Repository

```bash
git clone https://github.com/yourusername/wool-monitoring-application.git
cd wool-monitoring-application
```

#### 2. Install Dependencies

```bash
# Server
cd server
npm install

# Client
cd ../client
npm install
```

#### 3. Environment Variables

Create `.env` inside **server/**

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

### Running the Application

#### Start Backend

```bash
cd server
npm run dev
```

#### Start Frontend

```bash
cd client
npm run dev
```

Application runs at:

```
http://localhost:5173
```

---

## 📸 Screenshots

| Farmer Dashboard | Marketplace      |
| ---------------- | ---------------- |
| Dashboard View   | Marketplace View |

| Inspection Hub | Mobile View |
| -------------- | ----------- |
| Lab Interface  | Mobile UI   |

---

## 🎯 Key Modules

* Authentication & Authorization
* Role-based Dashboards
* Batch Tracking System
* Inspection Management
* Marketplace System
* Order & Invoice System
* IoT Monitoring Dashboard
* Analytics & Reports

---

## 🔮 Future Improvements

* Blockchain wool traceability
* Payment gateway integration
* SMS/Email notifications
* Mobile app version
* AI quality prediction
* Supply chain analytics
* Export reports (PDF/Excel)
* Multi-language support

---

## 👨‍💻 Author

**Anil Kumar**

---

## ⭐ Support

If you like this project, please give it a **star ⭐ on GitHub**.
