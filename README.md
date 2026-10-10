# Ian Mwashanja Profile

A one-page semantic HTML5 personal profile and mini-portfolio website
showcasing my background, skills, education and contact information.

## About the Project

This project is a personal Profile/Mini-Portfolio website created as
part of my Unit II coursework.

The website uses semantic HTML5 elements to organize the page and
includes sections for my About Me, Skills, Education and Contact
Information.

## Technologies Used

- HTML5
- CSS3
- Git
- GitHub

## Website Features

- Semantic HTML5 structure
- Personal About Me section
- Skills section
- Education section
- Contact Me form
- Native HTML5 form validation
- Accessible form labels
- Meaningful image alternative text
- Responsive-friendly structure

## Project Structure

ian-mwashanja-profile/
1) index.html
2) style.css
3) README.md
4) PROMPT_LOG.md

## Responsive Notes

### Responsive Testing

The page was tested using the browser's device toolbar at the following viewport widths:

- Mobile: 375px
- Tablet: 768px
- Desktop: 1280px

Testing checked the navigation, text wrapping, image sizing, skills layout, education layout, contact form, and horizontal overflow.

### Flexbox

Flexbox is used in the navigation bar to align navigation links, create consistent spacing, and allow links to wrap when the available width is limited.

Flexbox is also used in the contact form fields to arrange labels and controls vertically.

### CSS Grid

CSS Grid is used in the Skills and Education sections.

The Skills section displays one column on mobile, two columns at tablet widths, and three columns on larger desktop screens.

The Education section uses one column on mobile and two columns on larger screens.

Grid was chosen because these sections contain cards arranged in rows and columns.

### Tailwind CSS

Tailwind utility classes are used in the header, navigation, contact form, submit button, and footer.

Responsive variants such as `md:py-14` and `md:text-5xl` adjust spacing and typography at larger screen widths.

### Custom CSS and Tailwind

Custom CSS is responsible for the main layout, Flexbox, Grid, form-field layout, visual details, and custom responsive breakpoints.

Tailwind is used for selected colours, spacing, typography, and button styling.

This division keeps the styling organised while demonstrating both custom CSS and utility-first styling.