# React + Vite
# React Axios CRUD (GET, POST, PUT, DELETE)

A simple React project to practice CRUD operations using **Axios** and the **JSONPlaceholder API**.

This project covers:
- Fetching posts (GET)
- Adding a new post (POST)
- Editing an existing post (PUT)
- Deleting a post (DELETE)

---

## 🚀 Features

- View list of posts from API
- Add new post using a form
- Edit post (auto-fills form with existing values)
- Delete post from UI instantly
- Clean Axios API service layer (`PostApi.jsx`)
- React Hooks (`useState`, `useEffect`) used for state management

---

## 🛠 Tech Stack

- React (Vite)
- Axios
- JSONPlaceholder API
- CSS

---

# 📂 Project Structure
# src/
├── api/
│ └── PostApi.jsx
├── components/
│ ├── Form.jsx
│ └── Posts.jsx
├── App.jsx
├── App.css
├── index.css
└── main.jsx




---

## 🔗 API Used

This project uses the free fake REST API:

- https://jsonplaceholder.typicode.com/posts

⚠️ Note: JSONPlaceholder does not permanently store changes.
So POST/PUT/DELETE will work in response, but after refresh it resets.

---

## ⚙️ Installation & Run

Clone the repo and install dependencies:


# npm install
# npm run dev


📌 Learning Outcome
This project is mainly built to understand:
Axios instance + baseURL
API calls separation (service layer)
React form handling (controlled inputs)
Real-time UI update after CRUD actions
Handling Add & Edit mode in a single form

