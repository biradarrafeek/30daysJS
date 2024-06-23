**Key Logger Project**

This is a simple key logger project to demonstrate handling keyboard events using JavaScript and updating the DOM in real-time.
Project Overview

This project consists of an HTML file and a JavaScript file. The HTML file creates a user interface with buttons to start and stop logging key presses. The JavaScript file handles the key press events and updates the displayed text accordingly.
HTML Structure

**The HTML file contains:**

    A container div that holds the title, description, buttons, and logging areas.
    A button-container div that contains two buttons: "Start Logging Keypresses" and "Stop Logging Keypresses".
    A log-container div that contains two divs: one for displaying the key press logs and one for displaying the state (key down/up).

**JavaScript Functionality**

The JavaScript file contains:

    Variables to reference the log, state, start-btn, and stop-btn elements.
    Event listeners for the start-btn and stop-btn buttons.
    Functions handleDown and handleUp to handle keydown and keyup events, respectively.
    The event listeners for keydown and keyup are added when the "Start Logging Keypresses" button is clicked and removed when the "Stop Logging Keypresses" button is clicked.
    The text content of the log and state divs is updated based on the key events.
