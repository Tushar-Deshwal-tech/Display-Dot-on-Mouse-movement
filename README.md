Mouse Tracker
    A simple JavaScript project that tracks the mouse cursor on a webpage and creates a colored dot at the cursor’s position. The dot changes its color randomly with each movement, giving a fun, dynamic visual effect.

How It Works    
    1.  Mouse Movement Detection
        A mousemove event is triggered on the document.body whenever the mouse moves.
    2. Dot Creation
        The myFunction (or similar function) is called in response to the mousemove event. It creates a small dot element at the current mouse position.
    3. Random Colors
        The getRandomColor function generates a random color in hexadecimal format for each dot, making every movement colorful and dynamic.
    4. Dot Removal
        The displayHello function (or similar logic) removes the dot from the DOM after a short duration using setInterval or setTimeout, preventing clutter.

Usage
    1. Include the JavaScript code in your HTML file or link it externally.
    2. Open the HTML file in any modern web browser.
    3. Move your mouse around the webpage to see the colored dot follow the cursor.

Features
    Real-time mouse tracking with colorful dots.
    Smooth Falling and Gravity.
    Bouncing Effect.
    Smooth Fade Out
    Lightweight and easy to integrate into any webpage.
    No external dependencies required.

Dependencies
    This project does not require any external libraries or frameworks. Vanilla JavaScript and standard HTML/CSS are sufficient.

Contributions are welcome! You can:
    Submit pull requests to add features or fix bugs.
    Open issues for suggestions, bug reports, or improvements.
    Improve code efficiency, add new modes (like trails or fading effects), or enhance styling.

License
    This project is open source and free to use for personal and educational purposes.
