# Family Safety Tracker

## Overview

A web-based family safety tracking application that provides real-time location monitoring and safety features for family members. The application uses interactive maps to display family member locations, status updates, and safety alerts in a user-friendly interface.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Single-Page Application (SPA)**: Built using React 18 for component-based UI development
- **Styling Framework**: Tailwind CSS for utility-first styling with custom CSS variables for consistent theming
- **JSX Transformation**: Babel standalone for in-browser JSX compilation, enabling rapid development without build tools
- **Responsive Design**: Mobile-first approach using Tailwind's responsive utilities

### Map Integration
- **Mapping Library**: Leaflet.js chosen for lightweight, open-source mapping capabilities
- **Interactive Features**: Real-time location display with custom markers and popups
- **Map Tiles**: Utilizes OpenStreetMap tiles for free, reliable map data

### Client-Side State Management
- **React State**: Component-level state management using React hooks
- **Local Storage**: Browser storage for persisting user preferences and temporary data
- **Real-time Updates**: Event-driven architecture for location updates and safety alerts

### UI/UX Design Patterns
- **Color System**: Custom CSS variables for consistent theming across primary, success, warning, and danger states
- **Component Architecture**: Modular React components for reusability and maintainability
- **Accessibility**: Semantic HTML structure with proper ARIA labels and keyboard navigation support

### Development Approach
- **No Build Process**: Direct HTML file with CDN dependencies for simplicity and immediate deployment
- **Progressive Enhancement**: Core functionality works without JavaScript, enhanced with React components
- **Cross-Browser Compatibility**: Uses stable, widely-supported library versions

## External Dependencies

### Core Libraries
- **React 18**: Frontend framework for component-based UI development
- **React DOM 18**: DOM rendering for React components
- **Babel Standalone**: In-browser JSX transformation and ES6+ compilation

### Mapping and Geolocation
- **Leaflet.js 1.9.4**: Open-source mapping library for interactive maps
- **OpenStreetMap**: Map tile provider for geographic data

### Styling and UI
- **Tailwind CSS**: Utility-first CSS framework via CDN
- **Custom CSS Variables**: Theme system for consistent color schemes

### Browser APIs
- **Geolocation API**: Native browser API for accessing device location
- **Local Storage API**: Browser storage for data persistence
- **Notification API**: Browser notifications for safety alerts

### CDN Services
- **unpkg.com**: Package delivery network for npm packages
- **Tailwind CDN**: CSS framework delivery
- **Integrity Hashes**: Subresource integrity for security verification of external scripts