# 🏥 Smart Queue & Token Management System  
A real-time, intelligent queue automation platform that helps hospitals and clinics manage tokens, minimize waiting time, and deliver a seamless patient experience.

---

## 📌 Project Summary  

Hospital queues are often inefficient, overcrowded, and frustrating for both patients and doctors. Traditional token systems lack real-time updates, emergency handling, and proper communication.

The **Smart Queue & Token Management System** solves these issues through:  
- **Dynamic queue management**  
- **Instant automatic token generation**  
- **Live patient updates**  
- **Emergency slot handling**  
- **Smart prescription generation**  

This platform digitizes hospital queue flow, improving workflow efficiency, doctor utilization, and patient satisfaction.

---

## 🚀 Key Features  

- 🎫 **Automatic Token Generation** on appointment bookings  
- 🧍🧍‍♀️ **Human-like Live Queue Visualization** with animated characters  
- 🩺 **Multi-Department & Doctor Selection**  
- 🕒 **Dynamic Slot Management** (handles unavailable & emergency slots)  
- 🔔 **Real-Time Notifications** on queue progress  
- 📄 **NLP-Based Smart Prescription Builder**  
- 🧑‍⚕️ **Admin & Doctor Panels**  
- 📊 **Analytics Dashboard**  
- 🤖 **Help Chatbot**  
- 🌐 **Beginner-Friendly UI**

---

## 🛠️ Tech Stack  

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Firebase Firestore  
- **Authentication:** Firebase Auth  
- **Hosting:** Firebase Hosting  
- **Notifications:** Firebase Cloud Messaging  
- **Prescription:** JS + NLP templates  

---

## 🧪 How It Works  

1. Patient chooses department → doctor → date → slot  
2. System generates a **unique token instantly**  
3. **Queue screen updates live** with animated movement  
4. Patients receive **notifications** on queue progress  
5. Doctors manage queue through their panel  
6. **Smart prescriptions** are generated and sent to pharmacy  
7. Admin dashboard displays analytics & queue activity  

---

## 🧩 Example Use Cases  

| Role        | Example Action                                      | System Response                              |
|-------------|------------------------------------------------------|-----------------------------------------------|
| Patient     | Books appointment in Dermatology                     | Token generated + live updates start          |
| Doctor      | Marks patient as "in consultation"                  | Queue shifts for all waiting patients         |
| Admin       | Adds emergency patient                               | Queue adjusts with fairness rules             |
| Pharmacy    | opens prescription                                   | Prepares medicine in advance                  |

---

## 📥 Installation & Setup  

Follow these steps to run the Smart Queue System locally.



## 📁 1. Clone the Repository  

```bash
git clone https://github.com/your-username/smart-queue-token-system.git
cd smart-queue-token-system
```

## ⚙️ 2. Add Firebase Configuration

Create:
```bash
/config/firebaseConfig.js
```
Paste your Firebase project credentials:
```bash
export const firebaseConfig = {
  apiKey: "YOUR_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "SENDER_ID",
  appId: "APP_ID",
};

```

## ▶️ 3. Run the App Locally

Simply open the landing page in your browser:
```bash
landingpage.html
```
## 📸 Sample Output

### 🔹 Home Page
<img width="1920" height="1579" alt="screencapture-file-C-Users-rekha-OneDrive-Shreya-Projects-Prototype-landing-page-html-2025-11-20-18_25_17" src="https://github.com/user-attachments/assets/edbf9f85-aa6b-40a8-83b2-8b4925390eed" />

### 🔹 Patient Dashboard
![WhatsApp Image 2025-11-20 at 6 38 11 PM](https://github.com/user-attachments/assets/c6e55580-b9e6-4a5e-9c2d-0a88961c5170)

### 🔹 Book Token
![WhatsApp Image 2025-11-20 at 6 38 12 PM](https://github.com/user-attachments/assets/915faaea-76a2-4c83-a4a2-e6e8289cf456)

### 🔹 Generated Token
<img width="1892" height="877" alt="Screenshot 2025-09-24 130237" src="https://github.com/user-attachments/assets/abfaa0bc-05a1-45c0-a522-ac6de8071e8c" />

### 🔹 History
<img width="1920" height="1954" alt="screencapture-file-C-Users-rekha-OneDrive-Shreya-Projects-MediQueue-history-html-2025-11-20-18_47_04" src="https://github.com/user-attachments/assets/f267b88d-0039-4b19-a854-c939e02c683a" />

### 🔹 Live Queue Status
<img width="1920" height="1255" alt="screencapture-file-C-Users-rekha-OneDrive-Shreya-Projects-MediQueue-queue-html-2025-11-20-18_49_58" src="https://github.com/user-attachments/assets/dcd78e0b-8ea8-4f27-881f-9bda545c9197" />

### 🔹 Admin Dashboard
<img width="1920" height="984" alt="screencapture-file-C-Users-rekha-OneDrive-Shreya-Projects-MediQueue-admin-dashboard-html-2025-11-20-18_51_16" src="https://github.com/user-attachments/assets/a9b3303b-8f9d-4178-a4b4-a2141d85d294" />

### 🔹 Doctor Availability
<img width="1941" height="877" alt="screencapture-file-C-Users-rekha-OneDrive-Shreya-Projects-MediQueue-availability-html-2025-11-20-18_53_00" src="https://github.com/user-attachments/assets/8ca557bb-daf7-43cf-80d9-8b6cfe19fd89" />

### 🔹 Queue Management
<img width="1920" height="1140" alt="screencapture-file-C-Users-rekha-OneDrive-Shreya-Projects-MediQueue-admin-queue-html-2025-11-20-18_53_51" src="https://github.com/user-attachments/assets/9fad8d88-44f9-4665-aed7-a7103bd00253" />

### 🔹 Reports
<img width="1920" height="1006" alt="screencapture-file-C-Users-rekha-OneDrive-Shreya-Projects-MediQueue-report-html-2025-11-20-18_54_28" src="https://github.com/user-attachments/assets/92eec788-8804-4a0d-8f87-551281d1e5a5" />

### 🔹 Prescription
<img width="1920" height="1537" alt="screencapture-file-C-Users-rekha-OneDrive-Shreya-Projects-MediQueue-prescription-html-2025-11-20-18_56_14" src="https://github.com/user-attachments/assets/5c1f3505-fb68-4768-a28c-330ba82acdc1" />







