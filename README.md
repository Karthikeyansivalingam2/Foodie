# Foodiee — Online Food Ordering System

A full-stack food ordering and restaurant management application connecting customers, restaurant partners, and administrators.

## Overview
- **Customers:** Browse food items, manage a cart, place orders, and view order history.
- **Restaurant partners:** Manage restaurant information and incoming orders.
- **Administrators:** Oversee users, restaurant partners, and platform operations.

## Key Features
- Role-based authentication for customers, partners, and admins
- Dynamic menu and food item management
- Cart and order placement workflow
- Customer order history
- Partner order management dashboard
- Admin dashboard for platform operations
- Responsive interface using Tailwind CSS

## Tech Stack
| Layer | Technologies |
|---|---|
| Frontend | HTML5, CSS3, JavaScript, Tailwind CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB Atlas |
| Tools | Git, GitHub, VS Code, Postman |

## Architecture
The application follows a client-server approach. The frontend manages user interaction, while the Express backend handles application routes and database communication.

## Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/Karthikeyansivalingam2/Foodie.git
   cd Foodie
   ```
2. Install dependencies in the project directory:
   ```bash
   npm install
   ```
3. Create a local `.env` file and configure the variables required by the project. Example:
   ```env
   MONGODB_URI=your_mongodb_connection_string
   PORT=3000
   ```
4. Start the application using the script configured in `package.json`:
   ```bash
   npm start
   ```
   If a development script is configured, use `npm run dev`.
5. Open the local URL shown in your terminal.

> Keep credentials, database URLs, and API keys in local environment files. Never commit real secrets.

## Future Improvements
- Automated tests for key user flows
- Order status notifications
- Accessibility and performance improvements
- Deployment and setup documentation

## Author
**Karthikeyan S.**  
[GitHub Profile](https://github.com/Karthikeyansivalingam2)
