# Experiment 3.2 – Library Management UI

## Aim
To build a Library Management System with book search, add, and remove functionality using React.

---

## Objective
- Create a responsive book listing interface
- Implement search functionality to find books quickly
- Add a form to insert new book entries
- Enable removal of existing books
- Manage application state using React Hooks

---

## Hardware / Software Requirements

### Software
- Node.js 18+
- React 18+
- Visual Studio Code
- npm or yarn

### Hardware
- Intel i5 or higher processor
- Minimum 8 GB RAM

---

## About the Program
This project demonstrates basic CRUD operations in React:

- **Create** → Add new books
- **Read** → Display books in a list
- **Search** → Filter books using search functionality
- **Delete** → Remove books from the library

The application uses:
- `useState()` for managing books and form data
- Controlled form inputs for adding new books
- Dynamic rendering of book cards/list items
- Responsive CSS for mobile and desktop screens

---

## Features
- Responsive user interface
- Search books by title or author
- Add a new book with details
- Remove books from the list
- Real-time updates without page refresh

---

## Folder Structure

```text
library-management-ui/
│
├── public/
├── src/
│   ├── components/
│   │   ├── BookList.jsx
│   │   ├── BookCard.jsx
│   │   ├── SearchBar.jsx
│   │   └── AddBookForm.jsx
│   │
│   ├── App.jsx
│   ├── App.css
│   └── main.jsx
│
├── package.json
└── README.md
