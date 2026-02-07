# Joel Sander Portfolio

A modern, interactive portfolio website built with Astro and GSAP. This project showcases professional experience, education, and technical projects through a unique horizontal scrolling interface featuring glassmorphism design elements.

## Technologies Used

- **Astro**: A web framework for building content-driven websites with high performance.
- **GSAP (GreenSock Animation Platform)**: specialized animation library used for the horizontal scrolling mechanism via ScrollTrigger.
- **CSS3**: Custom styling implementing glassmorphism effects, responsive layouts, and bespoke typography.
- **TypeScript**: Utilized for type safety and robust code structure.

## Features

- **Horizontal Scrolling Navigation**: A distinctive scrolling experience that navigates horizontally through content sections.
- **Responsive Design**: Fully adaptive layout that maintains usability across desktop and mobile devices.
- **Glassmorphism UI**: A consistent aesthetic utilizing semi-transparent backgrounds and backdrop filters to create depth.
- **Content Sections**:
    - **Landing**: Introduction with gradient text effects.
    - **About**: Personal profile and professional summary.
    - **Education & Experience**: Detailed timeline of academic achievements and professional history, including roles at ValueMomentum and Chautauqua Institution.
    - **Projects**: Showcase of technical projects such as the AI Powered Recipe Manager and WolfPack fitness tracker.
    - **Quick Links**: Integrated access to professional profiles on GitHub and LinkedIn.

## Getting Started

Follow these instructions to set up the project locally.

### Prerequisites

Ensure effective Node.js and npm environments are set up on your machine.

### Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the necessary dependencies:

   ```bash
   npm install
   ```

### Development

To start the local development server with hot module replacement:

```bash
npm run dev
```

The application will be accessible at `http://localhost:4321`.

### Building for Production

To create an optimized production build:

```bash
npm run build
```

The built files will be output to the `dist/` directory.

### Preview

To preview the production build locally before deployment:

```bash
npm run preview
```

## Project Structure

The project follows a standard Astro directory structure:

- **src/pages/**: Contains route components. `index.astro` serves as the main entry point.
- **src/components/**: Houses reusable UI components, including the core `HorizontalScroll.astro` logic.
- **src/assets/**: Storage for static assets such as images and fonts.
- **src/layouts/**: Shared layout templates for consistent page structure.
- **public/**: Static assets that are served directly.

## License

All rights reserved.
