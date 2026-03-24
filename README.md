# 🔍 Job Search Engine (AppDev_Lab8) 🚀

### 📝 About
This project is a functional, lightweight web application built with **PHP** and **Tailwind CSS**. It serves as a search interface that allows users to browse through a collection of job listings and filter them specifically by location. The application demonstrates core server-side principles, such as handling `GET` requests from a form and using conditional logic to dynamically render content based on user input.

---

### 📂 Project Structure

* **`main.php`** 🏠: The entry point of the application featuring a centered search form for user input.
* **`result.php`** 📊: The logic engine that processes search queries against a data array of job listings, including titles, salaries, and tags.
* **`README.md`** 📖: Documentation providing an overview and instructions for the project.

---

### ✨ Key Features

* **📍 Dynamic Filtering**: 
    * Displays all available jobs by default if the search bar is left empty.
    * Filters the list to show exact matches when a valid location is entered.
    * If a location is not found, the system intelligently reverts to showing the full list.
* **🎨 Modern UI**: Uses **Tailwind CSS** to create a professional, responsive layout with clean cards and a blue-themed header.
* **🛠️ Data Management**: Handles structured information such as **Salary**, **Location**, and **Tags** for each listing.

---

### 🚀 How to Run

1.  **Environment** 💻: Ensure you have a local PHP server environment (like XAMPP, WAMP, or MAMP) installed.
2.  **Setup** 📁: Place the project files into your server's root directory (e.g., `htdocs/AppDev_Lab8/`).
3.  **Launch** 🌐: Open your web browser and navigate to `http://localhost/AppDev_Lab8/main.php`.
4.  **Search** ⌨️: Enter a city like **"San Francisco"** or **"New York"** to see the filter in action!

---

**Developed for AppDev_Lab8** 🎓
