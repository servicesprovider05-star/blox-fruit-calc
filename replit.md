# Blox Fruits Trading Calculator

## Overview

This is a full-stack Blox Fruits trading calculator web application built to help players determine fair trades in the Roblox game Blox Fruits. The application provides accurate fruit values, trade calculations, and W/L indicators to prevent users from getting scammed. It features a modern React frontend with shadcn/ui components and an Express.js backend with SEO optimization and AdSense readiness.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: React with TypeScript using Vite as the build tool
- **UI Library**: shadcn/ui components built on Radix UI primitives for accessible, customizable components
- **Styling**: Tailwind CSS with CSS variables for theming and responsive design
- **State Management**: TanStack Query (React Query) for server state management and caching
- **Routing**: Wouter for lightweight client-side routing
- **Theme System**: Custom theme provider supporting light/dark modes with localStorage persistence

### Backend Architecture
- **Framework**: Express.js with TypeScript for the API server
- **Data Layer**: In-memory storage implementation with predefined fruit and gamepass data
- **API Design**: RESTful endpoints for fruits, gamepasses, and trade values
- **SEO Features**: Server-side meta tag injection, sitemap generation, and structured data

### Data Management
- **Schema Validation**: Zod schemas for type-safe data validation and TypeScript type generation
- **Trade Logic**: Custom calculator for determining trade fairness based on fruit values and demand
- **Search & Filtering**: Client-side filtering by rarity, name search, and sorting capabilities

### Development Workflow
- **Build System**: Vite for fast development and optimized production builds
- **Database Migration**: Drizzle ORM configured for PostgreSQL (ready for future database integration)
- **Development Server**: Hot module replacement and error overlay for improved developer experience

### Styling System
- **Design Tokens**: CSS custom properties for consistent theming
- **Component Variants**: Class Variance Authority (CVA) for component styling variations
- **Responsive Design**: Mobile-first approach with Tailwind's responsive utilities
- **Typography**: Inter font family with carefully crafted font scales

## External Dependencies

### Core Dependencies
- **React Ecosystem**: React 18, React DOM, React Query for modern React patterns
- **UI Components**: Radix UI primitives for accessible, unstyled components
- **Validation**: Zod for schema validation and type safety
- **Styling**: Tailwind CSS, clsx, tailwind-merge for utility-first styling
- **Icons**: Lucide React for consistent iconography

### Development Tools
- **Build Tools**: Vite, esbuild for fast compilation and bundling
- **TypeScript**: Full TypeScript support across frontend and backend
- **Development Utilities**: Replit-specific plugins for enhanced development experience

### Future Integrations
- **Database**: Neon serverless PostgreSQL (currently configured but not active)
- **ORM**: Drizzle ORM ready for database operations
- **SEO**: Structured data, sitemaps, and meta tag management for search optimization
- **Analytics**: AdSense-ready configuration for monetization