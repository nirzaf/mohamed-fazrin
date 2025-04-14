# Mohamed Fazrin - Senior Full Stack Developer Portfolio

This repository contains the source code for Mohamed Fazrin's personal portfolio website. It's designed as a single-page HTML application showcasing his skills, professional experience, education, certifications, and contact information. The page is built with a focus on clean design, responsiveness, and SEO best practices.

## Description

This portfolio serves as a comprehensive digital resume for Mohamed Fazrin, a Senior Full Stack Developer specializing in React, .NET Core, Azure Cloud Architecture, and AI Integration. It aims to provide potential employers, recruiters, clients, and collaborators with a detailed overview of his technical expertise and career journey.

## Key Features

*   **Personal Information:** Displays name, title, tagline, profile picture, and contact details (Email, Phone, Location, Social Links).
*   **Professional Overview:** A summary of experience and key strengths.
*   **Core Expertise:** Highlights primary technical skill areas (Full Stack, Cloud, Performance, AI).
*   **AI Expertise Domains:** Details specific knowledge areas within Artificial Intelligence.
*   **Freelance Expertise:** Showcases proficiency with popular CMS/E-commerce platforms (WordPress, Magento, etc.) and related frameworks/contributions.
*   **Core Competencies:** Detailed breakdown of skills with associated technologies (React, .NET, Cloud, Databases, AI Tools, Architecture) presented in card format.
*   **Professional Experience:** A chronological timeline detailing past roles, companies, responsibilities, key achievements, and technologies used for each position.
*   **Education:** Information about academic background (MSc, BE) including university, degree, results, focus areas, and honors.
*   **Certifications & Achievements:** Lists relevant certifications (Azure, Google AI, IELTS, Udemy) and notable achievements (e.g., platform ratings).
*   **Responsive Design:** Fully responsive layout adapting seamlessly to desktops, tablets, and mobile devices.
*   **Visually Appealing UI:** Clean, modern design using Tailwind CSS utility classes, a consistent color scheme (slate/blue), custom timeline styling, and card components with hover effects.
*   **SEO Optimized:** Includes relevant meta tags (title, description, keywords, Open Graph) for better search engine visibility and social sharing.
*   **Print-Friendly:** Custom print stylesheet (`@media print`) ensures the page prints cleanly and professionally, hiding unnecessary elements like the profile picture and adjusting layout/styles.
*   **Email Obfuscation:** Uses basic JavaScript to dynamically generate the email address and `mailto:` link, helping to deter simple email harvesting bots.

## Technologies Used

*   **HTML5:** Semantic markup for structure and content accessibility.
*   **Tailwind CSS v3:** A utility-first CSS framework used for rapid UI development, responsive design, and consistent styling. All styling is primarily achieved through Tailwind classes.
*   **JavaScript (Vanilla):** Used for minor dynamic functionalities:
    *   Generating the current year and formatted date in the footer.
    *   Obfuscating the email address to protect it from basic web crawlers.
*   **Google Fonts (Inter):** Used for clean and readable typography (optional, linked via CDN).
*   **SVG Icons:** Embedded SVGs used for contact details and social media links for scalability and clarity.

## Getting Started / How to View

This is a static HTML website. To view it:

1.  **Clone or Download:** Get a copy of the repository/files onto your local machine.
    ```bash
    git clone <repository-url>
    ```
    or download the ZIP archive.
2.  **Open the File:** Navigate to the project directory and open the `index.html` file (or the specific HTML file name) directly in your web browser (e.g., Chrome, Firefox, Edge, Safari).

No build process or server is required to view the page locally.

## Design & Responsiveness

*   **Utility-First:** Leverages Tailwind CSS for styling, enabling rapid development and easy maintenance.
*   **Mobile-First:** Designed with a mobile-first approach, ensuring a great experience on smaller screens.
*   **Breakpoints:** Uses Tailwind's default breakpoints (`sm`, `md`, `lg`, `xl`, `2xl`) to adapt the layout (e.g., grid columns, header arrangement).
*   **Visual Hierarchy:** Clear visual hierarchy established through font sizes, weights, colors, and spacing.
*   **Custom Components:** Includes custom styling for elements like the experience timeline and skill tags for enhanced visual appeal.

## SEO & Accessibility

*   **Meta Tags:** Comprehensive `meta` tags are included in the `<head>` for SEO.
*   **Semantic HTML:** Uses semantic elements like `<header>`, `<section>`, `<nav>`, `<footer>`, `<h1>`-`<h4>`, `<ul>` to improve structure and accessibility.
*   **Image Alt Text:** The profile picture includes descriptive `alt` text.
*   **ARIA Labels:** Added `aria-label` attributes to icon-only links (social media) for screen reader users.

## Customizations

*   **Email Obfuscation:** The email address in the header and footer is generated via JavaScript to prevent simple scraping. If JavaScript is disabled, a placeholder `[email protected]` is shown.
*   **Print Styles:** A dedicated `@media print` block optimizes the layout for printing, ensuring readability and conserving ink/paper.

## Author

*   **Mohamed Fazrin**
