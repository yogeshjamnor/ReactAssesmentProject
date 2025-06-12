# React Developer Portfolio Components

This project includes a set of professional, responsive React components built with Bootstrap 5 and Bootstrap Icons. These components are designed to be part of a personal portfolio or admin dashboard.

---

## 📁 Components Overview

### 🔹 1. `About.jsx` – Developer Profile Section

A responsive personal introduction section for React portfolios.

#### Features:
- Displays profile image, name, location, email, and tech stack
- Uses Bootstrap grid and icons
- Buttons for contact and navigation

#### Tech:
- React, Bootstrap, Bootstrap Icons

---

### 🔹 2. `Team.jsx` – Team/Employee Listing with Modal

Displays a grid of employees/influencers with icons and performance scores. Clicking a card opens a modal with more details.

#### Features:
- Card layout with Bootstrap grid
- Uses Bootstrap Icons instead of images
- Modal popup for detailed employee info (email, department, score)

#### Sample Data Includes:
- Name, handle, email, score, department, and icon

---

### 🔹 3. `Projects.jsx` – Project Showcase with Modal

Displays project cards with screenshots and brief descriptions. Clicking a card opens a detailed modal.

#### Features:
- Responsive grid of cards (image, title, short desc)
- Modal with:
  - Full description
  - Key features list
  - Tech stack badges
- Uses `useState` for state management

#### Projects:
- **AgroFriend** – Farming assistant using React + Firebase
- **Payroll Dashboard** – HR & attendance management system
- **Quiz App** – Responsive quiz app with Realtime DB support

---

## 💻 Tech Stack

- React (Functional Components with `useState`)
- Bootstrap 5
- Bootstrap Icons

---

## 📷 Screenshots (Suggested)

- About Section with Profile
- Team Grid with Modal
- Projects Cards with Modal Open

*Add screenshots in your `README` repo to visually showcase components.*

---

## 📂 File Structure

```bash
src/
│
├── components/
│   ├── About.jsx
│   ├── Team.jsx
│   └── Projects.jsx
│
├── img/
│   ├── agrofriend.png
│   ├── payroll.png
│   ├── quiz.png
│   └── yogesh.jpg
