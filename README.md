# Scandalous 📷 

Scandalous is built using **pure front-end technologies** with no frameworks or build tools, making it a clean and accessible example of a client-side web app. Here's a breakdown of the skills demonstrated:

## ✅ HTML5

* Structured a responsive single-page application using semantic HTML
* Created user interface components: input field, buttons, image container, and footer
* Implemented accessibility-friendly elements like `label` and descriptive placeholders

## ✅ CSS3

* Designed a clean, modern interface with custom styling
* Utilized:

  * **Box model & Flexbox** for layout positioning
  * **Transitions and animations** for interactive UI elements (e.g. shake animation on input error)
  * **Responsive design** using media queries for mobile compatibility
* Styled conditionally visible elements using `max-height` transitions (e.g. `#qrBox`, `#downloadBtn`)

## ✅ JavaScript (Vanilla JS)

* Used **DOM manipulation** to interact with user input and update the interface dynamically
* Implemented:

  * Input validation and error feedback via animations
  * Real-time QR code generation using an external API:

    ```text
    https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=[your-text]
    ```
  * Image loading and download link generation using `onload` and `href`
  * Reset functionality via `window.location.reload()`
* No external libraries or frameworks—showcases strong grasp of core JS concepts

## ✅ API Integration

* Connected to a third-party **QR Code API** (`qrserver.com`) to offload generation logic
* Handled dynamic URL creation and response management without server-side code

## ✅ UX/UI Principles

* Interactive feedback for errors (input shaking)
* Hidden buttons and image areas that appear only when needed
* Consistent color scheme and readable typography

---
<img width="1320" height="659" alt="Screenshot 2025-08-18 at 14 28 07" src="https://github.com/user-attachments/assets/f585ee0e-3ab7-418d-b83a-5eb0b81cf9ac" />

<img width="1320" height="659" alt="Screenshot 2025-08-18 at 15 25 58" src="https://github.com/user-attachments/assets/0e4e1521-0fff-47ab-8db7-fea922a7d1e5" />

