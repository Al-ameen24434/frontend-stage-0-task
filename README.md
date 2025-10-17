Profile Card
A modern, accessible, and responsive profile card component built with plain HTML, CSS, and vanilla JavaScript. This project demonstrates semantic HTML, real-time updates, and a visually appealing design inspired by contemporary web standards.
Demo

Live URL: https://al-ammen-stage-o.netlify.app/
GitHub Repo: https://github.com/Al-ameen24434/frontend-stage-0-task.git

Features

Responsive Design: Adapts seamlessly to mobile, tablet, and desktop screens.
Real-Time Updates: Displays the current time in milliseconds, updated every second.
Beautiful Styling: Features a gradient header, soft pastel colors, and icon-based social links.

Requirements

A modern web browser (Chrome, Firefox, Edge, etc.).
No external dependencies; runs entirely with static files.

Installation

Clone the Repository:
git clone https://github.com/Al-ameen24434/frontend-stage-0-task.git
cd frontend-stage-0-task


Open the Project:

Simply open index.html in a web browser to view the profile card locally.


Deploy (Optional):

Push the code to a GitHub repository.
Enable GitHub Pages or deploy to Netlify for a live version.



Usage

View the Card: Open index.html to see the profile card with default content.
Social Links: Click the emoji icons to visit social profiles (opens in a new tab).

Structure

index.html: Contains the HTML structure, CSS styles, and JavaScript logic.
README.md: This file, providing project documentation.

Testing

All visible elements include data-testid attributes (e.g., test-profile-card, test-user-name) for automated testing.
Verify the current time matches Date.now() (within a small delta due to rendering).
Test keyboard navigation for social links and the bio expand button.
Ensure responsiveness by resizing the browser window.

Contributing
Feel free to fork this repository and submit pull requests for enhancements or bug fixes. Please ensure all changes maintain accessibility and responsiveness.
Notes

The time is updated every second using setInterval, reflecting the current timestamp in milliseconds (e.g., ~176061780000 ms as of 06:30 AM WAT, October 17, 2025).
The design is inspired by a modern profile card demo, using a gradient header, emoji icons, and a clean layout.
No external libraries or dependencies are required.
If deploying, update the live URL and GitHub repo links in this README with your actual project details.

License
This project is open-source and available under the MIT License. 
