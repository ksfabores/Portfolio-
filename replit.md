# Personal Portfolio Website

## Overview

This is a static personal portfolio website built with vanilla HTML, CSS, and JavaScript. The project uses a simple Python HTTP server for local development and hosting. The website features a modern, responsive design with sections for home, about, skills, and education.

## System Architecture

The application follows a simple client-side architecture:

- **Frontend**: Static HTML, CSS, and JavaScript files
- **Server**: Python HTTP server for development and deployment
- **Styling**: CSS with Google Fonts and Font Awesome icons
- **Interactivity**: Vanilla JavaScript for navigation and scroll effects

## Key Components

### 1. HTML Structure (`index.html`)
- Semantic HTML5 structure
- Responsive navigation with mobile menu
- Portfolio sections: Home, About, Skills, Education
- External dependencies loaded via CDN

### 2. Styling (`styles.css`)
- Modern CSS with Inter font family
- Responsive design principles
- Fixed navigation with backdrop blur effect
- CSS Grid and Flexbox for layout
- Smooth scrolling and transitions

### 3. JavaScript Functionality (`script.js`)
- Mobile menu toggle functionality
- Scroll-based navigation highlighting
- Dynamic navbar styling on scroll
- Event listeners for user interactions

### 4. Development Server (`.replit`)
- Python HTTP server running on port 5000
- Replit configuration for easy deployment
- Parallel workflow setup for development

## Data Flow

1. **Static Content Delivery**: HTML, CSS, and JS files served directly by Python HTTP server
2. **User Interactions**: JavaScript handles client-side navigation and UI updates
3. **External Resources**: CDN-hosted fonts and icons loaded asynchronously
4. **Responsive Behavior**: CSS media queries adapt layout based on screen size

## External Dependencies

- **Google Fonts**: Inter font family for typography
- **Font Awesome**: Version 6.0.0 for icons
- **Python**: Built-in HTTP server for development and deployment

## Deployment Strategy

The project uses Python's built-in HTTP server for both development and production:
- **Development**: `python -m http.server 5000`
- **Production**: Same command configured in Replit deployment settings
- **Static Hosting**: All assets served as static files
- **Port**: Application runs on port 5000

## Changelog

- June 14, 2025. Initial setup with complete portfolio sections
- June 14, 2025. Updated with user's professional photo and personalized with name "Dee Jay Catubig"

## User Preferences

Preferred communication style: Simple, everyday language.
User name: Dee Jay Catubig