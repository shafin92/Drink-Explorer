# 🍸 Drink Explorer (Cocktail Finder & Group Builder)

A responsive single-page web application built with **HTML5, Tailwind CSS, and Vanilla JavaScript** that fetches data from [TheCocktailDB API](https://www.thecocktaildb.com/api.php). This project allows users to explore various cocktails, search by name, view detailed information, and manage a custom group with a restriction limit.

---

## 🚀 Live Demo
* **Live Site:** [Add your deployed link here, e.g., Netlify / GitHub Pages]

---

## ✨ Features & Requirements Implemented

1. **Default Drink Cards (Q1):** 
   - Automatically loads and displays the first 10 cocktail cards upon initial page load.
2. **Search Functionality (Q2):** 
   - Fully functional search bar and search button to look up any cocktail by name. 
   - Displays a *"No drinks found"* warning message if the search yields no results.
3. **Drink Card UI (Q3):** 
   - Displays the **Drink Name**, **Category**, instructions trimmed down to **15 characters**, and action buttons ("Add to Group" & "Details").
4. **Responsive 2-Column Layout (Q4):** 
   - Designed using a grid layout where the primary section shows the drink feed, and the sidebar acts as the group selection panel.
5. **Group Management & Counter (Q5):** 
   - Clicking the "Add to Group" button dynamically adds the cocktail to the sidebar selection list and increments the live drink counter badge.
6. **Group Limit Validation (Q6):** 
   - Implements a strict restriction preventing users from adding more than **7 drinks** to a group, triggering an alert message if exceeded.
7. **Detailed Modal View (Q7):** 
   - Clicking the "Details" button opens a popup modal showcasing at least **5 distinct pieces of information** about the cocktail (Category, Alcoholic Type, Glass Type, Main Ingredient, and Instructions).

---

## 🛠️ Built With

* **HTML5** - Structure
* **Tailwind CSS (CDN)** - Styling & Responsive Layout
* **Vanilla JavaScript (ES6)** - Application Logic & API Integration
* **TheCocktailDB API** - Data Source

---

## 📦 Local Installation & Setup

To run this project locally on your machine, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/shafin92/Drink-Explorer.git](https://github.com/shafin92/Drink-Explorer.git)
