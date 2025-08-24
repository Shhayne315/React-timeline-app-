 Summer Holiday Trip Timeline ☀️ (Accessible React Edition)

Welcome to the project page for our interactive Summer Holiday Trip Timeline! This isn't just a static webpage; it's a dynamic and accessible single-page application built with modern web technologies like React and TypeScript.

The goal of this project is to create a beautiful, user-friendly, and inclusive experience for everyone, ensuring that people with disabilities can navigate and enjoy the timeline just as easily as anyone else.

---

### ✨ Key Features

* **Component-Based UI**: Built with React, the application is broken down into small, reusable components (`Header`, `Timeline`, `EventMarker`, etc.), making the code clean and easy to maintain.
* **Dynamic Data Loading**: The trip's event data is fetched asynchronously when the app loads, simulating how a real-world application would load data from a server.
* **Interactive Modal Views**: Clicking on any event on the timeline opens a detailed pop-up (a modal) with more information and a larger image.
* **Built with TypeScript**: The entire application is written in TypeScript, which adds static typing to our code. This helps catch potential bugs during development and ensures our data structures are consistent.
* **Modern State Management**: We use React Hooks (`useState`, `useEffect`, `useRef`) for clean and efficient state management, handling everything from the event data to the visibility of the modal.

---

### ♿ Accessibility First: Built for Everyone

Making this app accessible was a top priority. Here’s how we made sure it’s usable by people with disabilities:

* **Full Keyboard Navigation**:
    * You can navigate through all interactive elements, including every timeline event, using the **Tab** key.
    * Open the modal for a selected event by pressing **Enter** or **Space**.
    * Close the modal at any time by pressing the **Escape** key.
* **Smart Focus Management**:
    * When a modal opens, keyboard focus is **trapped inside it**, so you can't accidentally navigate to the page behind it.
    * When the modal closes, focus is **instantly returned** to the button that opened it, so you never lose your place.
* **Screen Reader Friendly**:
    * We use semantic HTML (like the `<dialog>` element for the modal) and ARIA roles (`role="list"`) to give the page a clear structure that screen readers can understand and announce correctly.
    * All images have descriptive `alt` text.
* **High-Contrast Design**: The color scheme was chosen to meet WCAG AA contrast ratio guidelines, ensuring the text is legible for users with low vision.

---

### 🛠️ The Technology Behind the Timeline

Here’s a breakdown of the tools and concepts that bring this timeline to life:

* **React**
    * **Description:** The foundation of our user interface. React allows us to build the UI out of isolated, reusable pieces called **components**. This structure makes our code cleaner and easier to manage, and leads to a fast, responsive user experience.

* **TypeScript**
    * **Description:** Adds a layer of safety and predictability to our JavaScript. By defining the "shape" of our data (like what a `TimelineEvent` must contain), TypeScript helps us catch common errors before the code even runs, leading to more robust and reliable code.

* **Vite**
    * **Description:** Our modern front-end build tool. It provides a blazing-fast development server for coding and testing. For the final product, Vite bundles our code into optimized files that are small and efficient, ensuring the app loads quickly.

* **React Hooks**
    * **Description:** Special functions that let us "hook into" React's state and lifecycle features. We use `useState` to manage what's happening on screen (like the list of events or which modal is open) and `useEffect` to perform actions like fetching data when the app starts.

* **CSS**
    * **Description:** Used for all visual styling. We use modern CSS features like variables, which make it easy to manage the color scheme and maintain a consistent design throughout the application.

---

### 🚀 How to Run This Project Locally

Want to get this running on your own machine? Just follow these simple steps:

1.  **Clone the Repository**: Download the code to your computer.
2.  **Install Dependencies**: Open your terminal in the project folder and run:
    ```bash
    npm install
    ```
3.  **Start the Development Server**: Once the installation is complete, run:
    ```bash
    npm run dev
    ```
4.  **View in Browser**: Open your web browser and go to the local address provided in your terminal (usually `http://localhost:5173`). You should see the timeline app up and running!
