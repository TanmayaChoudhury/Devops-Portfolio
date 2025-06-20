# DevOps Portfolio

This is a portfolio website showcasing various DevOps projects, skills, certifications, and contact information. The website is built using Tailwind CSS for styling and includes multiple sections to highlight the developer's expertise and experience in the DevOps field.

## Project Structure

The project is organized as follows:

```
devops-portfolio
├── public
│   ├── index.html          # Main HTML file for the portfolio website
│   ├── projects.html       # Detailed view of DevOps projects
│   ├── skills.html         # Skills section with tool logos
│   ├── certifications.html  # Certifications section
│   └── contact.html        # Contact information and links
├── src
│   ├── css
│   │   └── tailwind.css    # Tailwind CSS styles
│   └── js
│       └── main.js         # JavaScript functionality
├── tailwind.config.js       # Tailwind CSS configuration
├── package.json             # npm configuration and dependencies
└── README.md                # Project documentation
```

## Features

- **Responsive Design**: The website is fully responsive and looks great on all devices.
- **Tailwind CSS**: Utilizes Tailwind CSS for a modern and clean design.
- **Project Showcase**: Detailed pages for each project with descriptions and links to GitHub repositories.
- **Skills Display**: A visually appealing section showcasing various DevOps tools and technologies.
- **Certifications**: A dedicated section for displaying certifications.
- **Contact Information**: Easy access to contact details, including links to LinkedIn and GitHub.

## Setup Instructions

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd devops-portfolio
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Build the Tailwind CSS:
   ```
   npx tailwindcss -i ./src/css/tailwind.css -o ./public/styles.css --watch
   ```

5. Open the `public/index.html` file in your browser to view the portfolio.

## Usage Guidelines

- Customize the content in the `public` directory to showcase your own projects, skills, and certifications.
- Update the `src/js/main.js` file for any additional interactivity you wish to implement.
- Modify the `tailwind.config.js` file to customize Tailwind CSS settings as needed.

## License

This project is licensed under the MIT License.