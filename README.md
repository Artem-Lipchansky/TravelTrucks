# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


Project Overview
"TravelTrucks" offers users the chance to rent camper vans for their travels. Through this web application, users can explore different camper models, read user reviews, and book their preferred vehicle online.

Technologies Implemented
React – a library for building user interfaces.
Redux Toolkit – for state management.
React Router – for page navigation.
Axios – for handling HTTP requests.
Redux Persist – used to store the Redux state in local storage.
CSS/SCSS – for component styling via style modules.
Steps to Launch the Project:
Clone the repository:

Use the following command to clone the repository:

bash
Copy code
git clone [repository URL]
Navigate to the project directory:

bash
Copy code
cd [project directory name]
Install the dependencies:

Run this command to install all necessary dependencies:

bash
Copy code
npm install
Start the project:

Run the project in development mode:

bash
Copy code
npm start
The application will be available at: http://localhost:3000.

Interface Navigation:
Once the application is running, you can access the following pages:

Home Page:

Displays the project’s banner. Click the "View Now" button to access the catalog of all available campervans for rent.

Catalog:

A page showcasing all available vehicles, with filters based on various criteria (location, vehicle type, availability of air conditioning, kitchen, etc.). You can also add favorite campers.

Details Page:

Provides detailed information about each camper, including an image gallery, description, reviews, and a booking form.