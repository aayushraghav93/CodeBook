# CodeBook

PasteApp is a simple web application for creating, saving, viewing, and managing text pastes. Built with **React**, **Vite**, **Redux Toolkit**, **Tailwind CSS**, and **React Router**, it provides a fast and modern user experience for managing snippets of text.

---

## Features

- **Create & Edit Pastes:** Add new pastes or edit existing ones.
- **View Pastes:** View the content of any paste in a dedicated view.
- **Copy to Clipboard:** Quickly copy paste content with a single click.
- **Delete Pastes:** Remove pastes you no longer need.
- **Search:** Filter pastes by title.
- **Persistent Storage:** All pastes are saved in your browser's localStorage.
- **Responsive UI:** Styled with Tailwind CSS for a clean, responsive design.
- **Notifications:** User feedback via toast notifications.

---

## Getting Started

### 1. Clone the Repository

```sh
git clone https://github.com/your-username/pasteapp.git
cd PasteApp
```

### 2. Install dependency

```sh
npm install
```
### 3. Run the Development Server

```sh

npm run dev
```

- Open http://localhost:5173 in your browser to view the app.


## 📂 Project Structure

```bash
PasteApp/
├── public/
│   └── vite.svg
├── src/
│   ├── App.jsx
│   ├── index.css
│   ├── main.jsx
│   ├── assets/
│   │   └── react.svg
│   ├── components/
│   │   ├── Home.jsx
│   │   ├── Navbar.jsx
│   │   ├── Paste.jsx
│   │   └── ViewPaste.jsx
│   ├── data/
│   │   └── Navbar.js
│   ├── redux/
│   │   ├── pasteSlice.js
│   │   └── store.js
│   └── utlis/
│       └── formatDate.js
├── index.html
├── package.json
├── tailwind.config.js
├── postcss.config.js
├── vite.config.js
└── eslint.config.js
```


# CodeBook

## 📦 Main Packages Used
- [react](https://react.dev/)
- [react-dom](https://www.npmjs.com/package/react-dom)
- [react-router-dom](https://reactrouter.com/en/main)
- [@reduxjs/toolkit](https://redux-toolkit.js.org/)
- [react-redux](https://react-redux.js.org/)
- [tailwindcss](https://tailwindcss.com/)
- [react-hot-toast](https://react-hot-toast.com/)
- [lucide-react](https://lucide.dev/)

---

## 🚀 Usage
- **Home**: Create a new paste or edit an existing one (when accessed with a `?pasteId=...` query).
- **Paste**: View all your pastes, search by title, edit, delete, or copy content.
- **ViewPaste**: View a single paste in detail by navigating to `/pastes/:id`.

---

## 🛠️ Scripts
- `npm run dev` — Start the development server.
- `npm run build` — Build for production.
- `npm run preview` — Preview the production build.
- `npm run lint` — Lint the codebase.

---