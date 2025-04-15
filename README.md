# Simple QR Code Generator

A basic web application that generates a QR code based on the text or URL entered by the user. It utilizes the free [qrserver.com API](https://goqr.me/api/) to create the QR code image dynamically.

**[[Live Demo] https://qrcode-dellabella.netlify.app/

## What I Learned/Practiced:

*   **HTML Structure:** Setting up input fields (`input`), image elements (`img`), containers (`div`), and likely buttons (`button`) with appropriate `id` attributes.

*   **CSS Styling:**
    *   Basic element styling (background, padding, margins, borders).
    *   Centering elements (e.g., using `margin: auto` for the image box).
    *   Using `max-height` and `overflow: hidden` with a `transition` to smoothly show/hide the QR code image container.
    *   Applying conditional styling using CSS classes (`.show-img`, `.error`).
    
*   **JavaScript Fundamentals:**
    *   **DOM Manipulation:**
        *   Selecting elements using `document.getElementById()`.
        *   Reading the value from an input field (`element.value`).
        *   Setting the `src` attribute of an image element (`element.src`).
        *   Adding/removing CSS classes (`element.classList.add()`, `element.classList.remove()`).
    *   **Conditional Logic:** Using `if...else` statements to check if the input field has text (`value.length > 0`).
    *   **String Concatenation:** Building the API URL by joining strings together.
    *   **Interacting with APIs:** Making a request to an external API by constructing a specific URL.
    *   **Basic Asynchronous Operations:** Using `setTimeout()` to create a timed effect (removing the error class).
    *   **Debugging:** Identifying and fixing typos (like `lenght` vs `length`).
 
    
*   **(Implied)** **Event Handling:** Setting up an event listener (likely on a button click) to trigger the `generateQR` function.

This project was a good exercise in combining HTML, CSS, and JavaScript to create an interactive user interface that communicates with an external service.

#jslearning
