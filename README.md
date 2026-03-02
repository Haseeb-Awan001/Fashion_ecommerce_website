# Fashion_ecommerce_website
E-Commerce Website System
--------------------- Overview

This project is a Full-Stack E-Commerce Web Application developed as a Software Engineering project.
The system allows users to browse products, search and filter items, add products to cart or wishlist, place orders, track shipments, and submit reviews.

It also includes an Admin Panel for managing products, categories, discounts, users, and orders.

------------------------- Objectives

Build a scalable e-commerce platform

Implement complete database design (ERD)

Apply system architecture principles

Practice GitHub workflow

Demonstrate full-stack development skills

---------------- Features
------------------ User Features

User Registration & Login

Profile Management (Country & City included)

Browse Products

Search & Filter Products

Add to Cart

Wishlist System

Product Reviews & Ratings

Order Tracking (Tracking Number)

Notification System

Customer Support Ticket System

-------------------------- Product Features

Categories & Subcategories

New Arrivals

Trending Products

Discount / On Sale Products

Product Images

Stock Management

--------------------- Cart & Order Management

Add / Remove Products

Update Quantity

Checkout System

Order ID Generation

Shipping Details

Payment Status

Order Status Tracking

------------------------ Notification System

Order Confirmation

Shipping Updates

Discount Alerts

In-App Notification Panel

--------------------- Customer Support

Create Support Ticket

Admin Reply System

Ticket Status (Open / Closed)

------------------------ Admin Panel

Manage Users

Manage Products

Manage Categories

Manage Discounts

Manage Orders

View Reports

------------------------- System Architecture

The system follows a 3-Tier Architecture:

1. Presentation Layer (Frontend)
2. Application Layer (Backend API)
3. Data Layer (Database)

Frontend communicates with backend through REST APIs.
Backend handles business logic and interacts with the database.

--------------------------- Database Design

Main Entities:

Users

Products

Categories

Subcategories

Orders

Order Items

Reviews

Wishlist

Notifications

Support Tickets

Discounts

Shipping Details

All relationships are defined using Primary Keys and Foreign Keys.

----------------------------- Technologies Used
Frontend

HTML

CSS

JavaScript

React (Optional)

-------------------Backend

Node.js

Express.js

Database

MySQL

Tools

Git

GitHub

Postman

VS Code

--------------------------------- Project Structure
Ecommerce-Website/

-------- frontend/
 components/
 pages/
assets/

-------- backend/
 controllers/
 routes/
 models/
config/

---------- database/
 schema.sql

-------------docs/
 ERD.png
 Architecture.png

------------ TODO.md
 README.md
----------------------------- Installation & Setup
Step 1: Clone Repository
git clone <your-repository-link>
Step 2: Install Dependencies
npm install
Step 3: Run Backend
npm start
Step 4: Run Frontend
npm run dev
