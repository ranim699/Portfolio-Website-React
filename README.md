# Personal Portfolio Website (React)

> A modern one-page website that presents a CV, projects, skills and a contact form.

## Origin

Based on a repository by [ranim699](https://github.com/ranim699), used as a template. The texts, images and links it contains still have to be replaced with your own content.

## What it does

The page consists of sections (hero, about, services, skills, projects, contact) with scroll animations. The content is kept in separate data files, so it is easy to adapt.

## Tech stack

| Technology | Used for |
|---|---|
| React | JavaScript library – the page is built from components. |
| JavaScript (ES6) | Logic, data arrays, `import`/`export`. |
| CSS | One stylesheet per component (`src/styles/`). |
| Framer Motion | Animations while scrolling. |
| npm / Node.js | Package management and development server. |

## Project structure

| Path | Content |
|---|---|
| `src/components/` | Components: Navbar, HeroSection, About, Skills, Works, Contact. |
| `src/data/` | Content: `ResumeData.js`, `SkillsData.js`, `WorkData.js` – put your own data here. |
| `src/styles/` | CSS files. |
| `public/` | `index.html` and images. |

## How to run

1. Install Node.js (LTS).
2. Open a terminal in the folder and run `npm install`.
3. Run `npm start` and open http://localhost:3000.
4. `npm run build` creates the finished site for hosting (e.g. GitHub Pages, Netlify).

## Key concepts

- Components and props in React.
- Separating data and presentation.
- Turning arrays into elements with `.map()`.

## Known issues

- Still contains the original author's texts, images and links – replace everything.
- The contact form uses FaunaDB (`submitComment.js`); this service has been shut down – replace it (e.g. with Formspree) or remove it.

## Ideas for improvements

- Add your own data (studies, skills, projects) in `src/data/` and choose your own colours.
- Make the language switchable.
- Publish the site and add the link to your CV.

## My changes

- _(describe here what you built or improved yourself)_
