# Expense Tracker System

## Overview
This Expense Tracker application helps users manage their finances by allowing them to log expenses, categorize spending, and generate insightful reports. The system supports secure authentication, a responsive interface, and a detailed dashboard for tracking expenses effectively.

## Features

### User Authentication & Access Control
- Secure user registration and login system.

### Expense & Category Management
- Create, edit, and delete expense entries and categories.
- Track spending by category, date, and description.
- Attach receipts or other relevant documents to expense records.

### Dashboard & Reporting
- Interactive dashboard displaying total expenses and category-wise spending.
- Visual representation of expenses through pie charts and bar graphs.
- Generate reports based on date ranges and specific categories.

### Responsive UI
- A fully responsive design that works on desktop, tablet, and mobile devices.
- Built using React.js for dynamic and reusable UI components.
- Styled with Bootstrap and Material Icons for a modern look.

## Tech Stack

### Frontend:
- React.js for UI development.
- Redux for state management.
- Bootstrap for responsive styling.

### Backend:
- Node.js with Express.js for API development.
- Mongoose ORM for database schema and validation.

### Database:
- MongoDB as the NoSQL database.

## Installation & Setup

### Clone the Repository
```sh
git clone https://github.com/Priyanshu9898/Expense-Tracker-App
cd Expense-Tracker-App
```

### Install Frontend Dependencies
```sh
cd frontend
npm install
```

### Install Backend Dependencies
```sh
cd backend
npm install
```

### Environment Variables
Create a `.env` file with the following variables:
```env
MONGO_URL=your_mongodb_connection_string
PORT=your_preferred_port_number
```

### Run the Application
#### Start the Frontend Server
```sh
npm start
```
#### Start the Backend Server
```sh
npm run dev
```

Now, your Expense Tracker app is up and running!
