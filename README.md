# 🚗 Smart Parking System

A web-based Smart Parking Management System developed using **Python, Flask, HTML, CSS, JavaScript, and SQLite**. The system helps manage parking slots, vehicle entry and exit, token generation, parking records, WhatsApp booking confirmation, and overtime fine calculation.
## 🌐 Live Demo

[🚀 Open Smart Parking System](https://smart-parking-system-gn9z.onrender.com)

## 📌 Project Overview

The Smart Parking System is designed to simplify parking management by replacing manual parking processes with an automated web application.

Users can view available parking slots, enter their vehicle details, book a parking slot, receive a unique parking token, and manage vehicle exit. The system stores parking records in an SQLite database and automatically calculates overtime fines when the vehicle exceeds the expected parking duration.

## ✨ Features

- 🚗 Vehicle Entry & Exit Management
- 🅿️ Parking Slot Availability
- 🎫 Automatic Token Generation
- ⏱️ Parking Duration Calculation
- 💰 Automatic Overtime Fine Calculation
- 📱 WhatsApp Booking Confirmation
- 💾 SQLite Database Storage
- 📊 Admin Dashboard
- 🧾 Parking Record Management
- 🔄 Automatic Slot Availability Update

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Flask

### Database
- SQLite

### Development Tools
- Visual Studio Code
- Git
- GitHub

## 🔄 System Workflow

1. User enters vehicle number, phone number, and expected parking hours.
2. The system displays available parking slots.
3. User selects an available parking slot.
4. A unique parking token is generated.
5. Vehicle and parking details are stored in the SQLite database.
6. The selected parking slot is marked as occupied.
7. A WhatsApp confirmation message is generated.
8. During exit, the user provides the vehicle number and token.
9. The system calculates the actual parking duration.
10. If the actual duration exceeds the expected duration, an overtime fine is calculated.
11. The parking slot is released and becomes available again.

## 💰 Fine Calculation

The system calculates an overtime fine when the actual parking duration exceeds the expected parking duration.

**Fine Rate: ₹30 per extra hour**

## 📊 Admin Dashboard

The admin dashboard provides information about:

- Available parking slots
- Currently booked slots
- Total collected overtime fines

The dashboard can be accessed at:

```text
http://127.0.0.1:5000/admin
```

## 📂 Project Structure

```text
Smart-Parking-System/
│
├── static/
│   ├── script.js
│   └── style.css
│
├── templates/
│   ├── admin.html
│   ├── exit.html
│   └── index.html
│
├── .gitignore
├── app.py
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/maniprabha20/Smart-Parking-System.git
```

### 2. Navigate to the project

```bash
cd Smart-Parking-System
```

### 3. Install Flask

```bash
pip install flask
```

### 4. Run the application

```bash
python app.py
```

### 5. Open the application

Open your browser and visit:

```text
http://127.0.0.1:5000
```

> The SQLite database file is created automatically when the application starts.

## ✅ Advantages

- Reduces manual parking management
- Improves parking slot management
- Automates token generation
- Provides automatic overtime fine calculation
- Maintains digital parking records
- Provides WhatsApp booking confirmation
- Offers a simple and user-friendly interface
- Provides an admin dashboard for monitoring

## 🔮 Future Enhancements

- IoT-based parking sensors
- QR code-based parking entry
- RFID-based vehicle identification
- Online payment integration
- User authentication
- Cloud database integration
- Mobile application
- Real-time parking analytics
- Advanced admin dashboard
- AI-based parking prediction

## 👩‍💻 Developed By

**Maniprabha S**

B.Tech – Artificial Intelligence and Data Science