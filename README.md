🚌 Bus Booking API
🔗 Documentation Link: https://documenter.getpostman.com/view/42689573/2sAYdfrXKa

📌 Overview
The Bus Booking API allows users to search for buses, book tickets, retrieve booking details, and cancel reservations seamlessly.

🔐 Authentication
All requests require an API Key 🔑
Include your key in the Authorization header as:
Bearer YOUR_API_KEY
🚏 Endpoints
1️⃣ Search Buses 🔍
📌 Find available buses based on:
✅ Departure & Destination Cities
✅ Travel Date
✅ Seat Availability

2️⃣ Book Ticket 🎟️
📌 Secure a seat by providing:
✅ Bus ID
✅ Passenger Details
✅ Payment Method

3️⃣ Get Booking Details 📄
📌 Retrieve ticket details using the Booking ID

4️⃣ Cancel Booking ❌
📌 Cancel a ticket and receive a refund based on policy

⚠️ Error Handling
Uses standard HTTP status codes
Provides clear error messages in case of invalid requests
⏳ Rate Limiting
⚡ 1000 requests per hour per user
🚫 Exceeding the limit results in a 429 Too Many Requests error

📩 Support
For assistance, contact 📧 mahesh.v2022ai-ds@sece.ac.in
