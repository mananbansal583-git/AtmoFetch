# AtmoFetch 🌤️

A modern, responsive weather application built with Vanilla JavaScript, featuring a dynamic teal and green animated UI. AtmoFetch utilizes the OpenWeatherMap API to provide real-time weather data with robust error handling and a custom search fallback logic.

**[🔴 Live Preview](https://mananbansal583-git.github.io/AtmoFetch/)** | **[📂 Source Code](https://github.com/mananbansal583-git/AtmoFetch)**

---

## ✨ Features

* **Real-Time Data:** Fetches current temperature, humidity, wind speed, and weather conditions.
* **Smart Search Logic:** Implements a two-tier API fetching system. It handles global city name collisions by intelligently falling back to a worldwide search if the initial localized query fails.
* **Dynamic UI:** Features a custom, pure CSS animated gradient background and floating icons that update dynamically based on the current weather state.
* **Graceful Error Handling:** Provides clear, styled user feedback when a city is not found instead of breaking the UI.
* **Responsive Design:** Fully centered and optimized for both desktop and mobile viewing.

---

## 🛠️ Tech Stack

* **HTML5:** Semantic structure.
* **CSS3:** Flexbox, Keyframe animations, Box Shadows, and custom UI styling.
* **JavaScript (ES6+):** Async/Await, Fetch API, DOM manipulation, and custom algorithmic logic.
* **API:** OpenWeatherMap API.

---

## 🧠 What I Learned

Building this project was a deep dive into core web development and asynchronous programming. Key takeaways include:

* **Asynchronous JavaScript:** Mastering `async/await` and the `fetch` API to request and parse JSON data without freezing the user interface.
* **Edge Case Management:** Writing conditional logic to handle API errors (like `404 Not Found` status codes) and executing smart retry logic for accurate city searches.
* **Separation of Concerns:** Keeping the front-end architecture clean by strictly separating styling rules in CSS from the functional logic in JavaScript.
* **Modern CSS Techniques:** Implementing glass-like aesthetics, background gradient animations, and smooth component transitions.

---

## 💻 Local Installation

To run this project locally on your machine:

1. Clone the repository:
```bash
   git clone [https://github.com/mananbansal583-git/AtmoFetch.git](https://github.com/mananbansal583-git/AtmoFetch.git)
   ```

2. Navigate to the project directory:
```bash
   cd AtmoFetch
   ```

3. Open `index.html` in your browser, or use a development server like the Live Server extension in VS Code.

*(Note: If you are cloning this project, you will need to generate your own free API key from OpenWeatherMap and replace it in the `script.js` file.)*

---

## 👨‍💻 Author

**Manan Bansal**
* GitHub: [@mananbansal583-git](https://github.com/mananbansal583-git)

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
