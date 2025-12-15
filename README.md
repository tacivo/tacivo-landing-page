# Tacivo Landing Page

The official landing page for Tacivo - AI-powered tacit knowledge capture and preservation platform.

## Overview

Tacivo helps organizations capture and transform expert tacit knowledge into collective enterprise intelligence, accessible to teams, new hires, and AI systems.

## Tech Stack

- **Framework**: Next.js 15.5.7 (App Router)
- **React**: 18.3.1
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **Icons**: Lucide React
- **Deployment**: Vercel

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the landing page in your browser.

### Build

```bash
npm run build
```

### Production

```bash
npm start
```

## Project Structure

```
├── app/                  # Next.js app directory
├── components/
│   ├── landing/         # Landing page sections
│   │   ├── HeroSection.tsx
│   │   ├── PlatformSection.tsx
│   │   ├── HowItWorksSection.tsx
│   │   ├── ProblemSection.tsx
│   │   ├── StatsSection.tsx
│   │   ├── CTASection.tsx
│   │   └── Navbar.tsx
│   └── ui/              # shadcn/ui components
├── public/              # Static assets
│   └── assets/
│       └── logo/
└── tailwind.config.js   # Tailwind configuration
```

## Features

- Responsive design optimized for mobile, tablet, and desktop
- Mobile-friendly navigation with hamburger menu
- Calendly integration for demo bookings
- Custom color palette with book-cloth, kraft, and slate themes
- Animated components and transitions
- Built on proven knowledge frameworks (SECI Model, Cognitive Task Analysis)

## Deployment

The site is deployed on Vercel at [tacivo.com](https://tacivo.com).

## Contact

For demo requests or inquiries, visit [https://calendly.com/hello-tacivo/30min](https://calendly.com/hello-tacivo/30min)
