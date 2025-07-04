## 🚀 30-Day Coding Challenge: Day 25

This project is the twenty-fifth entry in my 30-day coding challenge. Today's goal was to build a highly interactive UI for a movie seat booking system. This project is a fantastic exercise in managing complex state, persisting data with `localStorage`, and creating an engaging, visually appealing user experience.

### 📖 Project Overview

This is a responsive and interactive movie seat booking interface built with React. Users can select a movie from a dropdown menu, which updates the ticket price. They can then click on available seats in the theater layout to select them. The application calculates the total number of selected seats and the corresponding price in real-time. All selections (both the chosen movie and the selected seats) are automatically saved to the browser's `localStorage`, so the user's booking is preserved even if they refresh the page.

### ✨ Live Demo & Screenshot

Below is a screenshot of the application's interface.
![Jul-03-2025 22-26-00](https://github.com/user-attachments/assets/45259501-56ef-4cca-b3ef-1818e22572ed)


### 🌟 Key Features

* **Interactive Seating Chart:** Users can click on available seats to select or deselect them. Occupied seats are disabled.
* **Movie Selection:** A dropdown menu allows users to choose from different movies, each with a different ticket price.
* **Real-Time Calculation:** The total number of selected seats and the total price are calculated and displayed instantly as the user makes selections.
* **Persistent State:** Uses the `useEffect` hook to automatically save the selected movie and seats to `localStorage`, so the user's progress is not lost on page reload.
* **Cinematic UI:** A dark-themed UI with a 3D perspective effect on the "screen" to create an immersive movie theater feel.
* **Component-Based Architecture:** The UI is broken down into logical components (`MovieSelect`, `Seat`, `Legend`) for a clean and maintainable codebase.

### 💻 Technologies Used

This project was built using a modern, lightweight React setup.

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Babel](https://img.shields.io/badge/Babel-%23F9DC3e.svg?style=for-the-badge&logo=babel&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

* **React:** The core library for building the user interface and managing state.
* **ReactDOM:** Used to render the React component into the browser's DOM.
* **Babel:** Used as a transpiler to convert JSX into standard JavaScript.
* **Tailwind CSS:** For all styling and layout.

### 🛠️ How to Run Locally

This project is set up to be extremely simple to run, with no build process required:

1.  **Clone the repository (or download the code):**
    ```bash
    git clone https://github.com/timothy-agboada/react-movie-seat-booking.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd react-movie-seat-booking
    ```
3.  **Open the `index.html` file in your web browser.** The CDN links will handle loading all necessary libraries automatically.

### 🎯 Learning Objectives

This project was a practical exercise in several important React concepts:

* **Persisting State with `useEffect`:** Mastering the use of two `useEffect` hooks—one to load data on mount and another to save data whenever state changes.
* **Complex State Interaction:** Managing multiple related pieces of state (`seats`, `selectedSeats`, `selectedMovie`) that work together to create the final UI.
* **Derived State:** Reinforcing the concept of calculating values (`totalPrice`) from the base state on every render.
* **Handling User Interaction on a Grid:** Writing logic to manage selections within a grid of items.
* **Styling and Theming:** Creating an immersive and visually appealing UI with CSS perspective and a consistent dark theme.
