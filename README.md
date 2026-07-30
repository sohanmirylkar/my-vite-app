# Digital Library

**[Try the live library demo](https://sohan-live-project-lab.miryalkarsohan.chatgpt.site/#library)**

A multi-page React application for browsing books and interacting with a simple digital-library interface. The project replaces the default Vite starter with routed pages, reusable components, login state, feedback, and contact flows.

## Features

- Responsive home and navigation experience
- Browsable book collection
- Client-side routing with React Router
- Simple login state shared with book interactions
- About, contact, and feedback pages
- Reusable header and page components
- Fast local development through Vite

## Technology

React, React Router, Vite, JavaScript, CSS, and ESLint.

## Project structure

```text
.
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── App.jsx
│   └── main.jsx
├── index.html
├── package.json
└── vite.config.js
```

## Getting started

```bash
git clone https://github.com/sohanmirylkar/my-vite-app.git
cd my-vite-app
npm install
npm run dev
```

Open the local URL printed by Vite.

## Commands

```bash
npm run dev      # Start the development server
npm run build    # Create a production build
npm run lint     # Run ESLint
npm run preview  # Preview the production build
```

## Current scope

Authentication and catalog behavior are front-end demonstrations. A production version would connect them to a persistent API and database, use secure sessions, and include automated component tests.

## Author

Sohan Miryalkar
