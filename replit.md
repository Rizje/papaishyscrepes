# Papa Ishy's Crepes Website

## Overview
This is a static website for Papa Ishy's Crepes, a crepe business located in San Leandro, CA. The site showcases their menu, ordering information, and social media links with a beautiful vintage-themed design featuring falling petal animations.

## Project Structure

### Main Files
- `index.html` - Homepage with business introduction, special offers, and social media links
- `menu/index.html` - Menu page displaying the crepe menu with a magnifying glass feature
- `how-to-order/index.html` - Order information page with contact details and payment methods
- `server.py` - Python HTTP server serving static files on port 5000
- `attached_assets/` - Directory containing fonts, images, and menu PDF

### Technology Stack
- **Backend**: Python 3.11 HTTP server (http.server module)
- **Frontend**: HTML5, CSS3, vanilla JavaScript
- **Server Port**: 5000 (bound to 0.0.0.0)
- **Deployment**: Autoscale configuration

## Features
- Responsive design for mobile, tablet, and desktop
- Falling petal animations (disabled for users who prefer reduced motion)
- Loading screens with animated dots
- Custom fonts and vintage aesthetic
- Special offers dropdown
- Menu magnifying glass feature for detailed viewing
- Cache-control headers to prevent caching issues

## Setup
The project is configured to run in Replit:
1. Python 3.11 is installed as the runtime
2. Server runs on port 5000 with 0.0.0.0 host binding
3. Cache control headers are set to prevent stale content
4. Workflow automatically starts the server

## Deployment
The site is configured for autoscale deployment, which is ideal for this stateless static website. The deployment runs `python server.py` to serve the content.

## Recent Changes
- October 2, 2025: Menu page layout update
  - Removed scroll ability on menu page (overflow: hidden)
  - Repositioned "view in full screen" link directly below menu image
  - Created "What you're getting" dropdown button for example images
  - Dropdown appears above button with scrollable content
  - Improved layout with better spacing

- October 2, 2025: GitHub import setup
  - Fresh clone from GitHub repository
  - Installed Python 3.11 module
  - Created .gitignore for Python files
  - Configured workflow for server on port 5000
  - Set up autoscale deployment configuration
  - Verified all pages load correctly (homepage, menu, and how-to-order)
