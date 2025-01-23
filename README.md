## Prerequisites

Before you begin, ensure you have the following software installed on your system:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (usually installed along with Node.js)

## Installation

To set up this project in your local environment, follow these steps:

1. **Clone the Repository**
   ```bash
   https://github.com/damar-glh/greenlify.git
   cd greenlify
   ```

2. **Install Dependencies & Set Up Pre-commit Scripts**
   Run the following command to install all required dependencies and set up the pre-commit scripts and execution permissions:
   ```bash
   npm run setup
   ```
   
3. **Run the Application**
   Once the setup is complete, you can run the application using:
   ```bash
   npm run dev
   ```

   The application will run at `http://localhost:3000` (or the appropriate port specified by Vite).

## Running Linting and Formatting

Before committing, ensure you run linting and formatting on your code. You can do this by executing:
```bash
npm run fix
```

## Contact

If you have any questions or feedback, feel free to reach out to us at [ErsTalent].

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
