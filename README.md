# SocietySync Prototype

A lightweight React prototype for a society-management web application. This repository is currently an early-stage frontend scaffold built with Vite, React, and Tailwind CSS.

The goal of SocietySync is to evolve into a clean, fast, and easy-to-use interface for managing society-related communication, events, notices, members, and day-to-day coordination workflows.

## Status

This project is in the prototype stage. The current codebase contains the base React/Vite setup, Tailwind configuration, and a minimal placeholder UI. The README has been structured to document the intended direction and make future development easier to continue.

## Tech Stack

- React 19
- Vite 7
- Tailwind CSS 3
- JavaScript / JSX
- ESLint
- PostCSS / Autoprefixer

## Project Structure

```text
SocietySync_Prototype/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
└── vite.config.js
```

## Getting Started

### Prerequisites

Make sure Node.js and npm are installed on your system.

```bash
node --version
npm --version
```

### Installation

Clone the repository:

```bash
git clone https://github.com/dev0302/SocietySync_Prototype.git
cd SocietySync_Prototype
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the local URL printed in the terminal, usually:

```text
http://localhost:5173
```

## Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Starts the Vite development server. |
| `npm run build` | Creates a production build. |
| `npm run preview` | Serves the production build locally for preview. |
| `npm run lint` | Runs ESLint across the project. |

## Planned Features

- Authentication screens
- Resident and member dashboard
- Society notices and announcements
- Event listing and event details
- Maintenance or request tracking
- Admin/member role-based views
- Responsive UI for mobile and desktop
- Reusable component structure

## Development Notes

The current UI is intentionally minimal. Before adding larger features, the next recommended step is to replace the placeholder `App.jsx` content with a proper layout and organize the frontend into reusable folders such as:

```text
src/
├── components/
├── pages/
├── layouts/
├── data/
├── hooks/
└── utils/
```

## License

No license has been added yet. Add one before using or distributing this project publicly.