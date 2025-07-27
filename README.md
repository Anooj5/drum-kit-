**Drum Kit**

A simple and interactive Drum Kit Web App built using HTML, CSS, and JavaScript. This project allows users to play drum sounds either by clicking on on-screen buttons or by pressing corresponding keyboard keys, making it both fun and a good introduction to DOM manipulation and event handling in JavaScript.

**Features**

Interactive Buttons: Click on the drum pads to play different drum sounds.
Keyboard Support: Use specific keys on the keyboard to trigger drum sounds.
Animations: Visual button press animations for a better user experience.
Responsive Design: Works across devices (desktop, tablet, mobile).
Lightweight: No external frameworks — pure HTML, CSS, and JavaScript.

**Technologies Used**

HTML5 – For the structure of the web page
CSS3 – For styling and button animations
JavaScript (ES6) – For event listeners, sound playback, and interactivity


**How It Works**

Each drum button is mapped to a unique sound file.
Event listeners detect either mouse clicks or keyboard presses.
JavaScript plays the corresponding .mp3 sound and triggers a short animation.


Folder Structure

drum-kit/
│
├── index.html     # Main HTML file
├── style.css      # Styling for the drum kit
├── script.js      # JavaScript logic for sound and interaction
└── sounds/        # Folder containing drum sound files
