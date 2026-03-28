# TweetForge — AI Brand Tweet Generator

An AI-powered web application that generates engaging brand tweets. Built with React and Vite for fast, modern development.

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Development](#development)
- [Building for Production](#building-for-production)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## About

**TweetForge** is an innovative tool designed to help brands create compelling, AI-generated tweets. Whether you need content inspiration, quick tweet ideas, or consistent brand voice, TweetForge streamlines the tweet creation process with intelligent automation.

## Features

- 🤖 AI-powered tweet generation
- 📱 Responsive web interface
- ⚡ Fast, modern development experience with Vite
- 🎨 Clean and intuitive UI built with React
- 🚀 Ready for cloud deployment (Vercel-configured)

## Tech Stack

- **Frontend Framework:** React 18.2.0
- **Build Tool:** Vite 5.0.0
- **Runtime:** JavaScript
- **Markup:** HTML5
- **Styling:** CSS (component-based)
- **Deployment:** Vercel

## Project Structure

```
tweetforge2-main/
├── src/                    # React source code
│   └── main.jsx           # Application entry point
├── api/                   # Backend API endpoints (serverless functions)
├── index.html             # HTML template
├── package.json           # Project metadata & dependencies
├── vite.config.js         # Vite configuration
├── vercel.json            # Vercel deployment configuration
└── README.md              # Project documentation
```

## Getting Started

### Prerequisites

- **Node.js** (v14 or higher)
- **npm** or **yarn** package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/PolamreddyRohini/ai-tweet-tool.git
cd ai-tweet-tool/tweetforge2-main
```

2. Install dependencies:
```bash
pm install
```

## Development

Start the development server with hot module reloading:

```bash
pm run dev
```

The application will be available at `http://localhost:5173` (or the URL shown in your terminal).

## Building for Production

Create an optimized production build:

```bash
pm run build
```

This generates a `dist/` folder with minified and optimized assets.

### Preview Production Build

To preview the production build locally:

```bash
npm run preview
```

## Deployment

This project is configured for deployment on **Vercel**. 

### Deploy with Vercel

1. Push your code to GitHub
2. Connect your GitHub repository to Vercel
3. Vercel will automatically detect the configuration in `vercel.json` and deploy

Or deploy directly using the Vercel CLI:

```bash
npm i -g vercel
vercel
```

## Available Scripts

| Script | Description |
|--------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Create production build |
| `npm run preview` | Preview production build locally |

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is private. For licensing inquiries, please contact the repository owner.

---

**Author:** [PolamreddyRohini](https://github.com/PolamreddyRohini)  
**Repository:** [ai-tweet-tool](https://github.com/PolamreddyRohini/ai-tweet-tool)