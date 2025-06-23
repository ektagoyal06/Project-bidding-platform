# Project-bidding-platform
Created a  project bidding platform using MYSQL. A platform where clients can post projects and freelancers can place bids to undertake those projects
# DevifyX Assignment: Project Bidding Platform

## 📌 Overview

This project implements a **MySQL-only backend** for a freelance project bidding platform. Clients can post projects, and freelancers can bid to work on them. The schema supports full lifecycle management of projects, bidding, user reviews, messaging (schema only), notifications, and analytics.

## 🧩 Objectives

- Design and implement a **normalized, scalable, and robust relational database schema**.
- Implement core business logic using **MySQL DDL, DML, views, triggers, stored procedures, and functions**.
- Provide **sample data** for testing and validation.
- Deliver at least **3 complex SQL queries** to extract useful insights from the system.

## 🚀 Core Features

1. **User Management**  
   - Two roles: **Client** and **Freelancer**.  
   - Role-based design using separate role table.

2. **Project Posting**  
   - Clients can post projects with title, description, budget, deadline, and required skills.

3. **Bidding System**  
   - Freelancers can place bids specifying their proposed price and timeline.
   - Each project can receive multiple bids.

4. **Bid History & Status**  
   - Bids tracked with status: `Pending`, `Accepted`, `Rejected`.

5. **Project Assignment**  
   - Clients accept bids to assign projects to freelancers.
   - Project status updated on assignment.

6. **Project Status Tracking**  
   - Statuses: `Open`, `In Progress`, `Completed`, `Cancelled`.

7. **Review & Rating**  
   - After project completion, clients and freelancers rate and review each other.

8. **Skill Management**  
   - Freelancers and projects can be tagged with multiple skills.

## ✨ Bonus Features (Schema only)

- **Messaging System** between clients and freelancers.
- **Notification System** for events like bid placed or accepted.
- **File Attachments** for projects and bids.
- **Analytics Views**:
  - Top freelancers by average rating.
  - Most active clients.
  - Average bid per project.

## 🛠️ Technical Stack

- **Database**: MySQL 8+
- **Normalization**: 3NF and higher.
- **Techniques Used**:
  - Stored Procedures
  - Views
  - Triggers
  - Functions
  - Foreign Keys and Constraints
  - ENUM and Check constraints
  - Sample Data Insertions

## 📊 Complex Queries

At least 3 complex SQL queries are included:
- Top freelancers by average rating
- Projects with the most bids
- Average bid amount per project

---


