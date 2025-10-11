# Couria Partners Limited - Corporate Website

## Overview

Couria Partners Limited is a modern, responsive corporate website showcasing a technology company specializing in logistics solutions, software development, and business process automation. The website is built with vanilla HTML, CSS, and JavaScript, featuring a clean, professional design with modern UI patterns.

The website consists of three main pages:
- **Home** (`index.html`) - Landing page with hero section and core service pillars
- **Services** (`services.html`) - Detailed breakdown of service offerings with feature lists
- **Contact** (`contact.html`) - Contact form for potential clients

This is a client-side only application with no backend infrastructure currently implemented.

## Recent Changes (October 2025)

- Complete website redesign with modern UI/UX
- Fixed file structure (separated pages into individual HTML files)
- Enhanced CSS with Google Fonts (Inter & Space Grotesk)
- Added responsive design for mobile and tablet devices
- Implemented gradient backgrounds and smooth animations
- Created comprehensive services page with detailed offerings
- Set up Python HTTP server workflow on port 5000
- Removed image dependencies in favor of emoji icons

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture

**Technology Stack:**
- Pure HTML5 for page structure
- CSS3 with custom properties (CSS variables) for styling
- Vanilla JavaScript for form handling
- Google Fonts (Inter and Space Grotesk) loaded via CDN

**Design System:**
- Color scheme defined in CSS variables:
  - Primary: `--couria-blue` (#004d80)
  - Accent: `--couria-orange` (#e76f51)
  - Supporting: light, text, and white variants
- Modern shadow system with three levels (sm, md, lg)
- Typography hierarchy using two font families (Inter for body, Space Grotesk for headings)
- Responsive breakpoints at 768px and 480px
- Grid and flexbox-based layouts

**Page Structure:**
- Consistent header/navigation across all pages with sticky positioning
- Hero sections with gradient backgrounds
- Grid-based layouts for service pillars and feature cards
- Form-based contact page with modern styling and transitions
- Comprehensive footer with contact information

**Visual Design:**
- Gradient backgrounds on hero sections
- Smooth hover animations and transitions
- Card-based layouts with elevation effects
- Emoji icons (🚚 💻 ⚙️ 🔌) as visual elements
- Modern spacing and typography scale

**Form Handling:**
- Client-side JavaScript form submission prevention
- Console logging of form data (no backend submission)
- Alert-based user feedback
- Form reset after submission

**Current Limitations:**
- No actual form submission to backend
- Emoji icons instead of custom graphics
- Static content with no dynamic data loading
- No state management or routing (multi-page traditional navigation)
- No build process or bundling

### Workflow Configuration

**Development Server:**
- Python HTTP server running on port 5000
- Command: `python -m http.server 5000`
- Configured as "Website" workflow with webview output

### Data Architecture

**Current State:**
- No database implementation
- No data persistence layer
- Form data is captured but not stored anywhere
- All content is hardcoded in HTML files

**Future Considerations:**
- Contact form submissions need backend API endpoint
- Email notification system for form submissions
- Potential integration with email services (SendGrid, Mailgun, or SMTP)
- Analytics integration (Google Analytics)

### Authentication & Authorization

Not implemented. The website is completely public with no restricted areas or user authentication.

## External Dependencies

### Third-Party Services

**Google Fonts:**
- Inter font family (weights: 400, 500, 600, 700)
- Space Grotesk font family (weights: 500, 700)
- Loaded via CDN from `fonts.googleapis.com`

### Future Integration Opportunities

**Potential Services:**
- Form backend service (e.g., Formspree, Basin, or custom API)
- Email service integration
- Analytics platform
- CDN for static assets
- Professional image/icon assets to replace emoji placeholders

### Development Dependencies

None currently specified. The project uses no package managers, build tools, or frameworks. It's designed to run directly in a browser without compilation or transpilation. The Python HTTP server is used only for local development serving.
