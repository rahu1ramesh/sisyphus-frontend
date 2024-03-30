# Sisyphus Frontend

Welcome to the Sisyphus Frontend repository! This repository contains the frontend codebase for our habit tracking web application built using Vue.js.

## Project Overview

The Sisyphus is a web application designed to help users track their habits and monitor their progress over time. Users can create habits, set goals, and visualize their progress through intuitive charts and graphs.

## Installation

To set up the frontend environment locally and start developing, follow these steps:

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/your-username/habit-tracker-frontend.git
   ```

2. **Navigate to Project Directory**:
   ```bash
   cd habit-tracker-frontend
   ```

3. **Install Dependencies**:
   ```bash
   npm install
   ```

4. **Start Development Server**:
   ```bash
   npm run serve
   ```

5. **Access the Application**:
   Open your web browser and navigate to `http://localhost:8080` to view the Sisyphus application.

## Usage

Once the frontend environment is set up and the development server is running, you can start exploring and developing features for the Sisyphus application.

### Folder Structure

- `public/`: Contains static files that are directly copied to the build output.
- `src/`: Contains the main source code for the Vue.js application.
  - `assets/`: Contains static assets like images, fonts, etc.
  - `components/`: Contains Vue components for building the UI.
  - `router/`: Contains Vue Router configuration and routes.
  - `store/`: Contains Vuex store configuration and modules.
  - `views/`: Contains Vue components representing different views or pages of the application.

### Development Guidelines

- **Vue Components**: Create reusable Vue components for different UI elements.
- **Vuex Store**: Use Vuex for state management, especially for managing user authentication state and application data.
- **Vue Router**: Configure Vue Router for client-side routing and navigation within the application.
- **API Integration**: Interact with the backend API endpoints using Axios or Vue Resource for fetching and sending data.
- **Styling**: Use CSS or pre-processors like SASS/SCSS for styling components and pages. Consider using utility classes or a CSS framework for consistency.
- **Responsive Design**: Ensure the application is responsive and works well on various screen sizes by using media queries and flexbox/grid layout.

### Deployment

To deploy the frontend application to a production environment, build the application for production using:
```bash
npm run build
```
This command will generate a production-ready build in the `dist/` directory. You can then deploy this build to a web server or a cloud platform of your choice.

## Contributing

Contributions to the Sisyphus Frontend are welcome! If you have any ideas, bug fixes, or new features to propose, please open an issue or submit a pull request. We appreciate your contributions to making the application better for everyone.

## License

This project is licensed under the [MIT License](LICENSE).