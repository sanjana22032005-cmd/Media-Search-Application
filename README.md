# Media Search Application

A modern **React + Redux Toolkit** web application that enables users to search for **Photos, Videos, and GIFs** from multiple media APIs. Users can save their favorite media to a personal collection, manage saved items, and enjoy a clean, responsive interface.

---

## Features

- Search media using keywords
- Browse Photos
- Browse Videos
- Browse GIFs
- Save media to a personal collection
- Remove individual items from the collection
- Clear the entire collection
- Collection persistence using Local Storage
- Toast notifications for save and remove actions
- Responsive UI built with Tailwind CSS

---

## Tech Stack

- React.js
- Vite
- Redux Toolkit
- React Redux
- React Router DOM
- Axios
- React Toastify
- Tailwind CSS
- JavaScript (ES6+)

---

## Project Structure

```text
src
│
├── api
│   └── mediaApi.js
│
├── components
│   ├── Navbar.jsx
│   ├── SearchBar.jsx
│   ├── Tabs.jsx
│   ├── ResultGrid.jsx
│   ├── ResultCard.jsx
│   └── CollectionCard.jsx
│
├── pages
│   ├── HomePage.jsx
│   └── CollectionPage.jsx
│
├── redux
│   ├── store.js
│   └── features
│       ├── searchSlice.js
│       └── collectionSlice.js
│
├── App.jsx
├── main.jsx
└── index.css
```

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git
```

### 2. Navigate to the project directory

```bash
cd YOUR_REPOSITORY_NAME
```

### 3. Install dependencies

```bash
npm install
```

### 4. Install required packages (if setting up manually)

```bash
npm install react-router-dom
npm install @reduxjs/toolkit react-redux
npm install axios
npm install react-toastify
npm install tailwindcss @tailwindcss/vite
```

> **Note:** If you cloned this repository, running `npm install` is sufficient because all required packages are already listed in `package.json`.

---

## Environment Variables

Create a `.env` file in the project root and add your API keys:

```env
VITE_UNSPLASH_ACCESS_KEY=YOUR_UNSPLASH_API_KEY
VITE_PEXELS_API_KEY=YOUR_PEXELS_API_KEY
VITE_TENOR_API_KEY=YOUR_TENOR_API_KEY
```

---

## Running the Application

Start the development server:

```bash
npm run dev
```

Open your browser and visit:

```text
http://localhost:5173
```

---

## Dependencies

| Package | Purpose |
|----------|---------|
| React | Frontend library |
| Vite | Build tool and development server |
| React Router DOM | Client-side routing |
| Redux Toolkit | Global state management |
| React Redux | Connect React with Redux |
| Axios | API requests |
| React Toastify | Toast notifications |
| Tailwind CSS | Styling |

---

## What Users Can Do

- Search for media using any keyword.
- Switch between **Photos**, **Videos**, and **GIFs** using dedicated tabs.
- View high-quality search results fetched from multiple APIs.
- Open the original media source in a new browser tab.
- Save favorite media items to a personal collection.
- View all saved items on the Collection page.
- Remove individual items from the collection.
- Clear the entire saved collection with a single click.
- Receive toast notifications for successful save and remove actions.
- Continue accessing saved items after refreshing the page through Local Storage persistence.

---

## APIs Used

- Unsplash API – Photo Search
- Pexels API – Video Search
- Tenor API – GIF Search

---

## Author

**Sanjana Kumari**

Third-year B.Tech Computer Science and Engineering student at IIIT Guwahati with an interest in Full Stack Development, Data Structures & Algorithms, and building scalable web applications. Passionate about learning modern technologies and developing impactful software projects.

GitHub: https://github.com/sanjana22032005-cmd
LinkedIn: https://www.linkedin.com/in/sanjana-kumari-5585b4340/


---

## License

This project is developed for educational and learning purposes.
