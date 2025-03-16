
# Takeaway
This is a simple fully functional takeaway website. My first web dev project!

---
# GDC Takeaway - Order Management & WhatsApp Notification System  

**GDC Takeaway** is a streamlined **delivery management system** designed for efficient order tracking, kitchen coordination, and automated customer communication. Built using **HTML, CSS, JavaScript**, and **Firebase Firestore**, it ensures real-time order updates, security, and a responsive design for seamless access across devices. **ChatGPT** was used to assist in structuring the project and refining features.  

## Features  

### 🔹 **Admin Dashboard**  
- **Menu Management** – Add, update, and remove menu items.  
- **Staff Management** – Manage delivery staff, chefs, and counter employees.  

### 🔹 **Chef Dashboard**  
- **New Orders Tab** – View incoming orders.  
- **Cooking Tab** – Track orders in progress.  
- **Ready Tab** – Mark completed orders ready for pickup.  

### 🔹 **Counter Dashboard**  
- **Ready Tab** – Monitor orders ready for handoff.  
- **Completed Tab** – Track fulfilled orders.  
- **Cash Order Tab** – Manage cash-based transactions separately.  

### 🔹 **Additional Features**  
✅ **Real-time WhatsApp Order Updates** – Customers receive automated status updates via **Twilio WhatsApp API**.  
✅ **Firestore Integration** – Secure and scalable order storage with real-time updates.  
✅ **Responsive Design** – Fully optimized for mobile and desktop viewing.  
✅ **Dynamic Data Updation** – Orders and dashboard data update in real time without page reloads.  
✅ **Security Features** – User authentication and access control to prevent unauthorized modifications.  
✅ **Developed with HTML, CSS, JavaScript** – Lightweight and efficient frontend.  
✅ **Built on Mobile** – Developed and hosted using simple HTTP on an Android smartphone.  
✅ **ChatGPT-Assisted Development** – AI-assisted structuring and feature refinement.  

This project is ideal for small food delivery businesses looking for an **efficient, secure, and automated order management system**.  

### **4️⃣ Manually Create Your Own `firebase-config.js` and `twilio-config.json` (Not Uploaded to GitHub)**  

#### **Create `firebase-config.js` (Private)**
- **File Name:** `firebase-config.js`  
- **File Type:** JavaScript  
- **Content:** _(Replace with real credentials)_
  ```javascript
  export const firebaseConfig = {
      apiKey: "YOUR_REAL_API_KEY",
      authDomain: "YOUR_REAL_AUTH_DOMAIN",
      projectId: "YOUR_REAL_PROJECT_ID",
      storageBucket: "YOUR_REAL_STORAGE_BUCKET",
      messagingSenderId: "YOUR_REAL_MESSAGING_SENDER_ID",
      appId: "YOUR_REAL_APP_ID"
  };
  ```

---

#### **Create `twilio-config.json` (Private)**
- **File Name:** `twilio-config.json`  
- **File Type:** JSON  
- **Content:** _(Replace with real credentials)_
  ```json
  {
      "accountSid": "YOUR_REAL_TWILIO_ACCOUNT_SID",
      "authToken": "YOUR_REAL_TWILIO_AUTH_TOKEN",
      "TWILIO_PHONE": "whatsapp:+YOUR_REAL_TWILIO_PHONE_NUMBER"
  }
  ```

---
