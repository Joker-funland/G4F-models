# G4F Model Explorer

A sleek, modern web interface to browse and explore models available through the **G4F.dev JavaScript client API**.

---

## About This Project

This tool provides a user-friendly way to see which models are currently available via the `g4f.dev/dist/js/client.js` library. It directly queries the official `/models` endpoint and displays the results in a clean, interactive grid.

**Important Note:** The models listed here are specific to the JavaScript client's API endpoint. The availability might differ from the models accessible through the G4F Python package.

## Features

-   **Live Data:** Fetches the model list directly from the G4F.dev API in real-time.
-   **Modern UI:** A clean, responsive, and aesthetically pleasing interface with a dark theme and glowing effects.
-   **One-Click Copy:** Easily copy any model ID to your clipboard with a single click.
-   **Zero Dependencies:** Built with pure HTML, CSS, and vanilla JavaScript (ES Modules). No build tools or frameworks needed.
-   **Error Handling:** Displays user-friendly messages if the API fails or returns no models.
-   **Sorted & Searchable:** Models are sorted alphabetically for easy browsing.

## How to Use
 **Locally:**
 
    1-   Copy or download `Models.html`
    
    2-   Open the `Models.html` file directly in a web browser that supports ES Modules (like Chrome, Firefox, Edge, Safari)
    

## Screenshot 1

<p align="center">
  <img src="https://github.com/Joker-funland/G4F-models/blob/main/Screenshots/1.jpg" alt="Description" width="800"/>
</p>

## Screenshot 2

<p align="center">
  <img src="https://github.com/Joker-funland/G4F-models/blob/main/Screenshots/2.jpg" alt="Description" width="800"/>
</p>

## Technology Stack

-   **HTML5:** For the core structure.
-   **CSS3:** For styling, including Flexbox, Grid, custom properties (variables), and animations.
-   **JavaScript (ES6+):** For API interaction, DOM manipulation, and all client-side logic, using modern features like `async/await` and ES Modules.
-   **G4F.dev JS Client:** The official client library used to interface with the API.

## Credits

-   This project was created by [Joker](https://github.com/Joker-funland)
-   Powered by the awesome [G4F (GPT4Free)](https://github.com/xtekky/gpt4free) project.
