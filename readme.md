# Final Project

## Overview
This is a responsive web project built with HTML and SCSS. It features a modern layout with multiple sections, including a header, skills showcase, information block, contact form, posts grid, and footer. The project uses SCSS for modular and maintainable styling, with media queries to ensure responsiveness across various screen sizes (2560px, 992px, 768px, 576px).

## Features
- **Responsive Design**: Adapts to different screen sizes using media queries.
- **Modular SCSS**: Styles are organized into separate files for better maintainability.
- **Grid Layouts**: Utilizes CSS Grid for arranging content in the skills and posts sections.
- **Interactive Elements**: Hover effects on buttons and skill items.
- **Mobile Navigation**: Includes a mobile-friendly navigation menu with a hamburger toggle.

## Project Structure
```
project-root/
│── css/
│   └── style.css         # Compiled CSS file
│── scss/
│   ├── style.scss        # Main SCSS file that imports all modules
│   ├── _base.scss        # Variables, mixins, and global styles
│   ├── _header.scss      # Styles for the header section
│   ├── _skills.scss      # Styles for the skills section
│   ├── _info.scss        # Styles for the info section
│   ├── _form.scss        # Styles for the contact form
│   ├── _posts.scss       # Styles for the posts section
│   └── _footer.scss      # Styles for the footer
│── images/               # Folder for images used in the project
│── index.html            # Main HTML file
└── README.md             # This file
```

## Installation
### 1. Clone the Repository
```bash
git clone https://github.com/alexanderik79/home-work-17/
cd home-work-17
```

### 2. Install Dependencies (if applicable)
If you're using a package manager like npm for Sass compilation:
```bash
npm install
```

### 3. Compile SCSS
Use a Sass compiler to generate the CSS file from SCSS:
```bash
npx sass --watch ./scss/style.scss ./css/style.css
```
Alternatively, use a tool like **Live Sass Compiler** (VS Code extension) to compile SCSS automatically.

### 4. Open the Project
Open `index.html` in a browser to view the project locally.

## Usage
- **Header**: Features a full-screen background image with navigation and call-to-action buttons.
- **Skills**: Displays a grid of skills with hover effects.
- **Info**: Contains a two-column layout with text and an image.
- **Form**: A contact form with responsive input fields and a submit button.
- **Posts**: A grid of posts that adjusts based on screen size.
- **Footer**: A simple footer with text and a decorative line.

To modify styles, edit the respective SCSS files in the `scss/` folder. Changes will be reflected after recompiling `style.scss`.

## Responsive Breakpoints
- **2560px**: Default desktop layout.
- **992px**: Adjusted layouts for tablets and smaller desktops.
- **768px**: Mobile-friendly layouts with stacked elements.
- **576px**: Single-column layout optimized for small screens.

## Technologies Used
- **HTML5**: Structure of the webpage.
- **SCSS**: Styling with variables, nesting, and modular files.
- **CSS Grid & Flexbox**: Layout techniques for responsive design.

## Contributing
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a Pull Request.

## Credits
- Developed by **Alex Pa**.
- Images sourced from [specify source if applicable, e.g., Unsplash].

## License
This project is licensed under the **MIT License** - see the `LICENSE` file for details.

