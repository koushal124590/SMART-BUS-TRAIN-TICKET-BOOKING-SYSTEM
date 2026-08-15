<div align="center">

# 🚌 Bus & Train Ticket Booking System 🎫

### *Search. Book. Travel.*

A full-stack web application that lets passengers search buses and trains, check real-time seat availability, reserve tickets online, make secure payments, and manage their bookings — while giving administrators a powerful dashboard to manage routes, schedules, vehicles, seats, fares, and reservations.

![Made with Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4-ff4b4b?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![GLA University](https://img.shields.io/badge/GLA%20University-Project-1F4E78?style=for-the-badge)

<br/>

<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
<img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />

</div>

---

## 🚌 About the Project

Ever struggled to compare bus and train schedules, find available seats, or manage tickets from different platforms? **Bus & Train Ticket Booking System** brings the complete journey-booking process into one centralized platform.

This full-stack application lets passengers search **buses and trains**, compare schedules and fares, check **real-time seat availability**, select seats, make secure payments, receive digital tickets, and manage their reservations — while administrators get a centralized dashboard to manage routes, schedules, vehicles, seats, fares, and bookings.

> Built as a full-stack academic project at **GLA University**, Department of Computer Science & Engineering (AI & ML).

---

## 🌟 Key Features

<table>
<tr>
<th>Feature</th>
<th>Description</th>
</tr>

<tr>
<td>🔍 <b>Smart Search</b></td>
<td>Search buses and trains by source, destination, travel date, timing, and transportation type</td>
</tr>

<tr>
<td>🚌 <b>Bus Booking</b></td>
<td>View bus schedules, fares, journey duration, operators, and available seats</td>
</tr>

<tr>
<td>🚆 <b>Train Booking</b></td>
<td>Search and reserve available train services with schedule and class information</td>
</tr>

<tr>
<td>💺 <b>Seat Selection</b></td>
<td>View available seats and select preferred seats before confirming the booking</td>
</tr>

<tr>
<td>🔄 <b>Real-Time Availability</b></td>
<td>Synchronized seat availability helps prevent two passengers from booking the same seat</td>
</tr>

<tr>
<td>📅 <b>Instant Booking</b></td>
<td>Reserve a selected bus or train after successful availability verification</td>
</tr>

<tr>
<td>💳 <b>Secure Payments</b></td>
<td>Complete ticket payments through an integrated secure payment gateway</td>
</tr>

<tr>
<td>🎫 <b>Digital Tickets</b></td>
<td>Automatically generate a digital ticket containing passenger and journey details</td>
</tr>

<tr>
<td>👤 <b>Passenger Dashboard</b></td>
<td>View upcoming bookings, previous bookings, ticket details, and travel history</td>
</tr>

<tr>
<td>❌ <b>Cancellation</b></td>
<td>Cancel eligible reservations and view applicable refund information</td>
</tr>

<tr>
<td>🛠️ <b>Admin Panel</b></td>
<td>Manage users, buses, trains, routes, schedules, fares, seats, and reservations</td>
</tr>

<tr>
<td>📊 <b>Booking Insights</b></td>
<td>Track reservations, seat occupancy, schedules, and booking statistics</td>
</tr>

<tr>
<td>🔐 <b>Secure Authentication</b></td>
<td>JWT-based login with role-based access for passengers and administrators</td>
</tr>

<tr>
<td>📧 <b>Notifications</b></td>
<td>Send booking confirmation and important ticket-related notifications</td>
</tr>

<tr>
<td>📱 <b>Responsive Design</b></td>
<td>Works seamlessly across desktop, tablet, and mobile devices</td>
</tr>

</table>

---

## 🛠️ Tech Stack

<div align="center">

<table>
<tr>
<th>Layer</th>
<th>Technology</th>
</tr>
<tr>
<td>🎨 Frontend</td>
<td>React.js, HTML5, CSS3, JavaScript, Bootstrap / Tailwind CSS</td>
</tr>
<tr>
<td>⚙️ Backend</td>
<td>Node.js, Express.js (REST API)</td>
</tr>
<tr>
<td>🗄️ Database</td>
<td>MySQL / PostgreSQL</td>
</tr>
<tr>
<td>🔑 Authentication</td>
<td>JWT, bcrypt</td>
</tr>
<tr>
<td>🔄 Real-Time Sync</td>
<td>WebSockets / synchronized API availability</td>
</tr>
<tr>
<td>💳 Payments</td>
<td>Secure Payment Gateway API</td>
</tr>
<tr>
<td>🎫 Ticket Generation</td>
<td>PDF digital ticket generation</td>
</tr>
<tr>
<td>☁️ Deployment</td>
<td>Vercel / Netlify, Render / Railway</td>
</tr>
<tr>
<td>🧪 Testing</td>
<td>Postman, Jest / React Testing Library</td>
</tr>
<tr>
<td>🎯 Version Control</td>
<td>Git & GitHub</td>
</tr>
</table>

</div>

---

## 🏗️ System Architecture

```text
Passenger / Admin
       │
       ▼
React Frontend (SPA)
       │
       │ HTTPS / JSON
       ▼
Node.js + Express REST API
       │
       ├───────────────┐
       │               │
       ▼               ▼
MySQL / PostgreSQL   Payment Gateway
       │
       ├── Users
       ├── Routes
       ├── Buses
       ├── Trains
       ├── Schedules
       ├── Seats
       ├── Bookings
       └── Tickets
```

---

## 📸 Screenshots

<div align="center">

| Home / Search | Seat Selection | Booking Flow | Admin Dashboard |
|---|---|---|---|
| *coming soon* | *coming soon* | *coming soon* | *coming soon* |

</div>

> 💡 Replace these placeholders with real screenshots or GIFs once the UI is ready.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have installed:

- [Node.js](https://nodejs.org/) (v18 or above)
- [MySQL](https://www.mysql.com/) or PostgreSQL
- [Git](https://git-scm.com/)
- Visual Studio Code

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/bus-train-ticket-booking-system.git

# 2. Navigate into the project directory
cd bus-train-ticket-booking-system

# 3. Install backend dependencies
cd server
npm install

# 4. Install frontend dependencies
cd ../client
npm install
```

### Environment Variables

Create a `.env` file inside the `server` folder:

```env
PORT=5000
DATABASE_URL=your_database_connection_string
JWT_SECRET=your_jwt_secret
PAYMENT_KEY=your_payment_gateway_key
EMAIL_USER=your_email_for_notifications
EMAIL_PASS=your_email_app_password
```

### Run the App

```bash
# Start backend (from /server)
npm run dev

# Start frontend (from /client)
npm start
```

The app will be live at:

```text
http://localhost:3000
```

---

## 📂 Folder Structure

```text
bus-train-ticket-booking-system/
├── client/                         # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── services/
│   │   └── App.js
│   └── package.json
│
├── server/                         # Node/Express backend
│   ├── models/
│   │   ├── User.js
│   │   ├── Bus.js
│   │   ├── Train.js
│   │   ├── Route.js
│   │   ├── Schedule.js
│   │   ├── Seat.js
│   │   ├── Booking.js
│   │   ├── Payment.js
│   │   └── Ticket.js
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
├── .gitignore
├── README.md
└── LICENSE
```

---

## 🗄️ Core Data Model

<table>
<tr>
<th>Entity</th>
<th>Key Fields</th>
</tr>
<tr>
<td><b>User</b></td>
<td>name, email, password, role</td>
</tr>
<tr>
<td><b>Bus</b></td>
<td>bus_number, operator, type, capacity</td>
</tr>
<tr>
<td><b>Train</b></td>
<td>train_number, train_name, class, capacity</td>
</tr>
<tr>
<td><b>Route</b></td>
<td>source, destination, distance</td>
</tr>
<tr>
<td><b>Schedule</b></td>
<td>service_id, route_id, departure, arrival, travel_date</td>
</tr>
<tr>
<td><b>Seat</b></td>
<td>service_id, seat_number, class, status</td>
</tr>
<tr>
<td><b>Booking</b></td>
<td>user_id, service_id, seat_id, passenger_details, status</td>
</tr>
<tr>
<td><b>Payment</b></td>
<td>booking_id, amount, payment_method, transaction_id, status</td>
</tr>
<tr>
<td><b>Ticket</b></td>
<td>booking_id, ticket_number, issue_date, journey_details</td>
</tr>
</table>

---

## 🗺️ Development Roadmap

<table>
<tr>
<th>Status</th>
<th>Development Task</th>
</tr>
<tr>
<td>✅ Completed</td>
<td>User authentication and role management</td>
</tr>
<tr>
<td>✅ Completed</td>
<td>Bus and train search module</td>
</tr>
<tr>
<td>✅ Completed</td>
<td>Route and schedule management design</td>
</tr>
<tr>
<td>🔄 In Development</td>
<td>Seat selection and availability module</td>
</tr>
<tr>
<td>🔄 In Development</td>
<td>Booking conflict prevention</td>
</tr>
<tr>
<td>🔄 In Development</td>
<td>Admin dashboard</td>
</tr>
<tr>
<td>⏳ Planned</td>
<td>Online payment integration</td>
</tr>
<tr>
<td>⏳ Planned</td>
<td>Digital PDF ticket generation</td>
</tr>
<tr>
<td>⏳ Planned</td>
<td>Email booking confirmations</td>
</tr>
<tr>
<td>⏳ Planned</td>
<td>Live bus/train tracking</td>
</tr>
<tr>
<td>⏳ Planned</td>
<td>AI-based travel recommendations</td>
</tr>
<tr>
<td>⏳ Planned</td>
<td>Mobile application</td>
</tr>
<tr>
<td>⏳ Planned</td>
<td>Real-world transportation API integration</td>
</tr>
</table>

---

## 🤝 Contributing

Contributions make the open-source community amazing! Any contributions are **greatly appreciated**.

1. Fork the project
2. Create your feature branch

```bash
git checkout -b feature/AmazingFeature
```

3. Commit your changes

```bash
git commit -m "Add some AmazingFeature"
```

4. Push to the branch

```bash
git push origin feature/AmazingFeature
```

5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

## 👤 Author

<div align="center">

**Koushal Gupta**

B.Tech CSE (AI & ML) | GLA University | Roll No. 22515500035

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/<your-username>)

</div>

---

<div align="center">

### 🚌 *"Search smart. Book easy. Travel better."* 🚆

⭐ **If you like this project, don't forget to star the repo!** ⭐

</div>
