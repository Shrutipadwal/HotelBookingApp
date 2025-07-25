# HotelBookingApp

`HotelBookingApp` is a minimalistic web application designed to simplify the hotel reservation process for both customers and hotel managers. It is crafted with Java and Spring Boot in backend, and Thymeleaf in frontend. The system adheres to the Model-View-Controller (MVC) architectural pattern.

## Features

- **User Registration & Management**: Users can register, login, and manage their profiles. Various data validations (e.g. strong password requirement) have been implemented.
- **Hotel Management**: Hotel managers can add/edit hotels, specifying details (e.g. name, address, room counts, prices) in a single interface.
- **Hotel Search**: Enables customers to search for available hotels based on location and check-in/check-out dates.
- **Hotel Listing**: Displays a list of available hotels with relevant details such as name, available room counts, and prices.
- **Hotel Details**: Provides in-depth information on hotels, including name, address, room availability, pricing, and an interactive map leveraging the Nominatim geocoding API and Leaflet library.
- **Room Booking**: Customers can select the desired number of rooms and get redirected to payment for finalizing the reservation.
- **Payment Processing**: Secure credit card payment with validations like Luhn checks and custom validators for expiry dates and CVV. (No third-party payment gateways are implemented.)
- **Booking Management**: Customers and hotel managers can view their bookings through the dashboard.
- **Admin Panel**: Allows administrators to manage users, hotels, rooms, and bookings.
- **Responsive Design**: The app is optimized for various devices including desktops, tablets, and smartphones.

## Technology Stack

- **Backend**:
  - Java 17
  - Spring Boot 3.1.1
  - MVC Architecture (Spring Web MVC 6.0.10)
- **Frontend**:
  - Thymeleaf 3.1.1
  - Bootstrap 5.3.0
  - Bootstrap Icons 1.10.5
  - jQuery 3.7.0
  - jQuery-UI 1.13.2
  - Leaflet 1.9.4 (interactive maps)
- **Database**:
  - MySQL
- **Security**:
  - Spring Security 6.1.1 (authentication and authorization)
- **Other Tools**:
  - Lombok (boilerplate code reduction)
  - Thymeleaf extras and layout dialect (enhanced UI functionality)

## Prerequisites

- Java JDK 17
- Maven
- MySQL

## Installation & Running

1. Clone the repository:
```bash
   git clone https://github.com/Shrutipadwal/HotelBookingApp.git

   ```
   
2. Navigate to the project directory::
   ```sh
   cd HotelBookingApp
   ```
   
3. Install the dependencies::
   ```sh
   mvn install
   ```
   
4. Update application.properties with your MySQL database configurations.
   
6. Run the application:
   ```sh
   mvn spring-boot:run
   ```
   
7. Access the application via your browser at http://localhost:8080/.

## Screenshots
- Home Page
<img width="1206" height="568" alt="Screenshot (269)" src="https://github.com/user-attachments/assets/f23abbde-6182-4a8a-a57d-6822422f933d" />

- Registration and login page
<img width="1280" height="563" alt="Screenshot (268)" src="https://github.com/user-attachments/assets/d268955b-8fd7-49e2-a742-e291f18346a7" />
<img width="1280" height="544" alt="Screenshot (267)" src="https://github.com/user-attachments/assets/a0a24958-bcdb-4e6d-b878-6823985d2e2d" />

- Search Hotel & Booking Page
<img width="1280" height="572" alt="Screenshot (262)" src="https://github.com/user-attachments/assets/02ee5aff-f834-46a0-9d60-0a6154b6a922" />
<img width="1280" height="572" alt="Screenshot (263)" src="https://github.com/user-attachments/assets/c4ee49d9-6c57-4102-893c-1f1e0d641f78" />
<img width="1280" height="579" alt="Screenshot (264)" src="https://github.com/user-attachments/assets/88533247-6b18-4cdb-b525-c9c8fcb5cf94" />

- Payment Portal
<img width="1280" height="602" alt="Screenshot (265)" src="https://github.com/user-attachments/assets/ec6ff5a5-40b3-426d-9e02-f12f46db999d" />

- Booking Confirmation
<img width="1280" height="602" alt="Screenshot (266)" src="https://github.com/user-attachments/assets/da6c8173-fb48-4beb-bfdf-c1dce2df33a6" />
<img width="1280" height="571" alt="Screenshot (261)" src="https://github.com/user-attachments/assets/97e8ce56-fdc0-4c48-9cb9-db7663c4d027" />



