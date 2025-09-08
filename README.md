# 🍳 Recipe Finder

A modern web app for discovering, saving, and sharing recipes. Built with **HTML, CSS, and vanilla JavaScript**, it uses [TheMealDB API](https://www.themealdb.com/api.php) to provide a seamless recipe search experience.

---

## ✨ Features

### 🔍 Recipe Search
- Search by **keyword** (e.g., *pasta, chicken, biryani*).
- Filter recipes by:
  - **Category** (e.g., Dessert, Seafood)
  - **Cuisine / Area** (e.g., Italian, Indian)
  - **Ingredient** (e.g., tomato, cheese)

### 📑 Results & Pagination
- Recipes displayed as **grid cards** with images, title, category, and cuisine.
- **Pagination controls** for browsing large result sets.
- Status messages (e.g., *Searching…*, *No recipes found*) guide the user.

### ❤️ Favorites
- Save favorite recipes with one click.
- Stored in **localStorage** for persistence.
- Manage favorites (open or remove) in a dedicated sidebar.

### 📝 Recipe Details
- Click **View** to open a **modal** with:
  - Full-size recipe image
  - Title, category, and cuisine
  - Ingredients list with measurements
  - Step-by-step instructions
  - Links to **source** and **YouTube tutorials** (if available)

### 🌗 Theme Toggle
- **Dark mode** (default) and **light mode** supported.
- User’s choice is saved in **localStorage**.

### 🔗 Shareable Links
- Generate a **URL with your search & filters encoded**.
- One-click copy to clipboard for easy sharing.

### 📱 Responsive Design
- Works across desktop, tablet, and mobile devices.
- Uses CSS Grid and media queries for a clean, adaptive layout.

---

## 🛠️ Tech Stack
- **HTML5**
- **CSS3 (Custom properties & responsive grid)**
- **Vanilla JavaScript (ES6+)**
- **TheMealDB API**

---

## 🚀 How It Works
1. Enter a recipe name or apply filters.
2. Browse results with pagination.
3. Save your favorites for later.
4. Share search results using the link generator.
5. Switch between light and dark themes at any time.

---

## 📌 Future Enhancements (Ideas)
- Advanced sorting (by popularity, prep time, etc.)
- Offline mode with service workers
- User accounts for syncing favorites across devices

---


