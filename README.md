# Productiv

This is a Vue.js project deployed on [Vercel](https://vercel.com/) and available at [productiv.vercel.app](https://productiv.vercel.app).

## Table of Contents

- [Project Overview](#project-overview)
- [Login Credentials](#login-credentials)
- [Live Demo](#live-demo)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Deployment](#deployment)
- [License](#license)

## Project Overview

This project is a Pomodoro Task-list application with the following features:
- Task-synchronised 'black out' Pomodoro
- Guided breathing meditation timer
- Data analytics of time spent in meditation and productivity
- Social Leaderboard
- Built in music player with soundtracks
- Focus mode reminders

The intent for this app is to enable the users to:
1) Understand their productivity through:
   1. Pomodoro-synchronised task lists and items
   2. Data analytics derived from time recorded on each task and mindfulness
2) Enable focus through:
   1. Black Out Pomodoro timers
   2. Webpage monitoring Focus reminders
   3. Built in music player with focus soundtracks
3) Relax and recover through:
   1. Visual guided meditation timer utilising box breath
   2. Built in relaxation music
- Leverage motivation and connect with peers via our leaderboards

## Login Credentials

- Email: tester@email.com
- Password: banana

## Live Demo

Access the live project here: [productiv.vercel.app](https://productiv.vercel.app)

## Technologies Used

- **Vue.js**: JavaScript framework for building interactive user interfaces
- **Pinia**: State management library for Vue
- **Vue Router**: Handles application routing
- **Shadcn, TailWind, CSS**: For page styling
- **Vercel**: Deployment and hosting platform

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/JameszLau/productiv.git
   ```
2. Navigate to the project directory:
   ```bash
   cd productiv
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

The app should now be running on [localhost:5173](http://localhost:5173).

### Available Scripts

- `npm run serve` - Runs the app in development mode.
- `npm run build` - Builds the app for production.
- `npm run lint` - Lints your code for style and potential issues.

## Deployment

The project is automatically deployed on Vercel whenever there are changes to the main branch. Any commits pushed to the main branch are built and deployed to [productiv.vercel.app](https://productiv.vercel.app).

## License

This project is licensed under the [MIT License](LICENSE).
