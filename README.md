# Apple Website

This is a project aimed at replicating the Apple website using modern web development technologies.

## Table of Contents

- [Installation](#installation)
- [Available Scripts](#available-scripts)
- [Dependencies](#dependencies)
- [Development](#development)
- [Build](#build)
- [Preview](#preview)
- [Linting](#linting)

## Installation

To get started with the project, clone the repository and install the dependencies:

```
git clone https://github.com/yashjk/apple_website.git
cd apple_website
npm install
```

## Available Scripts
In the project directory, you can run the following scripts:

```
npm run dev
```
Runs the app in development mode.

The page will reload when you make changes. You may also see any lint errors in the console.

```
npm run build
```
Builds the app for production to the dist folder. It correctly bundles React in production mode and optimizes the build for the best performance.

```
npm run preview
```
Serves the production build from the dist folder. Useful for previewing the production build locally.

```
npm run lint
```
Runs ESLint to lint the project files and ensures code quality. The script includes the following options:

```
--ext js,jsx to specify the file extensions.
--report-unused-disable-directives to report unused ESLint directives.
--max-warnings 0 to treat warnings as errors.
```

## Dependencies
This project uses the following main dependencies:
- React: A JavaScript library for building user interfaces.
- Vite: A fast build tool that leverages the power of native ES modules.
- GSAP: A JavaScript library for creating high-performance animations.
- React Three Fiber: A React renderer for Three.js.
- Three.js: A JavaScript 3D library.
- Tailwind CSS: A utility-first CSS framework for rapid UI development.
- Sentry: A tool for real-time error tracking and debugging.

## Development
To run the app in development mode, use:

```
npm run dev
```
This will start the development server and open the application in your default browser. The server will automatically reload if you make changes to the code.

## Build
To create a production build, use:

```
npm run build
```

This will generate an optimized build in the dist folder.

## Preview
To preview the production build locally, use:

```
npm run preview
```

This will serve the production build on a local server.

## Linting
To check your code for errors and ensure code quality, use:

```
npm run lint
```

This will run ESLint with the configured options and report any issues found in the code.
