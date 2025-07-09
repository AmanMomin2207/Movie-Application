# 🎮 Movie App

A responsive single-page movie application built using **React.js**, **React-Use**, and **Tailwind CSS**, integrated with **Appwrite** for backend services. The app allows users to browse movie data and authenticate securely.

**GitHub Repository:** [Movie App](https://github.com/AmanMomin2207/Movie-Application)

---

## 🧰 Tech Stack

* **Appwrite** — Backend as a service (Auth, Database, File Storage)
* **React.js** — Frontend UI library
* **React-Use** — React hooks library for state and lifecycle management
* **Tailwind CSS** — Utility-first styling framework
* **Vite** — Lightning-fast frontend build tool with HMR (Hot Module Replacement)

---

## 🚀 Features

* 🔐 **User Authentication** using Appwrite
* 📂 **Secure Database and File Storage** for user-generated content
* 🔍 **Search Movies** by title
* 🏆 **Browse Categories**: Trending, Popular, Top-rated
* 📈 **Responsive Design** for all screen sizes
* ⚡ **Instant Refresh & Fast Load** using Vite and React-Use

---

## 📁 Project Structure

```
Movie-Application/
├─ public/
├─ src/
│   ├─ components/
│   │   ├─ MovieCard.jsx
│   │   ├─ Search.jsx
│   │   └─ Spinner.jsx
│   ├─ App.css
│   ├─ App.jsx
│   ├─ appwrite.js
│   └─ main.jsx
│   ├─ index.css
├─ package.json
└─ README.md
```

---

## ⚙️ How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/AmanMomin2207/Movie-Application.git
cd Movie-Application
```

2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file in the root directory:

```env
VITE_APPWRITE_ENDPOINT=your_appwrite_endpoint
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_DATABASE_ID=your_database_id
VITE_APPWRITE_COLLECTION_ID=your_collection_id
VITE_APPWRITE_BUCKET_ID=your_bucket_id
```

4. Start the development server:

```bash
npm run dev
```

App runs on `http://localhost:5173` (default Vite port)

---

## 🛠️ Future Enhancements

* Add pagination and infinite scroll for movie results
* Implement user favorites and bookmarks
* Integrate movie trailers and recommendations

---

## 📩 Contact

Created by **Aman Momin** — [mominaman2207@gmail.com](mailto:mominaman2207@gmail.com)

Feel free to submit issues or suggestions!

---

Made with 🍿 by **Aman Momin**
