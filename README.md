Oh Young Ebon Yon: Web Development Learning Platform
Overview
Oh Young Ebon Yon is a landing page designed to engage aspiring web developers with a platform offering personalized web development education. The page promotes email sign-ups through MailChimp, enabling one-on-one mentorship and tailored learning experiences. Hosted at harrismbrad.github.io/start-up, it leverages modern web technologies for a responsive, animated interface optimized for user acquisition. A two-year A/B testing plan (2025–2027) with MailChimp aims to refine user engagement and maximize sign-up conversions.
Features

Interactive Landing Page: Engaging design with animated headlines and CTAs to attract users.
MailChimp Integration: Email sign-up form for capturing leads and managing campaigns.
Responsive Design: Built with Bootstrap 5 for seamless display across desktop, tablet, and mobile.
Animations: Powered by Animate.css for effects like bounce and heartbeat to enhance user interaction.
Custom Styling: Uses Google Fonts (Montserrat) and new-style.css for a distinctive look.
JavaScript Functionality: script.js supports dynamic features like form handling and animation triggers.

A/B Testing Plan (2025–2027)
The project employs MailChimp for A/B testing to optimize email sign-up rates over two years. Tests will run in quarterly cycles, with results driving iterative improvements. Key test areas include:

Headlines: Compare variations (e.g., “Ready to Learn Web Development?” vs. “Start Your Web Dev Journey!”) for maximum appeal.
CTA Buttons: Test button text (e.g., “Find Out More” vs. “Join Now”) and styles (e.g., color, size, hover effects).
Animations: Evaluate Animate.css effects (e.g., bounce vs. pulse) for engagement impact.
Layout Variations: Experiment with form placement or additional elements like testimonials.
Metrics:
Click-through rate (CTR) on the sign-up button.
Email sign-up conversion rate.
Campaign engagement (e.g., open rates, click rates in follow-up emails).


Process: Run each test for 2–4 weeks to ensure statistical significance. Log results in docs/ab-testing.md for transparency and future reference.

Tech Stack

HTML5: Core page structure.
Bootstrap 5: Responsive framework (CDN-hosted).
Animate.css: Animation library (CDN-hosted).
Google Fonts: Montserrat for typography.
Custom CSS: new-style.css for unique styling.
JavaScript: script.js for interactivity (e.g., form validation, animations).
MailChimp: Email marketing platform for lead capture and A/B testing.

Setup Instructions

Prerequisites:
Node.js (optional, for live-server).
A modern web browser.
A MailChimp account with a sign-up form URL.


Clone the Repository:git clone https://github.com/harrismbrad/start-up.git
cd start-up


Serve the Application:
Use live-server (requires Node.js):npm install -g live-server
live-server


Or use Python:python -m http.server 8000


Open http://localhost:8000 in a browser.


Configure MailChimp:
Update the <a href> in index.html with your MailChimp sign-up form URL (e.g., replace https://mailchi.mp/51a122bcd2ae/my-new-start-up-ztm-students).
Set up A/B testing campaigns in MailChimp aligned with the testing plan.


Verify Files:
Ensure new-style.css and script.js are in the project root.
Confirm CDN links for Bootstrap and Animate.css are accessible.



Project Structure
├── index.html         # Main landing page
├── new-style.css      # Custom styles
├── script.js          # JavaScript for interactivity
└── docs/             # Directory for A/B testing logs (create if needed)

Contributing
Contributions are welcome to enhance the landing page or A/B testing setup. To contribute:

Fork the repository and create a feature branch:git checkout -b feature/your-feature-name


Make changes and test locally using a web server.
Commit with a descriptive message:git commit -m "Add feature: describe your changes"


Push to your fork and submit a pull request to the master branch.
If changes affect the user interface, note A/B testing implications (e.g., new headline to test).

A/B Testing Guidelines

Setup: Create MailChimp campaigns with clear variations (e.g., headline A vs. B).
Tracking: Monitor CTR, sign-up rates, and campaign engagement via MailChimp analytics.
Iteration: Run tests for 2–4 weeks, analyze results, and update the page accordingly.
Documentation: Record test details in docs/ab-testing.md (e.g., variations, metrics, outcomes) to guide future tests.

Vision for 2025–2027
Oh Young Ebon Yon aims to be a leading platform for aspiring web developers, offering personalized mentorship and a vibrant learning community. Through iterative A/B testing, the project will optimize user acquisition and engagement, ensuring a seamless onboarding experience. Future enhancements may include:

Course previews to showcase learning content.
Live mentorship scheduling via integrated tools.
Community forums for peer collaboration.
Integrations with learning management systems (e.g., Moodle, Canvas).

Next Steps

Implement script.js for form validation and animation controls.
Launch initial A/B tests in MailChimp for headline and CTA variations.
Collect user feedback via MailChimp campaigns to refine content.
Explore integrations with educational or community platforms.
