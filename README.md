<div align="center">

🚌 Bus & Train Ticket Booking System 🎫

Search. Book. Travel.

A full-stack web application for searching buses and trains, checking seat availability, reserving tickets, making secure payments, generating digital tickets, and managing bookings through a centralized platform.






<br/>

<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
<img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />

</div>

🚌 About the Project

Bus & Train Ticket Booking System provides a centralized online platform where passengers can search buses and trains, compare schedules and fares, check seat availability, select seats, complete online payments, receive digital tickets, and manage reservations.

The system also provides an Admin Dashboard for managing routes, schedules, buses, trains, fares, seats, users, and bookings.

Built as a full-stack academic project at GLA University, Department of Computer Science & Engineering (AI & ML).

🌟 Key Features

Feature

Description

🔍 Smart Search

Search buses and trains by source, destination, date, and type

🚌 Bus Booking

View schedules, fares, duration, and available seats

🚆 Train Booking

Search and reserve available train services

💺 Seat Selection

Select preferred available seats

🔄 Live Availability

Synchronized seat availability reduces double-booking

📅 Instant Booking

Reserve tickets after availability verification

💳 Secure Payment

Complete payments through an integrated gateway

🎫 Digital Ticket

Generate a digital ticket after successful booking

👤 Passenger Dashboard

View upcoming and previous bookings

❌ Cancellation

Manage eligible cancellations and refunds

🛠️ Admin Panel

Manage routes, schedules, vehicles, seats, fares, users and bookings

📊 Booking Insights

View reservations and occupancy information

🔐 Secure Authentication

JWT-based authentication with role-based access

📱 Responsive UI

Works across desktop, tablet and mobile

🔔 Notifications

Booking confirmations and important travel notifications

🛠️ Tech Stack

Layer

Technology

🎨 Frontend

React.js, HTML5, CSS3, JavaScript, Bootstrap / Tailwind CSS

⚙️ Backend

Node.js, Express.js REST API

🗄️ Database

MySQL / PostgreSQL

🔑 Authentication

JWT, bcrypt

🔄 Real-Time Updates

WebSockets / synchronized API

💳 Payments

Secure Payment Gateway API

🎫 Ticket Generation

PDF Ticket Generation

☁️ Deployment

Vercel / Netlify, Render / Railway

🧪 Testing

Postman, Jest / React Testing Library

🎯 Version Control

Git & GitHub

🐳 Development

Docker

🏗️ System Architecture

                    Passenger / Admin
                          │
                          ▼
                  React Frontend (SPA)
                          │
                     HTTPS / JSON
                          │
                          ▼
               Node.js + Express REST API
                          │
             ┌────────────┼────────────┐
             │            │            │
             ▼            ▼            ▼
        MySQL /       Payment      WebSocket /
       PostgreSQL      Gateway       Availability
             │
             ▼
   Users | Routes | Vehicles | Seats
   Schedules | Bookings | Payments | Tickets

🔄 Booking Workflow

User Login / Registration
          │
          ▼
Enter Source, Destination & Date
          │
          ▼
Search Bus / Train
          │
          ▼
View Schedule, Fare & Availability
          │
          ▼
Select Service & Seat
          │
          ▼
Enter Passenger Details
          │
          ▼
Verify Seat Availability
          │
          ▼
Secure Online Payment
          │
          ▼
Booking Confirmation
          │
          ▼
Generate Digital Ticket
          │
          ▼
View / Download / Manage Booking

📸 Screenshots

Home / Search

Seat Selection

Booking Page

Admin Dashboard

coming soon

coming soon

coming soon

coming soon

💡 Replace these placeholders with real screenshots once the UI is ready.

🚀 Getting Started

Prerequisites

Node.js v18+

MySQL or PostgreSQL

Git

Visual Studio Code

Installation

git clone https://github.com/<your-username>/bus-train-ticket-booking-system.git
cd bus-train-ticket-booking-system

cd server
npm install

cd ../client
npm install

Environment Variables

Create .env inside the server folder:

PORT=5000
DATABASE_URL=your_database_connection_string
JWT_SECRET=your_jwt_secret
PAYMENT_KEY=your_payment_gateway_key
EMAIL_USER=your_email_for_notifications
EMAIL_PASS=your_email_app_password

Run the App

# Backend
cd server
npm run dev

# Frontend - use another terminal
cd client
npm start

Application URL:

http://localhost:3000

📂 Folder Structure

bus-train-ticket-booking-system/
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── services/
│   │   └── App.js
│   └── package.json
│
├── server/
│   ├── models/
│   │   ├── User.js
│   │   ├── Bus.js
│   │   ├── Train.js
│   │   ├── Route.js
│   │   ├── Schedule.js
│   │   ├── Seat.js
│   │   ├── Booking.js
│   │   └── Payment.js
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
├── .gitignore
├── README.md
└── LICENSE

🗄️ Core Data Model

Entity

Key Fields

User

name, email, password, role

Bus

bus_number, operator, type, capacity

Train

train_number, train_name, class, capacity

Route

source, destination, distance

Schedule

service_id, route_id, departure, arrival, travel_date

Seat

service_id, seat_number, class, status

Booking

user_id, service_id, seat_id, passenger_details, status

Payment

booking_id, amount, payment_method, transaction_id, status

Ticket

booking_id, ticket_number, issue_date, journey_details

🔐 Security

JWT-based authentication

Password hashing using bcrypt

Role-based authorization for Admin and Passenger

Server-side booking validation

Seat availability verification before confirmation

Secure payment processing

Protected API routes

Environment variables for sensitive configuration

🗺️ Roadmap

User authentication

Bus and train search design

Route and schedule management

Seat selection module

Booking conflict prevention

Admin dashboard design

Online payment integration

Digital PDF ticket generation

Email booking confirmations

SMS / WhatsApp travel reminders

Live bus/train tracking

AI-based travel recommendations

Mobile application

Real-world transportation API integration

🤝 Contributing

Contributions are welcome!

Fork the project

Create your feature branch

git checkout -b feature/AmazingFeature

Commit your changes

git commit -m "Add some AmazingFeature"

Push to the branch

git push origin feature/AmazingFeature

Open a Pull Request

📄 License

Distributed under the MIT License. See LICENSE for more information.

👤 Author

<div align="center">

Koushal Gupta

B.Tech CSE (AI & ML) | GLA University
University Roll No.: 22515500035



</div>

<div align="center">

🚌 "Search smart. Book easy. Travel better." 🚆

⭐ If you like this project, don't forget to star the repo! ⭐

</div>
