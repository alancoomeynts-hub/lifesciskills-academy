# AI Coding Guidelines for LifeSciSkills Academy Website

## Project Overview
This is a static website built with Bootstrap 5.3.8 and custom CSS, showcasing life sciences training programs. No build tools or frameworks beyond Bootstrap - edit HTML/CSS directly.

## Page Structure
All pages follow this template:
- **Head**: Meta tags, favicons, Bootstrap CSS, custom `assets/css/style.css`
- **Nav**: Fixed-top dark navbar with offcanvas mobile menu (copy from `index.html`)
- **Body**: `d-flex flex-column min-vh-100` for sticky footer
- **Main**: Sections with `container content-padding` class
- **Footer**: Shared footer (copy from `index.html`)

## Styling Conventions
- **Colors**: Use CSS variables (`--primary`, `--secondary`, `--background`, `--tertiary`, `--highlight`)
- **Fonts**: `Inter` for body text, `DM Serif Display` for headings
- **Buttons**: `.custom-btn` (gold on navy) or `.custom-btn-main` (navy on gold)
- **Responsive**: Bootstrap grid (`col-12 col-md-6`), mobile-first
- **Images**: Store in `assets/images/`, use descriptive alt text

## Common Patterns
- **Forms**: Bootstrap form controls, `required` attributes, GET method for enquiries
- **Tables**: `.table.table-hover` for event listings
- **Cards**: `.card` with `.card-img-top` and `.card-body` for course previews
- **Tabs**: Bootstrap nav-pills for course details (see `courses.html`)
- **Carousel**: Hero carousel with glassmorphic captions (backdrop-filter blur)
- **Accessibility**: Ensure `aria-labelledby` matches the `id` of the referenced element (e.g., offcanvas title)

## Adding New Pages
1. Copy structure from existing page
2. Update nav active link and title
3. Use consistent section IDs and classes
4. Ensure mobile responsiveness with Bootstrap utilities
5. Follow heading hierarchy: One `<h1>` per page, then `<h2>` for sections (e.g., course details in `courses.html`)

## Key Files
- `index.html`: Home with hero carousel and course/events previews
- `courses.html`: Tabbed course information with enquiry forms
- `events.html`: Event details and registration forms
- `assets/css/style.css`: Custom styles with color variables and button classes

Focus on Bootstrap components and custom CSS classes for consistent design.