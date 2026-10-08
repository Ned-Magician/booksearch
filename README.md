# Reading List — React CRUD Demo

A small React application for managing a reading list locally in the browser session.

**[Live Demo](https://booksearch-vert.vercel.app/)** · **[Source Code](https://github.com/Ned-Magician/booksearch)**

## Tech Stack

- React 18
- JavaScript
- CSS
- Create React App

## Features

- Add books to a reading list
- Display the current list
- Edit a book title
- Remove a book
- Organize the interface into reusable React components

## How It Works

The `App` component holds the list in React state and passes callbacks to components for creating, editing, and deleting books.

**Scope:** This is a client-side CRUD/state-management exercise. The current public code does **not** include external book search, REST API integration, a backend database, or persistent storage; items reset when the page is reloaded.

## Run Locally

```bash
npm install
npm start
```

The repository name is `booksearch`, but **Reading List** more accurately describes the current app.
