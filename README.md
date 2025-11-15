# Personal Portfolio

A modern, responsive portfolio website built with Astro, featuring a clean design and showcasing projects, blog posts, and contact information.

## Live Demo

[Live Demo](https://jrreda.netlify.app/)

## ✨ Features

- Clean, modern portfolio design
- Project showcase section
- Blog with dynamic routing
- Contact page
- Responsive layout
- Reusable component architecture

## 🚀 Project Structure

```text
/
├── public/
│   ├── favicon.svg
│   ├── images/          # Project and blog images
│   └── resume.pdf       # Downloadable resume
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   ├── Navbar.astro
│   │   ├── Footer.astro
│   │   ├── BlogSection.astro
│   │   ├── BlogCard.astro
│   │   ├── MyProjectsSection.astro
│   │   ├── ProjectCard.astro
│   │   └── ...
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       ├── index.astro      # Home page
│       ├── projects.astro   # Projects page
│       ├── blog.astro       # Blog listing
│       ├── blog/
│       │   └── [slug].astro # Dynamic blog posts
│       └── contact.astro    # Contact page
└── package.json
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 🛠️ Tech Stack

- [Astro](https://astro.build) - Static Site Generator
- HTML/CSS/JavaScript
- Component-based architecture
- Netlify for deployment

## 📝 Customization

To customize this portfolio for your own use:

1. Update personal information in the header and footer components
2. Add your projects in the projects section
3. Create blog posts in the blog directory
4. Replace images in `/public/images/` with your own
5. Update `resume.pdf` with your own resume

## 👀 Want to learn more?

Feel free to check [Astro documentation](https://docs.astro.build) or jump into the [Astro Discord server](https://astro.build/chat).
