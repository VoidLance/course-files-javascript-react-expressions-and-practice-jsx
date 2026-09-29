# Expressions and Practice JSX

A small React learning project for practicing JavaScript expressions and JSX. The app presents an in-memory job list and lets users create jobs from the browser.

## Why this project is useful

- Demonstrates JSX expressions inside rendered content.
- Provides a focused example of React component composition (`App` and `CreateJob`).
- Shows event handling, `useState`, array rendering, and conditional text.
- Uses Create React App so learners can run and change the example with minimal setup.

Jobs are stored only in the current page session. A refresh clears the list, and each generated job title is a random number.

## Getting started

### Prerequisites

- Node.js and npm
- A modern web browser

### Install and run

From the project directory:

```bash
npm ci
npm start
```

Open [http://localhost:3000](http://localhost:3000). The development server reloads the page when source files change.

### Try the app

1. Select **Create Job**.
2. Observe the available-job count and new job in the list.
3. Select the button again to add another in-memory job.

## Available commands

| Command | Purpose |
| --- | --- |
| `npm start` | Start the development server. |
| `npm test` | Run the Jest test runner supplied by Create React App. |
| `npm run build` | Create an optimized production build in `build/`. |
| `npm run eject` | Copy Create React App configuration into the project. This is irreversible and normally unnecessary. |

## Project structure

```text
src/
├── App.js          # Root component and job-list state passed to CreateJob
├── CreateJob.js    # Job creation UI and JSX expression practice
├── App.css         # App-specific styles
├── index.css       # Global styles
└── index.js        # Browser entry point
public/             # Static HTML, icons, and manifest assets
```

The project uses React 19, React DOM, and `react-scripts` 5.0.1. Dependency versions and scripts are defined in [`package.json`](package.json); `package-lock.json` keeps installations reproducible.

## Help and documentation

For project-specific questions or bug reports, [open an issue](https://github.com/VoidLance/course-files-javascript-react-expressions-and-practice-jsx/issues). Useful external references include:

- [React documentation](https://react.dev/)
- [JSX documentation](https://react.dev/learn/writing-markup-with-jsx)
- [Create React App documentation](https://create-react-app.dev/docs/getting-started/)

## Contributing

Contributions are welcome. Before making a larger change, open an issue to discuss the proposed learning objective or behavior. For a pull request:

1. Create a focused branch from the default branch.
2. Make the smallest clear change that improves the example.
3. Run the relevant command from [Available commands](#available-commands).
4. Explain the change and verification steps in the pull request.

Please keep examples beginner-friendly and avoid adding dependencies unless they are necessary to demonstrate the lesson.

## Maintainer

This project is maintained by [VoidLance](https://github.com/VoidLance). See the repository’s issue tracker for current questions and proposed improvements.
