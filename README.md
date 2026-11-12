<div align="center">
  <h1>Card Project</h1>
  <p><strong>A clean, card-based showcase of job openings.</strong></p>
  <p>A React frontend prototype that presents sample roles with company details, employment tags, location, and hourly pay.</p>
  <p>
    <img src="https://img.shields.io/badge/React-19-149ECA?logo=react&logoColor=white" alt="React 19" />
    <img src="https://img.shields.io/badge/Vite-8-646CFF?logo=vite&logoColor=white" alt="Vite 8" />
    <img src="https://img.shields.io/badge/JavaScript-ESM-F7DF1E?logo=javascript&logoColor=111111" alt="JavaScript ES modules" />
    <img src="https://img.shields.io/badge/Icons-Lucide-111111?logo=lucide&logoColor=white" alt="Lucide icons" />
  </p>
</div>

---

## About

Card Project displays a set of sample job listings in a reusable card layout. Each card shows a company logo and name, posting date, role, employment type, seniority, hourly pay, and location.

The project is built with React and Vite, with job listing data defined in the app and passed into a reusable `Card` component.

## Features

- **Job listing cards** — View sample openings from companies including Google, Amazon, Microsoft, Apple, Meta, Netflix, Adobe, Salesforce, Uber, and LinkedIn.
- **Role details at a glance** — See posting date, job title, work type, seniority, hourly rate, and location.
- **Reusable React component** — Render each listing with the shared `Card` component.
- **Simple visual interactions** — Includes Save and Apply Now controls, plus a hover treatment on the apply button.
- **Fast development** — Use Vite for the local dev server and production build.

## Built with

| Area | Technology |
| --- | --- |
| UI | React 19 |
| Development and build | Vite 8 |
| Language | JavaScript with ES modules and JSX |
| Icons | Lucide React |
| Styling | CSS |

## Getting started

### Prerequisites

- Node.js and npm

### 1. Clone the repository

```bash
git clone https://github.com/Rahul-Negi-GitWork/Card-Project.git
cd Card-Project
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```

Open the local URL printed by Vite in your terminal.

## Available scripts

```bash
npm run dev      # Start the local development server
npm run build    # Create a production build
npm run preview  # Preview the production build locally
npm run lint     # Run ESLint
```

## Project structure

```text
src/
├── Components/
│   └── Card.jsx       # Reusable job listing card
├── assets/
│   ├── hero.png
│   ├── react.svg
│   └── vite.svg
├── App.jsx            # Sample job data and card list
├── App.css            # App-level styles
├── index.css          # Global and card styles
└── main.jsx           # React entry point
public/
├── favicon.svg
└── icons.svg
```

## Prototype notes

The job listings are sample data stored in `src/App.jsx`; the project does not currently connect to a jobs API or backend. The Save control is visual and does not persist saved jobs. Apply Now currently opens a generic Google account page rather than a job-specific application. These controls can be connected to real actions as the project grows.

## Contributing

Contributions and suggestions are welcome. Create a feature branch, make your changes, and open a pull request with a short description of the update.

## License

No license file is currently included. Add a `LICENSE` file to define the terms for using and redistributing this project.
