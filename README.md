#project Lee Wing
Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This website is designed to showcase your portfolio, with sections for services, portfolio items, testimonials, and a contact form. It includes a carousel for portfolio images and a sticky navigation bar that adapts to screen sizes.
Features

	•	Responsive Design: The site adapts seamlessly to various screen sizes, from desktop to mobile.
	•	Sticky Navigation: The navigation bar stays at the top of the screen as you scroll.
	•	Portfolio Carousel: A sliding carousel showcasing project images.
	•	Service Cards: Each service is displayed in an easy-to-click card format.
	•	Testimonials Section: A scrollable carousel of client feedback.
	•	Contact Section: Includes contact info and social media links.
Installation

To run this project locally, follow these steps:
1.	Clone the Repository
Clone this repository to your local machine using the following command:

git clone https://suadtech.github.io/ProjectLeeWing/
2.	Navigate to the Project Directory
Change to the project directory:

cd portfolio-website


3.	Open in Browser
Open the index.html file in your browser to see the portfolio website in action.
Alternatively, you can use a local development server, such as:

python -m http.server
Usage

This portfolio site is designed to be easily customizable:
	•	To update the logo, replace the logo image in the assets/images directory and update the path in the HTML file.
	•	To modify the portfolio items, go to the index.html file, and under the “Portfolio Section,” replace the images and descriptions with your own.
	•	To add more services or testimonials, update the HTML under the respective sections.
	•	Contact Form: If you want to make the contact form functional, integrate it with a backend or use a service like Formspree.

Technologies Used

	•	HTML5: Used for the structure and content of the website.
	•	CSS3: For styling and responsive design.
	•	JavaScript: For functionality such as the portfolio carousel.
	•	Bootstrap: (If included) For quick, responsive layout design (Optional).
Contributing

	1.	Fork this repository.
	2.	Create a new branch (git checkout -b feature-name).
	3.	Make changes and commit them (git commit -m 'Add feature').
	4.	Push to your branch (git push origin feature-name).
	5.	Open a Pull Request.
USER STORIES
User story1
As a user, I want a responsive navigation menu so that I can easily move between sections on any device.
• Acceptance Criteria:
• Navigation menu must collapse on mobile screens and expand on desktop screens.
• Links should scroll to the correct sections without delay.
• Menu should be accessible via touch and click on all devices.
• Tasks:
1. Create mobile-first design for the navigation menu.
2. Test menu behavior on various screen sizes.
3. Implement smooth scrolling for anchor links.
4. Ensure accessibility (ARIA labels, keyboard navigation).
User story2
As a visitor, I want to see an engaging introduction so I can immediately understand the site’s purpose.
• Acceptance Criteria:
• The hero section must have clear, concise text introducing the service or brand.
• Background image or video should load quickly and not obstruct the content.
• Text should be legible on all screen sizes, with proper contrast.
• Tasks:
1. Design hero section with attention-grabbing visuals and clear text.
2. Optimize images/videos for faster load time.
3. Ensure the hero section resizes appropriately on different devices.
4. Test for contrast and legibility on various screen brightness levels.
User story3
As a potential client, I want to browse the portfolio images to get a sense of the company’s capabilities.
• Acceptance Criteria:
• Portfolio images should be displayed in a carousel format.
• Carousel navigation (next/previous buttons) should work seamlessly.
• Images should maintain quality across devices.
• Tasks:
1. Set up a carousel structure using appropriate JavaScript or library (e.g., Slick, Swiper).
2. Ensure image responsiveness to maintain quality on different screen sizes.
3. Add image captions/descriptions that are accessible for all users.
4. Test carousel functionality on mobile, tablet, and desktop devices.
User story 4
As a user, I want to see clear service descriptions and pricing so I can make informed decisions.
• Acceptance Criteria:
• Each service card should display the name, a brief description, and pricing.
• Clicking a service card should open a detailed view with more information.
• Cards should have consistent styling and clear CTAs (e.g., “Learn More”).
• Tasks:
1. Design service cards with relevant content (description, pricing).
2. Implement modal or dedicated page for detailed service information.
3. Add clear and consistent CTA buttons.
4. Test card responsiveness and styling across devices.
User story 5
As a new visitor, I want to read testimonials so I can trust the quality of services provided.
• Acceptance Criteria:
• Testimonials must be visually distinct and easy to read.
• Testimonials should include the name and position of the person, and ideally, a photo.
• At least 5 testimonials should be displayed.
• Tasks:
1. Collect and format testimonials (text + optional photos).
2. Design a layout that alternates between testimonials to avoid monotony.
3. Implement a carousel or grid layout to display multiple testimonials.
4. Ensure text is legible with appropriate font size and color contrast.
User story 6
As a user, I want a clear “Book Now” button so I can easily schedule a service.
• Acceptance Criteria:
• CTA button should be prominent and accessible from multiple sections of the site.
• Clicking the CTA should lead to a booking form or scheduler page.
• Button should change color or style on hover to indicate interactivity.
• Tasks:
1. Design and style the “Book Now” button with distinct colors.
2. Link the button to the booking page/form.
3. Implement hover and active states for the button.
4. Ensure the button is accessible for users with disabilities (focus styles, keyboard navigation).
• User Story:7
As a user, I want to easily find contact details so I can quickly get in touch.
• Acceptance Criteria:
• Contact info (phone, email, address) should be easily visible in the footer or a dedicated section.
• Phone numbers should be clickable on mobile devices to call directly.
• Email links should open the default email app on mobile and desktop.
• Tasks:
1. Gather and organize contact details for display.
2. Implement clickable phone numbers and email addresses.
3. Add a map (optional) for physical location on the contact page.
4. Test for mobile compatibility (click-to-call on mobile devices).
• User Story:8
As a customer, I want to see clear opening hours so I know when the business is available.
• Acceptance Criteria:
• Hours should be displayed in a clear table format with days of the week and time slots.
• Table should be responsive and easy to read on mobile.
• If there are holidays or special hours, they should be noted.
• Tasks:
1. Design the opening hours table with proper formatting.
2. Ensure the table is responsive for mobile users.
3. Implement a holiday schedule if applicable.
4. Test the visibility of the table on smaller screen sizes.
• User Story:9
As a visitor, I want the site to load quickly so I don’t get frustrated waiting for content.
• Acceptance Criteria:
• The website should load in under 3 seconds on average.
• Lazy loading should be used for images and videos to improve initial load time.
• All critical assets should be optimized for fast loading (images, scripts, CSS).
• Tasks:
1. Compress images and optimize for faster loading.
2. Implement lazy loading for non-essential images or content.
3. Minify CSS, JavaScript, and HTML files.
4. Test load times using tools like Google PageSpeed Insights.
• User Story:10
As a mobile user, I want the footer to be readable and easy to navigate on a small screen.
• Acceptance Criteria:
• Footer sections (contact, social links, legal) should be organized vertically on mobile.
• Links should be large enough to be easily tapped.
• Social icons should link to the correct profiles and be tappable on mobile.
• Tasks:
1. Reorganize footer content for mobile display.
2. Make sure footer links are tappable (increase touch target area).
3. Ensure social media icons are clickable and open in a new tab.
4. Test footer on multiple mobile devices to ensure usability.