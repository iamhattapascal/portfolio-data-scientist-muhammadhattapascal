Data Science Portfolio Implementation Plan
This plan outlines the creation of a stunning, modern, and high-performance Data Science Portfolio for Muhammad Hatta Pascal based on the provided resources.

User Review Required
IMPORTANT

Since you did not explicitly request a complex web framework like React, I propose building this portfolio using pure HTML, CSS, and vanilla JavaScript. This ensures a fast, lightweight, and easily hostable website. I will design it with a premium dark mode aesthetic (deep navy/black background with neon cyan/teal accents) to give it a tech-forward, professional data scientist vibe. Does this sound good to you?

Proposed Changes
We will create a new directory named portfolio-website inside your current folder.

Project Structure (HTML/CSS/JS)
[NEW] 
index.html
The main structure of the portfolio, divided into several semantic sections:

Hero Section: Introduces you as a Data Analyst / Data Scientist with your Name and a dynamic, typing text animation.
About Me: Your background in International Relations and your transition into Data Analytics. Includes your profile picture.
Skills Section: A visually appealing grid of your skills (Python, SQL, PowerBI, etc.) with custom hover effects.
Projects Section: Showcasing your "Bank Marketing Campaign Analysis" project with details on your goal, the metrics, and business questions answered.
Contact Info: Your email, phone, and LinkedIn properly linked and easily accessible.
[NEW] 
styles.css
The stylesheet responsible for the premium, dynamic aesthetic.

Custom modern fonts (e.g., 'Inter', 'Outfit').
Glassmorphism effects for project and skill cards.
Responsive layout using Flexbox and CSS Grid.
Smooth gradients and hover animations for an interactive feel.
[NEW] 
script.js
Handles all dynamic interactivity:

Smooth scrolling for navigation links.
"Fade-in on scroll" animations using the Intersection Observer API.
Dynamic text typing effect in the hero section for a "coding" aesthetic.
[NEW] [assets folder]
We will copy your profile picture (DSC_0400 copy.JPG) to this folder so it can be displayed seamlessly on the website.

Verification Plan
Manual Verification
I will start a local python server and use my browser tools to capture screenshots of the final result for your review.
You can manually open index.html in your browser to test the responsiveness and animations!