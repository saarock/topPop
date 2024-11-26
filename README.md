# JavaScript BackToTop Library 🚀

A lightweight and customizable JavaScript library to add a "Back to Top" button to your website. **No additional dependencies needed**—everything is handled automatically!

## Key Features 🛠️
- **Auto-hide Button:** The button only appears when the user scrolls down.
- **Built-in Icons:** Font Awesome icons are automatically included.
- **Customizable:** Change the button color and other styles.
- **Smooth Scrolling:** Enhances user experience with a smooth scroll effect.

## Installation 📥

### Step 1: Add the Library
Add the library to your project via CDN:

```html
<script type="module">
    import { backToTop } from "https://cdn.jsdelivr.net/gh/saarock/topPop@main/index.js";

    // Initialize the Back to Top button
    backToTop.backToTopCodes({
        backColor: "green", // Optional: Customize the button color
    });
</script>
```

# How It Works 🛠️
- Font Awesome Integration: Automatically includes Font Awesome icons, no need to manually add them.
- Dynamic Button Creation: The button is added to the page only when necessary, and automatically appears/disappears based on user scroll.
- Smooth Scrolling: When the button is clicked, the page scrolls back to the top smoothly for a better user experience.

# Contributing 🤝
Feel free to submit issues or contribute to the project by forking it and sending a pull reques