Part 3: Development & AI Integration Reflection
Development Reflection (Your own coding experience):
Overall Approach and Strategy:
When developing each page, I aimed for clarity, functionality, and responsiveness. I focused on creating a well-structured HTML and CSS layout, ensuring a clean, user-friendly design. I followed a component-based approach, treating each section of the website (header, main content, footer, etc.) as distinct components to improve reusability. I made sure to test frequently and ensured responsiveness, particularly for mobile users.

Challenges and Solutions:
Challenge #1: Image Layout and Alignment Initially, I faced issues with aligning the images within the project cards. The images either stretched or didn't maintain their aspect ratio, creating inconsistency across different cards.
Solution: I used object-fit: cover; for the images in the .project-img class. This allowed the images to fill the container while maintaining their aspect ratio, ensuring they fit well within their respective project cards.

Challenge #2: Responsive Design for Smaller Screens My initial design had some issues on smaller screens. The text and images didn't scale properly, leading to poor readability and user experience.
Solution: I implemented media queries to adjust the layout based on screen sizes. Specifically, I used Flexbox and adjusted the layout for devices with screen widths under 768px, stacking the project cards vertically and ensuring that the text and images resized appropriately.

Insights and Skills Learned:
Responsive Design: I deepened my understanding of responsive design, particularly with Flexbox and media queries. I learned how to structure content to adapt across multiple screen sizes without compromising the layout.
CSS Transitions and Hover Effects: I learned how to implement interactive design elements, like hover effects on images and buttons. This added a dynamic feel to the website, making it more engaging.
AI Interaction Log:
AI Tool(s) Used:
I used ChatGPT for various purposes, including:

Writing HTML and CSS snippets for the project.
Troubleshooting specific coding challenges.
Getting suggestions for optimizing layout and design.
AI Prompts:
Prompt 1: "Can you generate HTML and CSS for a project card layout with images, titles, and links?"
Prompt 2: "How do I create a responsive layout using Flexbox that adapts to smaller screens?"
Prompt 3: "How can I implement a hover effect on images in CSS?"
Original AI-Generated Code:
html
Copy
Edit
<div class="project-card">
  <img src="images/project1.jpg" alt="Project 1" class="project-img" />
  <h3>Project 1</h3>
  <p>A description of the project.</p>
  <a href="https://example.com" target="_blank" class="project-link">Visit Website</a>
</div>
css
Copy
Edit
.project-img {
  width: 100%;
  height: auto;
  transition: transform 0.3s ease;
}

.project-img:hover {
  transform: scale(1.05);
}
My Modifications:
Modification to HTML:

Added extra details to the project description and links in the project cards.
Included more context for the images (such as alt text) for better accessibility.
Modification to CSS:

I adjusted the hover effect to scale(1.05) to make it more subtle and less aggressive.
I also added the object-fit: cover; property to ensure images maintain their aspect ratio within the cards.
Screenshots:
Screenshots of my AI conversations can be found in the docs/screenshots folder, demonstrating the prompts, AI responses, and code snippets generated.
Comparative Analysis:
Strengths of AI-Generated Solutions:
Quick Generation: The AI was extremely fast at generating basic structures like HTML layout and CSS for hover effects. This saved me a lot of time and helped me quickly get the structure in place.
Concise Solutions: The AI provided concise and clean code, particularly for the hover effect, which I could directly use without needing to write it from scratch.
Weaknesses of AI-Generated Solutions:
Lack of Customization: The initial code provided by AI was basic and lacked customization for the specific project. I had to modify the design details to fit the specific content and layout I envisioned.
Limited Responsiveness: The AI did not initially consider responsiveness in its design. I had to manually add media queries and adjust the layout to make the site mobile-friendly.
Optimizations Made:
I added media queries to improve the responsiveness of the layout on smaller screens. AI's code did not include this, so I manually incorporated Flexbox and adjusted the CSS for mobile-first design.
I also refined the hover effects and ensured that the images within the project cards maintained a consistent aspect ratio using object-fit: cover;.
Overall Reflection:
Experience Reflection:
Writing code manually was a rewarding experience because it deepened my understanding of how design principles and coding techniques work together. I gained hands-on experience with Flexbox, media queries, and CSS transitions, which gave me more confidence in my coding abilities.

Working with AI was incredibly helpful for getting quick solutions and brainstorming ideas. I found it most valuable when I was looking for quick fixes or solutions to repetitive tasks like generating code for layout or styling. The AI also provided creative suggestions that I wouldn't have thought of immediately.

Recommendations for Future AI Integration:
Use AI for Quick Prototyping: In future projects, I plan to use AI for rapid prototyping of basic structures like layout and hover effects, which can be time-consuming.
Customization & Fine-Tuning: While AI can handle basic code, I will focus on fine-tuning and customizing the code to match the specific needs of my project, particularly for responsiveness and dynamic features.
Test AI-Generated Code Thoroughly: Always test AI-generated code thoroughly to ensure it meets the desired functionality, especially for more complex interactions or specific project requirements.