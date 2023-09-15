This project is initiated using Create React App, a tool that simplifies React application setup. Here are the essential scripts for the project to run:

##npm start: This command launches the development server and runs the app in development mode. We can access it at http://localhost:3000, and any code changes will trigger an automatic page reload. Any linting errors will be displayed in the console.

##npm test: Running this script starts the test runner in an interactive watch mode, allowing us to run and monitor tests for our application.

##npm run build: Use this command to build the app for production. It optimizes the build, including minification to reduce file sizes and includes hash values in filenames for cache management. Now the app will be ready for deployment in the build folder.

##npm run eject: Note that ejecting is a one-way operation. If not satisfied with the default configuration and build tools, this command copies all configuration files and dependencies (e.g., webpack, Babel, ESLint) into the project. It gives us full control over these configurations, but we won't be able to revert to the default setup. Ejecting is typically reserved for advanced customization needs.

While ejecting provides extensive customization options, it's not required for most projects. Create React App offers a curated set of features suitable for small to medium deployments, and we can use it effectively without the need to eject.
