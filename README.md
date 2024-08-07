Project Overview
This Auction Site is a full-stack web application that allows users to participate in an online auction system. Users can sign up, log in, list auction items, place bids, and manage their accounts through a user-friendly interface.

Features
User Authentication: Secure login and signup functionalities.
Auction Item Management: Users can create, view, update, and delete auction items.
Bidding Functionality: Users can place bids on items and view the bid history.
Technical Stack
Frontend: React.js
Backend: Node.js with Express
Database: MySQL
Authentication: JWT for secure user authentication
Documentation: Swagger for API documentation
Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

Prerequisites
What you need to install the software:

Node.js
NPM (Node Package Manager)
MySQL Server

Installing
A step by step series of examples that tell you how to get a development environment running.

Setting up the Backend
Clone the repository to your local machine:

git clone https://github.com/ishaan131nagal/Bidding-Site
Navigate into the project directory:

cd auction-site
Install the necessary packages:

Copy code
npm install
Set up your MySQL database:

Create a database named auction
Import the provided SQL script to set up the tables
Configure your environment variables:

Rename .env.example to .env
Update the database credentials and any other configurations
Start the server:

Copy code
npm start
Setting up the Frontend
Navigate to the frontend directory:
cd frontend
Install dependencies:
npm install
Start the React application:
npm start
The application should now be running on http://localhost:3000.
