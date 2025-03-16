![Screenshot_20250315-224802](https://github.com/user-attachments/assets/8f7aa5c0-3a1d-468a-ae87-0af6ae24410d)
![Screenshot_20250315-224808](https://github.com/user-attachments/assets/c4e856b5-4ba9-4df8-9443-cc0a429a50c1)
![Screenshot_20250315-224813](https://github.com/user-attachments/assets/b39899bc-97e6-4544-9c89-54b615b8da2e)
![Screenshot_20250315-224825](https://github.com/user-attachments/assets/1d6ff455-74e8-40ee-839f-8bd857a23016)
![Screenshot_20250315-224838](https://github.com/user-attachments/assets/c2ac864d-6de8-4107-bb1b-90769066db22)
![Screenshot_20250315-224859](https://github.com/user-attachments/assets/a2a7cc17-0ee8-49e0-979e-19c8ae5062d6)
![Screenshot_20250315-224914](https://github.com/user-attachments/assets/58a32ca0-c5b2-4e82-ad80-222644c6f4b0)
![Screenshot_20250315-224924](https://github.com/user-attachments/assets/026d27dd-f166-4c11-85fd-ef01d6cec97c)
![Screenshot_20250315-224940](https://github.com/user-attachments/assets/9ec48334-5c44-4b12-bb6e-abb0b2f3f491)
![Screenshot_20250315-224956](https://github.com/user-attachments/assets/48f71d5e-6862-47eb-929e-835cf87f1de7)
![Screenshot_20250315-225001](https://github.com/user-attachments/assets/450988b3-6844-4b95-94d4-71ad21d4e417)
![Screenshot_20250315-225012](https://github.com/user-attachments/assets/c6785aa1-9e7a-4ade-b98d-53fda10c3770)
![Screenshot_20250315-225018](https://github.com/user-attachments/assets/6c152ee7-af53-4c80-9fd4-564193287c42)

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
