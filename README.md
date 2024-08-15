# Personal Portfolio Website

Welcome to my personal portfolio website! This project is built using Jekyll, a static site generator, to showcase my skills, experience, and projects as a JavaScript/TypeScript developer. The site serves as a dynamic resume and a platform to highlight my work in web development, computer vision, and machine learning.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This portfolio website is designed to offer a comprehensive view of my professional journey. It features an "About Me" section, a project showcase, a detailed skills list, and a contact form. The website is fully responsive, ensuring it looks great on any device.

## Features

- **Responsive Design:** Adaptable layout that works on desktop, tablet, and mobile devices.
- **Project Showcase:** A dedicated section for displaying my projects, including descriptions, technologies used, and links to live demos or repositories.
- **About Me:** An overview of my background, research interests, and professional experience.
- **Skills & Technologies:** A list of the tools and technologies I am proficient in.
- **Contact Form:** A simple form for visitors to get in touch with me.
- **Blog (Optional):** A space to share articles, tutorials, and insights on technology and development.

## Technologies Used

- **Static Site Generator:** Jekyll
- **Frontend:**
  - HTML5
  - CSS3/Sass
  - JavaScript
  - Liquid Templating
- **Deployment:** GitHub Pages or other static hosting platforms
- **Version Control:** Git & GitHub

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/portfolio-website.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd portfolio-website
   ```

3. **Install Jekyll and Bundler:**
   ```bash
   gem install jekyll bundler
   ```

4. **Install dependencies:**
   ```bash
   bundle install
   ```

5. **Build the site and start the development server:**
   ```bash
   bundle exec jekyll serve
   ```

6. **Visit the website:**
   Open your browser and go to `http://localhost:4000` to view the website.

## Usage

Explore the site by navigating through the sections. The "Projects" section highlights my work, while the "Contact" section allows for easy communication. If you wish to customize the site, you can modify the content in the `_config.yml` file and the markdown files in the `_posts` or `_pages` directories.

## Project Structure

```bash
portfolio-website/
├── _includes/          # Reusable HTML components
├── _layouts/           # Layouts for pages
├── _posts/             # Blog posts
├── _sass/              # Sass partials
├── _pages/             # Static pages (e.g., about, contact)
├── assets/             # Images, fonts, etc.
├── _config.yml         # Jekyll configuration file
├── Gemfile             # Ruby dependencies
└── index.html          # Main landing page
```

- `_includes/`: Contains reusable components like the header and footer.
- `_layouts/`: Defines the overall structure of pages (e.g., default, post).
- `_posts/`: Blog posts written in Markdown.
- `_pages/`: Static pages like "About Me" and "Contact."
- `assets/`: Contains images, fonts, and other assets.
- `_config.yml`: Configuration settings for the Jekyll site.

## Contributing

Contributions are welcome! If you find a bug or have a suggestion for improvement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For inquiries or collaborations, feel free to reach out via the contact form on the website or connect with me on [LinkedIn](https://linkedin.com/in/your-linkedin-profile).

---

Feel free to customize this README further to suit your project!