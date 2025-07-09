# Dashboard Application

A React-based dashboard that displays user profiles and comments with pagination, sorting, and search functionality.

## Features

- **Profile Screen**
  - Displays first user from API
  - Non-editable view
  - Navigation to dashboard

- **Comments Dashboard**
  - Paginated data grid (500 comments)
  - Custom pagination (no library)
  - Page size options: 10, 50, 100
  - Search by name, email, or body
  - Sort by Post ID, Name, or Email
  - State persistence on refresh

## Technologies

- React
- React Router
- Custom hooks
- LocalStorage for state persistence
- Fetch API for data
