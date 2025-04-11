# 🚢 SplitShips

## Overview  
**SplitShips** is a web application that optimizes shipping for small businesses through **collaborative logistics**. The platform allows users to share shipment space, lowering costs and reducing environmental impact. By combining real-time tracking, dynamic pricing, and robust search tools, SplitShips addresses common shipping inefficiencies for small-scale businesses.

---

## 🎯 Purpose  
SplitShips aims to:
- **Reduce shipping costs** for small businesses via shared logistics.
- **Promote sustainability** by maximizing shipment space utilization.
- **Streamline shipment management** with intuitive tools for tracking and documentation.

---

## ✨ Features  
- **User Account Management**  
  Secure registration and login using Firebase Authentication.

- **Shipment Listings**  
  Create, browse, and manage collaborative shipment opportunities.

- **Dynamic Pricing**  
  Automatically calculate shared shipping costs based on real-time data (e.g., package weight, destination, and available space).

- **Real-Time Tracking**  
  Monitor shipment status with Firebase-powered live updates.

- **Two-Way Rating System**  
  Foster trust and transparency with mutual post-shipment reviews.

- **Advanced Search & Filtering**  
  Filter shipments by size, price, date, and availability.

- **Document Management**  
  Securely upload and manage shipment-related documents (invoices, customs forms, etc.).

---

## ✅ Requirements  

### Functional Requirements
- Users must register with a valid email to access platform features.
- Shipment listings are viewable on the dashboard post-login.
- Shipment statuses must update in real time.
- Ratings and reviews are stored and shown after shipment completion.
- Uploaded documents must be securely stored and accessible when needed.

### Non-Functional Requirements
- Built using Firebase for authentication and real-time data sync.
- Cross-platform support: works on desktop and mobile browsers.
- UI/UX remains consistent across all device types.
- Supports a minimum of 100 concurrent users.
- Average response time should remain under 2 seconds under high traffic.
- Adheres to data privacy and compliance regulations.

---

## 🛠️ Installation

### Clone the Repository
```bash
git clone <repository-url>
```

### Set Up Firebase
1. Create a Firebase project: [https://console.firebase.google.com](https://console.firebase.google.com)
2. Enable Firebase Authentication and Firestore.
3. Add your Firebase configuration to the environment variables.

### Install Dependencies
```bash
npm install
```

### Run the Application
```bash
npm start
```

### Access Locally
Open `http://localhost:3000` in your browser.

---

## 🚀 Deployment
- Deployed on a cloud platform (e.g., **Firebase Hosting**, **Vercel**).
- Firebase backend handles authentication, data storage, and real-time tracking.
- Make sure environment variables are properly set in production.

---

## 🗂️ Project Structure
```
/src       → Application source code  
/docs      → Documentation (SRS, UI design, system design)  
/scripts   → Deployment and setup scripts  
/tests     → Unit and integration tests  
```

---

## 👥 Contributors
- **Robert Dunham** – Firebase Integration, Sprint Documentation  
- **Eyob Gizachew** – UI Design & Requirements  
- **Kidus Sebsibe** – Dynamic Pricing Model  
- **Yeamlak Workneh** – Backend Features, Document Management

---

## 📄 Documentation
- [System Requirements Specification (SRS)](./docs/SRS.pdf)
- User Interface Design Document
- System Design Document

---

## 🧩 Open Issues
- Finalizing the dynamic pricing algorithm.
- Enhancing advanced search filters.
- Testing real-time data synchronization.
- Strengthening document upload functionality.

---

## 📜 License
This project is developed under the terms outlined in the **Agreement Between Customer and Contractor** (see SRS Appendix A).

---

## 📬 Contact
For support or questions, contact the SplitShips team:  
Robert Dunham, Eyob Gizachew, Kidus Sebsibe, Yeamlak Workneh

---
