# Personal Website PRD

## Goal

Create a simple, professional, and personal portfolio website for Charles Tong. The website should introduce Charles, show his interests and course projects, and make it easy for visitors to contact him.

Version 1 will be a static website built with HTML, CSS, and a small amount of JavaScript, and hosted on GitHub Pages. It should be realistic to build, test, and complete for this course.

## Audience and key action

### Primary audience

Recruiters who want to quickly understand Charles's background, interests, and projects.

### Secondary audience

Classmates, professors, and anyone else who wants to learn more about Charles.

### Key action

Visitors should be able to view Charles's projects. They should also be able to learn about him and find his contact information easily.

## Pages

Version 1 will include four pages:

1. **Home**
   - Short introduction to Charles Tong
   - Clear link to view projects
   - Brief indication of his interests and background

2. **About Me**
   - Short personal introduction
   - Student status and academic context
   - Interests and hobbies, including entrepreneurship, business, technology, golf, travel, and cars
   - Photo, if Charles provides one

3. **Projects**
   - Projects or websites built for the course
   - A short description for each project
   - Links to live websites or repositories when available

4. **Contact**
   - Charles's email address
   - GitHub profile link
   - Any additional contact method Charles provides

## Navigation

- A consistent navigation bar will appear on every page.
- Navigation links will include Home, About Me, Projects, and Contact.
- The Projects link will be visually easy to find because viewing projects is the main visitor action.
- The site name, Charles Tong, will link back to Home.
- Navigation will work with keyboard focus and on mobile screens.
- Links to external websites, such as GitHub and project pages, will be clearly labeled.

## Content

| Content | Status | From whom |
| --- | --- | --- |
| Name: Charles Tong | Have | Charles Tong |
| Babson College student status | Have | Charles Tong |
| Interests: entrepreneurship, business, technology, golf, travel, and cars | Have | Charles Tong |
| Short personal introduction | Have, needs final wording | Charles Tong |
| Email address | Have: `ctong2@babson.edu` | Charles Tong |
GitHub profile URL | Have: https://github.com/Ctong0622 | Charles Tong
| Personal photo | Missing | Charles Tong |
| Project names | Missing | Charles Tong |
| Project descriptions | Missing | Charles Tong |
| Project links or repository URLs | Missing | Charles Tong |
| Any additional contact method | Missing | Charles Tong |

No jobs, awards, work experience, project outcomes, or other personal details will be added unless Charles provides them.

## Look

The visual direction should be clean, modern, professional, and personal. It should use generous whitespace, clear typography, and strong images when Charles provides them. The visual language may take inspiration from Apple's simple layouts and Porsche's modern presentation, without copying either site.

The initial CSS can use values similar to these in a `:root` block:

```css
:root {
  --color-background: #f7f8f5;
  --color-surface: #ffffff;
  --color-text: #17202a;
  --color-muted: #5f6b76;
  --color-accent: #d66b3d;
  --color-accent-dark: #a94b27;
  --color-border: #dfe4df;
  --content-width: 1080px;
  --space-section: 6rem;
}
```

The design should avoid unnecessary decoration, complicated animations, and crowded layouts. Content should be readable before visual effects are considered.

## Responsive design requirements

- The site must work on desktop, tablet, and mobile widths.
- Navigation must remain usable on small screens without overlapping or overflowing.
- Content should use a readable line length and comfortable spacing.
- Project cards, images, and other content must resize within the viewport.
- Text must not be clipped or overlap other content.
- Buttons and links must have comfortable touch targets.
- Images must include meaningful alternative text when used.
- The site must remain usable with keyboard navigation and visible focus states.

## Checks

A visitor must be able to:

1. Understand who Charles Tong is from the Home page.
2. Navigate to About Me, Projects, and Contact from every page.
3. View the available course projects and open their links when provided.
4. Read about Charles's interests and background.
5. Use the email link to contact Charles and open his GitHub profile once the URL is provided.

## Project requirements and constraints

- Use HTML, CSS, and a small amount of JavaScript only.
- Host Version 1 on GitHub Pages.
- Keep the implementation understandable for a course project.
- Keep Version 1 to four pages.
- Do not use a server, database, login system, payment system, or saved form data.
- Use a `mailto:` link instead of a server-backed contact form.
- Do not invent content, experience, awards, project details, or links.
- Keep visual effects simple and avoid complicated animations.
- Test the pages at desktop and mobile widths before submission.
- Ensure all internal links, external links, images, and contact links work.

## Out of scope

- Server-side features
- Database storage
- User accounts or login
- Payments or e-commerce
- A contact form that stores submissions
- A blog or content management system
- Advanced animations or interactive 3D content
- Invented portfolio projects or professional experience
- A large multi-page site beyond the four Version 1 pages

## Later

- Add complete project case studies with screenshots, process, and outcomes.
- Add a downloadable resume after Charles provides and approves it.
- Add a serverless contact form if a real submission workflow becomes necessary.
- Add analytics after deciding what visitor information is appropriate to collect.
- Add more projects, writing, or a blog as content becomes available.
- Refine the visual design after testing the first version with classmates, professors, or recruiters.
