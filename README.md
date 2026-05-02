# Job Tracker

A modern job application tracking web app built with React. Track your job search journey by managing your applications, monitoring interview progress, and analyzing your job hunt statistics.

![Job Tracker](https://img.shields.io/badge/React-19.x-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-8.x-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.x-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

## ✨ Features

- **📋 Application Management** - Add, track, and manage job applications
- **📊 Statistics Dashboard** - View summary stats for total applications, interviews, offers, and pending
- **🔄 Multiple View Modes** - Switch between Table view and Grid/Card view
- **📱 Responsive Design** - Works on desktop, tablet, and mobile devices
- **🗑️ Easy Deletion** - Delete applications with confirmation to prevent accidents
- **🎨 Modern UI** - Clean, professional interface with Tailwind CSS

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Navigate to the project directory:

```bash
cd job-tracker
```

2. Install dependencies:

```bash
npm install
```

### Running the App

Start the development server:

```bash
npm run dev
```

Open http://localhost:5173 in your browser to view the app.

### Building for Production

Create a production build:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

## 📁 Project Structure

```
job-tracker/
├── public/
│   ├── favicon.svg
│   └── icons.svg
├── src/
│   ├── components/
│   │   ├── JobBoard.jsx      # Main job listing component (table/grid views)
│   │   ├── JobCard.jsx       # Card view for individual jobs
│   │   ├── JobModal.jsx     # Modal form for adding new jobs
│   │   └── StatsDashboard.jsx # Statistics overview
│   ├── App.css
│   ├── App.jsx              # Main application component
│   ├── index.css
│   └── main.jsx             # Entry point
├── index.html               # HTML template
├── package.json             # Dependencies and scripts
├── vite.config.js          # Vite configuration
└── eslint.config.js        # ESLint configuration
```

## 🎯 Usage Guide

### Adding a Job Application

1. Click the **"Add Job"** button in the top-right corner
2. Fill in the company name and job role (both required)
3. Select the initial status (default: Applied)
4. Click **"Add Application"** to save

### Managing Applications

- **Update Status**: Use the dropdown in the table or card view to change status (Applied → Interview → Offer/Rejected)
- **Delete**: Click the trash icon, then confirm by clicking again within 3 seconds
- **Switch Views**: Toggle between Table view and Grid view using the view mode buttons

### Status Categories

| Status    | Description              |
| --------- | ------------------------ |
| Applied   | Application submitted    |
| Interview | Scheduled for interview  |
| Offer     | Received job offer       |
| Rejected  | Application not selected |

## 🛠️ Available Scripts

| Script            | Description              |
| ----------------- | ------------------------ |
| `npm run dev`     | Start development server |
| `npm run build`   | Create production build  |
| `npm run preview` | Preview production build |
| `npm run lint`    | Run ESLint               |

## 📦 Tech Stack

- **React 19** - UI Framework
- **Vite 8** - Build Tool
- **Tailwind CSS 3** - Styling (via CDN)
- **Lucide React** - Icons

## 🔧 Configuration

The project uses Tailwind CSS loaded via CDN in `index.html`. Custom colors are configured for the primary theme in the HTML head section.

## 📄 License

MIT License

---

Built with ❤️ using React and Vite
