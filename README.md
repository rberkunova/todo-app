This **Todo App** is built using **React** and **TypeScript**, providing seamless task management with real-time API interactions. The application loads todos from an API, displaying them dynamically while ensuring error handling through user-friendly notifications that disappear automatically after a delay. Users can filter tasks by status, add new todos with validation, delete single or multiple completed todos, and toggle their completion status. The app also supports bulk status toggling while optimizing API calls. Editing functionality allows renaming todos via double-click, automatically saving changes on blur or Enter key press, and canceling edits with the Escape key. The UI ensures a smooth experience by implementing loading indicators, disabled controls during API requests, and focus management, preventing duplicate actions and enhancing usability.

[DEMO_LINK}\](https://rberkunova.github.io/todo-app/)

## How to Run the Project Locally

Follow these steps to clone and run the project on your local machine.

### Prerequisites

Ensure you have the following installed on your machine:
- **Node.js**: Version `14.21.3` or higher.
- **Git**: For cloning the repository.

You can check your current Node.js version by running:

```bash
node -v
```

If you don't have Node.js installed, download it from the [official website](https://nodejs.org/).

### Clone the Repository

1. Open your terminal.
2. Navigate to the directory where you want to store the project.
3. Run the following command to clone the repository:

```bash
git clone <repository-url>
```

Replace `<repository-url>` with the actual URL of your GitHub repository.

### Navigate to the Project Directory

Once the repository is cloned, navigate to the project directory:

```bash
cd <project-folder>
```

Replace `<project-folder>` with the name of the cloned repository folder.

### Install Dependencies

Install the required dependencies by running:

```bash
npm install
```

This will install all the packages specified in the `package.json` file.

### Run the Project

Start the development server with the following command:

```bash
npm start
```

This will start the project, and you can view it in your browser at:

```
http://localhost:3000
```

> Note: The default port is `3000`. If it's already in use, the application will suggest another port.

### Build for Production

To build the project for production, run:

```bash
npm run build
```

This will create an optimized build of the project in the `build` directory.

### Troubleshooting

- If you encounter any issues, ensure your Node.js version is correct.
- Delete the `node_modules` folder and reinstall dependencies if needed:

  ```bash
  rm -rf node_modules
  npm install
  ```
