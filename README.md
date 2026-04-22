Dual-Path Professional Portfolio

🚀 Overview


This is a high-performance, minimalist Dual-Path Portfolio designed for individuals with multi-disciplinary backgrounds. Built with a focus on user experience and clean aesthetics, it allows visitors to choose between two distinct career tracks: Civil Engineering and Data Analytics.

The project uses a dynamic JavaScript-driven architecture to swap content, accent colors, and themes instantly without reloading the page, providing a seamless "app-like" transition.

✨ Key Features


Dynamic Theme Switching: Using CSS Variables (--accent-data), the entire color palette of the site shifts based on the selected career path (Earth-toned for Civil Engineering, Cyan-toned for Data Analytics).

Interactive Accordion Grid: A custom-built hover-trigger system for Skills, Internships, and Projects that maximizes screen real estate while keeping the UI clean.

Smooth Transitions: Implements custom CSS keyframes and cubic-bezier transitions for the selection screen "slide-up" effect.

Fully Responsive: Built with a mobile-first approach using Flexbox and viewport units.

Data-Driven UI: All professional content is centralized in a single JavaScript object, making it incredibly easy to update or scale.

🛠️ Tech Stack


HTML: Semantic structure.

CSS: Custom properties (variables), Flexbox, and keyframe animations.

JavaScript (Vanilla): DOM manipulation, event listeners, and dynamic template rendering.

📂 Project Structure


├── index.html      # The core structure & selection screen

├── style.css       # Global styles, animations, and dynamic themes

├── script.js       # Content data and transition logic

└── profile-photo.png # User professional image


⚙️ How It Works


Selection: The user lands on a selector-screen displaying two primary career choices.

Injection: Upon clicking a card, initPortfolio(type) is triggered. This function pulls data from the userData object in script.js.

Transformation:

The CSS --accent-data variable is updated.

Text content for the Hero, Skills, and Projects sections is injected into the DOM.

The selection screen slides up, and the main-content is revealed via a fade-in animation.

🖋️ Customization


To adapt this portfolio for yourself:

Update Content: Open script.js and modify the userData object with your own name, contact info, and professional milestones.

Change Colors: Modify the accent hex codes in the userData object to match your personal branding.

Swap Image: Replace profile-photo.png with your own headshot.

👤 Author


Shayantika Ghosh B.Tech Civil Engineering | NIT Agartala Specializing in Structural Execution & Data Intelligence

📄 License


This project is open-source. Feel free to fork, modify, and use it for your own professional portfolio!
