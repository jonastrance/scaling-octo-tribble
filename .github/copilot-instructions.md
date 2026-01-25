# Copilot Instructions for MK Property Services LLC Website

## Project Overview
This is a simple, static HTML/CSS website for MK Property Services LLC, a property management company serving Northern Neck, Virginia. The site provides information about services, company details, and a contact form.

## Technology Stack
- **Frontend:** Pure HTML5 and CSS3 (no frameworks)
- **No build process:** Direct file serving
- **Testing:** Manual browser testing

## File Structure
- `index.html` - Main HTML page with all content sections
- `styles.css` - All styling and responsive design
- `README.md` - Project documentation

## Coding Standards

### HTML Guidelines
- Use semantic HTML5 elements (`<section>`, `<nav>`, `<footer>`, etc.)
- Include proper meta tags for SEO and accessibility
- Use meaningful `id` and `class` names that describe content/purpose
- Maintain accessibility with ARIA labels and alt text where needed
- Keep form elements accessible with proper labels (use `.sr-only` class for visually hidden labels)

### CSS Guidelines
- Follow mobile-first responsive design approach
- Use CSS custom properties (variables) for colors and common values when appropriate
- Keep selectors specific but not overly nested
- Use flexbox and CSS Grid for layouts
- Maintain consistent spacing and typography
- Group related styles together with comments

### Code Organization
- Keep HTML structure clean and well-indented (4 spaces)
- Use comments to separate major sections in both HTML and CSS
- Maintain consistent naming conventions (kebab-case for classes and IDs)

### Responsive Design
- Ensure mobile compatibility with appropriate breakpoints
- Use relative units (rem, em, %) for better scalability
- Test layouts across different viewport sizes

## Best Practices
- **Simplicity:** This is a static site - avoid suggesting complex frameworks or build tools
- **Accessibility:** Ensure all changes maintain or improve accessibility
- **SEO:** Maintain proper meta tags and semantic HTML structure
- **Performance:** Keep CSS and HTML optimized and minimal
- **Browser Compatibility:** Use widely supported CSS and HTML features

## Restrictions
- Do not add JavaScript unless absolutely necessary
- Do not introduce build tools or package managers
- Do not modify the core business information without explicit instruction
- Keep the site simple and maintainable

## Testing
- View the website by opening `index.html` in a browser
- Test responsive design at various screen sizes
- Verify all links and form elements work correctly
- Check accessibility with browser dev tools
