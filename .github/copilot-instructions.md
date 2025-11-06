# AI Agent Instructions for WEBD168 Project

This document provides essential guidance for AI agents working with this web development project.

## Project Structure

This is a progressive web development learning project organized by lessons:
- Each lesson folder (e.g., `lesson01`, `lesson02`, etc.) contains standalone web pages and assets
- CSS and image assets are organized within each lesson folder
- Main navigation and styles are consistently structured across lessons

## Key Patterns and Conventions

### CSS Organization
- Base styles are defined at the top of CSS files (reset, typography, basic elements)
- Component-specific styles follow (e.g., `.hero-image`, `.main-menu`)
- Responsive design patterns are placed at the bottom using media queries
- Example: See `lesson04/styles.css` for the full pattern implementation

### HTML Structure
- Common page structure:
  ```html
  nav > .main-menu
  .hero-image > .hero-text
  .container-fluid > main
  footer
  ```
- Font Awesome icons are used for visual elements
- Google Fonts integration for typography (Poppins, Style Script)

### Asset Management
- Images are stored in `images/` subdirectories within each lesson
- Hero images follow naming convention: `hero-{page}-image`
- CSS references images using relative paths

### Responsive Design
- Mobile-first approach with breakpoints at:
  - 600px for form elements
  - 768px for hero text and buttons
- Flexbox used for layout (`.main-menu`, `.main`)

## Common Tasks

### Adding New Pages
1. Copy the base HTML structure from an existing page
2. Update the hero image class and content
3. Maintain the common nav structure
4. Use existing CSS classes for consistency

### Styling Guidelines
- Use the established color palette:
  - Primary blue: `#90c7e3`
  - Accent color: `coral`
  - Text color: `#333`
- Maintain consistent spacing using the defined margins and paddings
- Follow the existing responsive design patterns

## Important Files
- `lesson04/index.html`: Reference for current best practices and structure
- `lesson04/styles.css`: Complete styling guide with latest patterns
- `lesson03-flexbox/`: Examples of flexbox layout implementations