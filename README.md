# HotelBookingApp

**HotelBookingApp** is a modern and minimalistic web application built to streamline hotel booking and management for both customers and hotel administrators. It follows the **Model-View-Controller (MVC)** design pattern and is developed using **Java**, **Spring Boot**, and **Thymeleaf**.

---

## ✨ Features

- **User Registration & Management**  
  - Register, log in, and manage user profiles.  
  - Includes strong password validation and input checks.

- **Hotel Management**  
  - Hotel managers can add and edit hotel information, including name, address, room count, and pricing.

- **Hotel Search**  
  - Search available hotels based on location and check-in/check-out dates.

- **Hotel Listings**  
  - Displays a list of hotels with room availability and pricing details.

- **Hotel Details**  
  - Shows detailed hotel information and an interactive map using **Leaflet** and **Nominatim API**.

- **Room Booking**  
  - Book rooms based on availability and proceed to the payment page.

- **Secure Payment Processing**  
  - Implements credit card validation including Luhn check, expiry date, and CVV format checks.  
  - (Note: No third-party payment gateway integration.)

- **Booking Management**  
  - Customers and hotel managers can view and manage their bookings via dashboards.

- **Admin Panel**  
  - Manage users, hotels, rooms, and bookings with admin privileges.

- **Responsive Design**  
  - Fully responsive UI compatible with desktops, tablets, and smartphones.

---

## 🔧 Technology Stack

### 🖥️ Backend
- Java 17  
- Spring Boot 3.1.1  
- Spring MVC 6.0.10  
- Spring Security 6.1.1  
- Lombok  

### 🎨 Frontend
- Thymeleaf 3.1.1  
- Bootstrap 5.3.0  
- Bootstrap Icons 1.10.5  
- jQuery 3.7.0  
- jQuery UI 1.13.2  
- Leaflet 1.9.4  

### 🗄️ Database
- MySQL  

### 🛠️ Other Tools
- Thymeleaf Layout Dialect  
- Nominatim Geocoding API for location mapping  

---

## 🚀 Getting Started

### ✅ Prerequisites
- Java JDK 17  
- Maven  
- MySQL  

### 📦 Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/HotelBookingApp.git
   cd HotelBookingApp
