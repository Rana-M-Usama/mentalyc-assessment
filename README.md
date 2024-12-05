Mentalyc Assessment

This is the Mentalyc Assessment project, which contains React components, integrated with Storybook for component development and documentation. The project also includes a mocked design for easier UI and functionality testing.


Installation

Step 1: Clone the repository

Clone the repository to your local machine:
```bash
git clone https://github.com/yourusername/mentalyc-assessment.git
```
```bash
cd mentallyc-assessment
```
Step 2: Install dependencies

```bash
npm install
```
Or using yarn:


Step 3: Additional Setup (Optional)

    TailwindCSS Configuration: The project uses TailwindCSS for styling. Make sure your build system (via PostCSS) is correctly configured to compile Tailwind's styles.

    ESLint: The project uses ESLint to enforce consistent code quality. You can configure your editor to automatically lint your code or run the following command to lint manually:

    npm run lint

Usage
Running the Development Server


```bash
npm start
```
This will start the server and open the app in your default browser, typically at http://localhost:3000.
Running Storybook

Storybook is set up to display  React components in isolation. To start Storybook in development mode, run:
```bash
npm run storybook
```


This will open Storybook at http://localhost:6006, where you can browse through your components, interact with them, and view their documentation.
Running the Build Process

To build the project for production:
```bash
npm run build
```

