# 🫀 Organ Donation & Transportation App (with Integrated Machine Learning)

This is a centralized organ donation and transplant management app built with **Kotlin + Jetpack Compose** for Android and **Spring Boot** for backend ML APIs. The app provides a seamless experience for **donors**, **recipients**, and **hospitals** — all on one platform. With ML integration and real-time Firebase support, it ensures smart and efficient communication.

---

## 🚀 Features

- 🔐 **Firebase Authentication** (Email ogin)  
- 🧠 **Machine Learning Integration** (Nearby donors finding,Review Classification)  
- 📡 **Nearby Donors/Hospitals Finder** using dbscan algorithm  
- 🔄 **Request Sending & Acceptance** between donors, recipients, and hospitals  
- 🧩 **MVVM Architecture** with Kotlin Coroutines  
- 📱 **15+ UI Screens** built with Jetpack Compose  
- 📦 **Centralized Platform** for all users (Donors, Recipients, Hospitals)  
- 📲 **Notifications** for request updates and alerts  
- 🌐 **Spring Boot API Integration** for ML-based processing   

---

## 🛠 Tech Stack

- **Frontend**: Kotlin, Jetpack Compose, MVVM, Coroutines 
- **Backend**: Spring Boot (for ML models & custom APIs),Firebase Database 
- **Machine Learning**: Text classification (review sentiment),dbscan  
- **Others**: Firebase Authentication, Realtime Database 

---

## 🧭 User Panels & UI Screenshots

### 🩸 Donor Panel

| Donor Home | Search Recipients | Recipient Detail |
|------------|-------------------|------------------|
| <img src="https://github.com/abhinavreddy8/Organ-donation-and-Transportation-with-integraed-ML/blob/master/app/src/main/res/drawable/donorhome.jpg?raw=true" width="250"/> | <img src="https://github.com/abhinavreddy8/Organ-donation-and-Transportation-with-integraed-ML/blob/master/app/src/main/res/drawable/findrecipients.jpg?raw=true" width="250"/> | <img src="https://github.com/abhinavreddy8/Organ-donation-and-Transportation-with-integraed-ML/blob/master/app/src/main/res/drawable/recipientdetails.jpg?raw=true" width="250"/> |

| Search Hospitals | Donor Notifications |
|------------------|---------------------|
| <img src="https://github.com/abhinavreddy8/Organ-donation-and-Transportation-with-integraed-ML/blob/master/app/src/main/res/drawable/findhospitals.jpg?raw=true" width="250"/> | <img src="https://github.com/abhinavreddy8/Organ-donation-and-Transportation-with-integraed-ML/blob/master/app/src/main/res/drawable/donornotifications.jpg?raw=true" width="250"/> |

---

### 🏥 Hospital Panel

| Hospital Home | Search Donors | Donor Detail |
|---------------|---------------|--------------|
| <img src="https://github.com/abhinavreddy8/Organ-donation-and-Transportation-with-integraed-ML/blob/master/app/src/main/res/drawable/hospitalhome.jpg?raw=true" width="250"/> | <img src="https://github.com/abhinavreddy8/Organ-donation-and-Transportation-with-integraed-ML/blob/master/app/src/main/res/drawable/nearbydonors.jpg?raw=true" width="250"/> | <img src="https://github.com/abhinavreddy8/Organ-donation-and-Transportation-with-integraed-ML/blob/master/app/src/main/res/drawable/donordetails.jpg?raw=true" width="250"/> |

| Search Hospitals | Hospital Notifications |
|------------------|------------------------|
| <img src="https://github.com/abhinavreddy8/Organ-donation-and-Transportation-with-integraed-ML/blob/master/app/src/main/res/drawable/findhospitals.jpg?raw=true" width="250"/> | <img src="https://github.com/abhinavreddy8/Organ-donation-and-Transportation-with-integraed-ML/blob/master/app/src/main/res/drawable/hospitalrequests.jpg?raw=true" width="250"/> |

---

### 🧬 Recipient Panel

| Recipient Home | Search Donor | Search Hospital |
|----------------|--------------|-----------------|
| <img src="https://github.com/abhinavreddy8/Organ-donation-and-Transportation-with-integraed-ML/blob/master/app/src/main/res/drawable/userdetailscreen.jpg?raw=true" width="250"/> | <img src="https://github.com/abhinavreddy8/Organ-donation-and-Transportation-with-integraed-ML/blob/master/app/src/main/res/drawable/nearbydonors.jpg?raw=true" width="250"/> | <img src="https://github.com/abhinavreddy8/Organ-donation-and-Transportation-with-integraed-ML/blob/master/app/src/main/res/drawable/findhospitals.jpg?raw=true" width="250"/> |

| Recipient Notifications |
|--------------------------|
| <img src="https://github.com/abhinavreddy8/Organ-donation-and-Transportation-with-integraed-ML/blob/master/app/src/main/res/drawable/recipientnotifications.jpg?raw=true" width="250"/> |

---

## 📂 Project Structure (MVVM)

