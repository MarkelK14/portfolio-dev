# Portfolio Website

This is a personal portfolio website built to showcase projects, experience, and skills. The website is designed to be responsive, accessible, and visually appealing, using modern web development tools and best practices.

## Index

- [Portfolio Website](#portfolio-website)
  - [Index](#index)
  - [Features](#features)
  - [Tech Stack](#tech-stack)
  - [Project Structure](#project-structure)
  - [Installation](#installation)
  - [Build](#build)
  - [License](#license)

## Features

- **Responsive Design**: Optimized for all screen sizes, from mobile to desktop.
- **Dark Mode**: Includes a theme toggle to switch between light and dark modes.
- **Projects Section**: Highlights key projects with descriptions, tags, and links to code or live previews.
- **Experience Section**: Showcases professional experience with detailed descriptions.
- **Social Links**: Easy access to LinkedIn, GitHub, and email.

## Tech Stack

- **Astro**: A modern static site generator for fast and optimized websites.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **TypeScript**: For type-safe JavaScript development.

## Project Structure

The project follows a modular structure for better maintainability:

```
portfolio-dev/         # Root directory of the project
├── astro.config.mjs   # Astro configuration file
├── package.json       # Project dependencies and scripts
├── README.md          # Project documentation
├── tsconfig.json      # TypeScript configuration file
├── public/            # Publicly accessible files
│   ├── favicon.svg    # Website favicon
│   ├── og-image.jpg   # Open Graph image for social sharing
│   └── projects/      # Project-specific assets
│       ├── password-generator.webp
│       └── svgl.webp
├── src/               # Source files
│   ├── assets/        # Static assets like images and icons
│   │   ├── astro.svg
│   │   └── background.svg
│   ├── components/    # Reusable UI components
│   │   ├── Badge.astro
│   │   ├── Experience.astro
│   │   ├── ExperienceItem.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   ├── LinkButton.astro
│   │   ├── Projects.astro
│   │   ├── SectionContainer.astro
│   │   ├── SocialPill.astro
│   │   ├── ThemeToggle.astro
│   │   └── icons/     # Icon components
│   │       ├── Briefcase.astro
│   │       ├── Code.astro
│   │       ├── CSS.astro
│   │       ├── GitHub.astro
│   │       ├── HTML.astro
│   │       ├── JavaScript.astro
│   │       ├── Link.astro
│   │       ├── LinkedIn.astro
│   │       ├── Mail.astro
│   │       ├── Moon.astro
│   │       ├── NextJS.astro
│   │       ├── ProfileCheck.astro
│   │       ├── Sun.astro
│   │       ├── System.astro
│   │       └── Tailwind.astro
│   ├── layouts/       # Layout components for pages
│   │   └── Layout.astro
│   ├── pages/         # Website pages
│   │   └── index.astro
│   └── styles/        # Global and component-specific styles
│       └── global.css
```

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone git@github.com:MarkelK14/portfolio-dev.git
   ```

2. Navigate to the project directory:
   ```bash
   cd portfolio-dev
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:4321`.

## Build

To build the project for production:
```bash
npm run build
```

The output will be in the `dist/` directory.

## License

This project is for personal use and is not licensed for commercial purposes.