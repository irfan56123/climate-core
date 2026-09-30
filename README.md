
# ClimateCore – HVAC Business Website

A modern, responsive website for an HVAC (Heating, Ventilation, and Air Conditioning) business, designed to showcase services, communicate business information, and provide a professional digital presence.

**Live Demo:** [https://climate-core.vercel.app/](https://climate-core.vercel.app/)

---

## Overview

ClimateCore is a full-stack web application built to deliver a modern and user-friendly experience for an HVAC business.

The project combines a responsive frontend with a PostgreSQL database and Prisma ORM, using the Next.js ecosystem to build and manage the application.

## Tech Stack

### Frontend
- Next.js
- React
- TypeScript
- Tailwind CSS
- Framer Motion
- GSAP
- Lucide React

### Backend & Database
- Next.js
- PostgreSQL
- Prisma ORM
- Neon Database

### Tools & Services
- Git & GitHub
- Vercel
- Vercel Blob
- Resend

## Features

- Modern and responsive website design
- Mobile-friendly user interface
- HVAC business-focused presentation
- Smooth animations and interactive UI elements
- Full-stack architecture
- PostgreSQL database integration
- Prisma ORM for database management
- Production deployment with Vercel

## Getting Started

Follow these instructions to run the project locally.

### Prerequisites

Make sure you have the following installed:

- Node.js (LTS recommended)
- npm
- PostgreSQL database or Neon account
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/irfan56123/climate-core.git
```

### 2. Navigate to the Project

```bash
cd climate-core
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env` file in the root directory.

Add the environment variables required by your local configuration, such as your PostgreSQL connection string and authentication secrets.

Example:

```env
DATABASE_URL="your_postgresql_connection_string"
```

Refer to the project's Prisma configuration and authentication setup for any additional required variables.

**Important:** Never commit your `.env` file or expose database credentials and API keys.

### 5. Generate Prisma Client

```bash
npx prisma generate
```

### 6. Sync Database Schema

```bash
npm run db:push
```

### 7. Start Development Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start development server |
| `npm run build` | Build the application |
| `npm run start` | Start production server |
| `npm run lint` | Run ESLint |
| `npm run db:push` | Sync Prisma schema with database |
| `npm run db:seed` | Seed database |
| `npm run db:studio` | Open Prisma Studio |

## Deployment

The application is deployed on Vercel.

**Live Application:** https://climate-core.vercel.app/

For your own deployment:
1. Import the repository into Vercel.
2. Configure the required environment variables.
3. Connect your PostgreSQL database.
4. Deploy the application.

## Project Structure

```text
climate-core/
├── app/                 # Next.js App Router
├── components/          # Reusable UI components
├── prisma/              # Database schema and seed
├── public/              # Static assets
├── package.json
├── tsconfig.json
└── README.md
```

*Note: The structure above is a high-level overview. Actual folders may vary.*

## Author

**Irfan Ahmad**

B.Tech – Information Technology

- GitHub: [@irfan56123](https://github.com/irfan56123)
- Project: [ClimateCore](https://github.com/irfan56123/climate-core)

---

Built with Next.js, TypeScript, and PostgreSQL.
