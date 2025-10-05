# Papa Ishy's Crepes Website

## Overview
A static website for Papa Ishy's Crepes, a crepe business in San Leandro, CA. The site features:
- Home page with social media links and special offers
- Interactive menu with magnifying glass feature
- How to order page with contact information
- Animated falling petals background effect
- Mobile-responsive design

## Project Structure
- `index.html` - Main landing page
- `menu/index.html` - Menu display page
- `how-to-order/index.html` - Ordering information page
- `server.py` - Python HTTP server serving static files
- `attached_assets/` - Static assets (images, fonts, PDFs)
- `style.css`, `script.js` - Additional assets (currently minimal)
- `particles.js`, `particlesjs-config.json` - Particle animation configuration

## Technical Details
- **Language**: Python 3.11 (server), HTML/CSS/JavaScript (frontend)
- **Server**: Python's built-in HTTP server on port 5000
- **Host**: 0.0.0.0 (configured for Replit environment)
- **Cache Control**: Enabled in server.py to prevent caching issues

## Recent Changes
- 2025-10-05: Initial Replit setup
  - Installed Python 3.11
  - Created .gitignore for Python
  - Configured workflow to run server
  - Created replit.md documentation

## Running the Project
The project runs automatically via the configured workflow which executes `python server.py`.
The website is accessible on port 5000.
