# Immersive

## Authors:
Phi Le, AK Nguyen, Aimen Faiz Rehman  
**Status:** Completed  
**Last Update:** Dec 10, 2024  

## Overview
Immersive is a full-stack web application for sales management, built using Angular (frontend), Node.js with Express.js (backend), and MySQL (database). It enables users to manage transactions, submit product reviews, track sales, and monitor revenue.

## Features
- User authentication (Firebase Authentication)
- Item management (create, edit, delete listings)
- Search & filtering by title and category
- Transaction tracking and net sales revenue
- Review system for product feedback
- Data analysis via Tableau

## Tech Stack
- **Frontend:** Angular
- **Backend:** Node.js, Express.js
- **Database:** MySQL
- **Authentication:** Firebase
- **Visualization:** Tableau

## Database Schema (Key Tables)
- **User:** Stores user details.
- **Item:** Stores product information.
- **Review:** Stores product reviews.
- **Transaction:** Records sales data.
- **Category:** Categorizes items.

## Installation & Setup
### Prerequisites:
- Install [Node.js](https://nodejs.org/en)
- Install [MySQL](https://dev.mysql.com/downloads/mysql/)

### Steps:
1. Clone the repository:
   ```sh
   git clone https://github.com/Phizzle32/immersive.git
   cd immersive
   ```
2. Install dependencies:
   ```sh
   npm run install-all
   ```
3. Configure `.env` file:
   ```sh
   MYSQL_HOST='localhost'
   MYSQL_USER='root'
   MYSQL_PASSWORD=''
   MYSQL_DATABASE='immersive'
   ```
4. Start the backend:
   ```sh
   npm run dev
   ```
5. Start the frontend:
   ```sh
   npm start
   ```
6. Open in browser:
   ```
   http://localhost:4200/
   ```

## API Endpoints (Examples)
- **Get Items:** `GET /api/item`
- **Add Review:** `POST /api/review/create`
- **Perform Transaction:** `POST /api/transaction/create`

## Conclusion
Immersive streamlines e-commerce management with an intuitive interface and data-driven insights.

