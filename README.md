# ReBite: A Smart Marketplace for Surplus Food Recovery

ReBite is an academic project prototype developed for **CSE 495: IT and Project Management & Entrepreneurship** at **East West University**. The project explores a practical digital marketplace for recovering safe surplus food by connecting customers, restaurant partners, and platform administrators in one coordinated system.

> **Project theme:** Rescuing Food, Empowering Communities, Creating Sustainable Value.

## Academic Information

| Item | Details |
|---|---|
| Institution | East West University |
| Department | Department of Computer Science and Engineering |
| Course Code | CSE 495 |
| Course Title | IT and Project Management & Entrepreneurship |
| Semester | Summer 2026 |
| Section | 05 |
| Faculty | Proma Chowdhury, Lecturer |

## Project Overview

A significant amount of edible food can remain unsold at the end of a restaurant's selling period. ReBite is designed to help restaurants recover value from that surplus while giving customers access to discounted food through a simple reservation and pickup process.

The prototype focuses on three connected user areas:

- **Customer Hub** — discover, review, reserve, pay for, and collect surplus food.
- **Restaurant Hub** — publish surplus items, manage orders and listings, and review performance analytics.
- **Admin Dashboard** — monitor platform activity, restaurants, orders, donations, analytics, reports, and revenue-related information.

## Key Problems Addressed

The project was refined around several practical concerns identified during course feedback:

1. **Restaurant-side loss perception** — discounted surplus sales should be viewed as recovered value instead of only as a price reduction.
2. **Customer trust in surplus food** — the prototype communicates freshness and verification information through indicators such as **Made Today** and **Hygiene Verified**.
3. **Platform sustainability** — the admin side includes a revenue view to represent platform fees, subscriptions, featured listings, payouts, and overall revenue tracking.

## Prototype Features

### Customer Hub

- Onboarding and login flow with basic empty-field validation
- Demo login credentials for quick testing
- Nearby surplus food discovery
- Search and category navigation
- Freshness and hygiene indicators
- Food details, discount, pricing, rating, and pickup information
- Reservation quantity selection
- bKash, Nagad, and Card payment-option interface
- Order confirmation with pickup QR representation
- Home, Search, Orders, Favorites, and Profile navigation

### Restaurant Hub

- Restaurant dashboard with sales, orders, food-saved, and listing summaries
- Order tracking
- Add surplus food listing
- Manage active and sold-out items
- Weekly sales analytics
- Food saved, order count, average order value, and sell-through indicators
- Order-mix visualization
- Performance insights for pickup success, repeat customers, and sold-before-closing performance

### Admin Dashboard

- Platform overview
- User management
- Restaurant management
- Order monitoring
- Listing management
- NGO donation overview
- Platform analytics
- Revenue section with:
  - Gross Order Value
  - Platform Fees
  - Subscription Revenue
  - Featured Listings
  - Restaurant Payouts
  - Net Platform Revenue
- Reports and settings

## Additional Concept Features

The prototype also presents several broader ReBite concepts that support the long-term project vision:

- AI Waste Prediction
- Dynamic Discounts
- NGO Donations
- Student Saver
- Carbon Tracking
- Secure and trusted pickup experience

## Technology Used

- **React 18.3.1**
- **JavaScript / JSX**
- **HTML5**
- **CSS3**
- **Babel Standalone**
- **Poppins** typography
- Frontend state and mock data for interactive prototype behavior

## Running the Prototype

This repository is prepared as a browser-based prototype and does not require a separate build process.

1. Clone or download the repository.
2. Open `index.html` in a modern web browser.
3. Start from the ReBite role-selection screen.
4. Select **Customer Hub**, **Restaurant Hub**, or **Admin Dashboard** to explore the corresponding workflow.

### Demo Login

```text
Email: demo@rebite.com
Password: demo123
```

The login form requires both fields to contain a value before continuing.

## Prototype Scope

This repository represents the **interactive frontend prototype** prepared for academic demonstration. The current version uses mock data and simulated workflows. Production-level backend services such as real authentication, persistent database storage, live payment processing, production QR verification, and deployed AI prediction are outside the scope of this prototype version.

## Team Members

| Name | Student ID |
|---|---|
| Shawna Akter | 2023-1-60-071 |
| Tabassum Nahar Yeah | 2023-1-60-068 |
| Ariana Ziauddin | 2023-1-60-187 |
| Tasnia Taher Esha | 2023-1-60-173 |
| Mahfuz Uddin Ahmed | 2023-1-60-207 |

## Course Project Note

ReBite was developed as part of the coursework for **CSE 495: IT and Project Management & Entrepreneurship**. The project evolved through proposal development, problem refinement, work breakdown planning, cost analysis, faculty feedback, and iterative prototype improvement.

---

**ReBite — turning surplus food into value instead of waste.**
