# 🏨 Hotel Management System

A simple *Java console application* to manage hotel room bookings.  
It allows customers to book multiple rooms, keeps track of available rooms, and stores booking details with timestamps in a file.

---

## ✨ Features

- Input validation for customer name and phone number 📋  
- Book multiple rooms in one go 🛏  
- Unique room number assignment for each booking 🔢  
- Real-time available rooms update  
- Stores booking details (customer info, room numbers, timestamp) in bookings.txt 📂  
- Friendly console interface  

---

## 🛠 How It Works

1. *Enter your name and phone number* with proper validation.  
2. View total and available rooms along with the price per room.  
3. Enter the number of rooms you want to book.  
4. The system checks availability and confirms booking with unique room numbers.  
5. Booking details are saved in bookings.txt with the current date and time.  
6. Optionally book more rooms until you choose to exit.  

---

## 💻 Usage

1. Clone or download the repository.  
2. Compile the Java file:  
   bash
   javac HotelManagement.java
   
3. Run the program:  
   bash
   java HotelManagement
   
4. Follow the on-screen instructions.

---

## 📁 File Output

* *bookings.txt* — Contains logs of all bookings with customer details and booking timestamps.

---

## 👨‍💻 Code Structure

- Details — Stores and displays customer name and phone number.
- Room — Manages room availability, pricing, and generates unique room numbers.
- BookingRoom — Handles booking process: room allocation, availability check, file saving.
- HotelManagement — Main class that manages user interaction and coordinates the booking workflow.

---

## 🚀 Future Enhancements

- Add cancellation or modification options  
- Introduce room categories (e.g., Deluxe, Suite)  
- Use a database instead of file storage  
- Develop a GUI with JavaFX or Swing  
- Add invoice/receipt generation  

---

## 📌 Authors

- Kritika Jha  
- Ayush Awasthi  
- Tarun Kushwaha  
- Aditya Kumar  

