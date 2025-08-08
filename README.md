🛠 Tools
HTML + CSS

Chrome DevTools

VS Code

🎯 Features
Responsive layout using media queries

Flexible grid that stacks on smaller screens

Scalable images and font sizes

Mobile navigation optimized for vertical stacking

📁 File Structure
bash
Copy
Edit
/project-root
│
├── server.js         # Node.js REST API server
├── index.html        # Main HTML file
├── style.css         # Responsive CSS with media queries
├── README.md         # This file
📱 Responsive Design Notes
CSS uses media queries to adjust layout for smaller screens (max-width: 768px):

css
Copy
Edit
@media (max-width: 768px) {
  .container {
    flex-direction: column;
  }

  .nav-menu {
    flex-direction: column;
  }
}
