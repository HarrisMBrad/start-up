# Oh Young Ebon Yon: Learn Web Development
Overview
Oh Young Ebon Yon is a landing page designed to attract aspiring web developers to a learning platform offering personalized web development education. The platform encourages users to sign up via email through MailChimp, enabling one-on-one mentorship and tailored learning experiences. Built with modern web technologies, the page is optimized for engagement and conversion, with a focus on A/B testing to refine user experience over a two-year period (2025–2027).
Features

## Engaging Landing Page: A responsive, visually appealing interface with animated elements to capture user interest.
MailChimp Integration: Email sign-up form linked to MailChimp for user acquisition and campaign management.
Responsive Design: Built with Bootstrap 5, ensuring compatibility across desktop, tablet, and mobile devices.
Animations: Powered by Animate.css for dynamic effects like bounce and heartbeat to enhance user interaction.
Custom Styling: Uses Google Fonts (Montserrat) and a custom stylesheet (new-style.css) for a unique look.

### A/B Testing Plan (2025–2027)
The project leverages MailChimp for A/B testing to optimize user sign-up rates over two years. Key testing areas include:

Headline Variations: Test different headlines (e.g., "Ready to Learn Web Development?" vs. "Master Web Dev with Us!") to identify the most compelling messaging.
Button Text and Design: Experiment with button labels (e.g., "Find Out More" vs. "Join Now") and styles (e.g., color, size).
Animation Effects: Compare the impact of different Animate.css effects (e.g., bounce vs. pulse) on user engagement.
Layout Adjustments: Test variations in layout, such as repositioning the sign-up form or adding testimonials.
Metrics: Track click-through rates (CTR), sign-up conversion rates, and user retention in MailChimp campaigns.

### Testing will be conducted in iterative cycles, with data analyzed quarterly to refine the landing page and maximize conversions.
Tech Stack

HTML5: Core structure of the landing page.
Bootstrap 5: Responsive design framework (CDN-hosted).
Animate.css: Animation library for dynamic effects (CDN-hosted).
Google Fonts: Montserrat font for typography.
Custom CSS: new-style.css for additional styling.
JavaScript: script.js for dynamic behavior (e.g., form handling, animations).
MailChimp: Email marketing platform for sign-up collection and A/B testing.

### Setup Instructions

Clone the Repository:git clone <repository-url>
cd <repository-directory>


Serve the Application:
Use a local web server (e.g., live-server or Python's HTTP server):npx live-server

orpython -m http.server 8000


Open http://localhost:8000 (or the specified port) in a browser.


Dependencies: No local dependencies are required, as Bootstrap and Animate.css are CDN-hosted. Ensure new-style.css and script.js are in the project root.
MailChimp Setup:
Update the <a href> link in index.html with your MailChimp form URL.
Configure A/B testing campaigns in MailChimp to align with testing goals.



### Project Structure

├── index.html         # Main landing page
├── new-style.css      # Custom styles
└── script.js          # JavaScript for dynamic behavior

Contributing
Contributions are welcome to enhance the landing page or A/B testing setup. To contribute:

Fork the repository and create a feature branch:git checkout -b feature/your-feature-name


Make changes and test locally.
Commit with a clear message:git commit -m "Add feature: your feature description"


Push to your fork and submit a pull request to the master branch.

### Please include a description of A/B testing implications if your changes affect the user-facing interface.
A/B Testing Guidelines

#### Test Setup: Use MailChimp's A/B testing tools to create campaigns with variations (e.g., different headlines or button text).
Tracking: Monitor sign-up rates, CTR, and campaign performance via MailChimp analytics.
Iteration: Run tests for at least 2–4 weeks per variation to gather sufficient data, adjusting based on results.
Documentation: Log test outcomes in a docs/ab-testing.md file (create if needed) to track what works and inform future iterations.

#### Vision for 2025–2027
Oh Young Ebon Yon aims to become a leading platform for aspiring web developers, offering personalized learning paths and community support. Through continuous A/B testing, the project will optimize user acquisition and engagement, ensuring a seamless onboarding experience. The platform will evolve based on user feedback and analytics, potentially integrating additional features like course previews, live mentorship scheduling, or community forums.

#### Next Steps

 - Implement script.js to handle form validation and dynamic animations.
 - Set up initial A/B tests in MailChimp for headline and button variations.
 - Collect user feedback via MailChimp campaigns to refine content.
 - Explore integrations with learning management systems or community platforms.
