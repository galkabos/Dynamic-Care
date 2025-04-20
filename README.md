# 🏥 DynamicCare - Patient & Caregiver Management System

DynamicCare is a full-stack healthcare management web application built with **Next.js** and **Firebase Realtime Database**, designed to help nurses and caregivers manage patients, assign tasks, track safety protocols, and ensure efficient shift workflows.

## 🚀 Features

### ✅ Authentication
- Secure login using Firebase Authentication.
- Role-based access for **nurses** and **caregivers**.

### 🧍 Patient Management
- Add new patients with medical info, safety instructions, and room assignments.
- View and edit patient details, including allergies, medications, and care instructions.
- Track patient activities like **diaper change**, **shower**, and **position change** with status updates.

### 📝 Task Scheduling
- Nurses can assign specific tasks to caregivers by day and time.
- Tasks support real-time status updates and are tracked visually.
- Diaper changes include additional documentation via a modal form.

### 🧑‍⚕️ Caregiver Interface
- Displays today's tasks, shift-based filtering, and assigned patients.
- Allows caregivers to mark tasks as completed.
- Automatically filters tasks by current shift (morning/evening/night).

### 📋 Nurse Dashboard
- Overview of all caregivers' assignments.
- Add new task assignments to caregivers dynamically.
- View urgent and non-urgent recommendations and mark them as completed.

### 🧠 Recommendations System
- Nurses can view recommendations filtered by urgency, category, and patient name.
- Tasks can be marked as completed for tracking follow-up care.

## 🛠️ Technologies Used

- **Next.js (App Router)**
- **React + TypeScript**
- **Firebase Authentication**
- **Firebase Realtime Database**
- **Tailwind CSS**
- **JWT for session token handling**

