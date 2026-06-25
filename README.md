# Ibad-ur-Rehman Rashid - Academic & Engineering Portfolio

This repository contains the source code for my personal portfolio, showcasing my research in Natural Language Processing (NLP), Agentic AI architectures, and Computational Linguistics, alongside my deployable systems engineering projects.

🌐 **Live Site:** [ebad-urrehman.github.io](https://ebad-urrehman.github.io)

## 🧠 Core Focus Areas
* **Arabic NLP:** Transformers, classification models, and cross-lingual generation detection.
* **Computational Linguistics:** Multi-hop reasoning evaluation and Perso-Arabic text processing.
* **Ontology Design & RAG:** Hierarchical knowledge graphs (QurSci-Onto) and Retrieval-Augmented Generation pipelines.
* **Systems Engineering:** Local AI agent frameworks, hardware-optimized Linux environments, and full-stack architectures.

## 🛠️ Tech Stack & Architecture
This site is built for speed, simplicity, and low overhead:
* **Framework:** [Astro](https://astro.build/) (Static Site Generation)
* **Interactive Elements:** Pure CSS/JS Cover Flow Carousel, `tsparticles` for the dynamic network constellation background.
* **Content Management:** Markdown-driven (`.md`) content collections for seamless updating of research papers and engineering projects.
* **Deployment:** Automated CI/CD pipeline via GitHub Actions to GitHub Pages.

## 📁 Content Management
To add a new project to the **Featured Engineering** carousel:
1. Navigate to `src/content/engineering/`.
2. Add a new `.md` file with the required frontmatter (`title`, `description`, `publishDate`, `img`, `repo_url`).
3. Add the corresponding screenshot to `public/assets/`.
4. Push to the `main` branch—the site will rebuild and update automatically.

## 💻 Local Development

If you are cloning this environment to run locally:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs all project dependencies                |
| `npm run dev`             | Starts the local dev server at `localhost:4321`  |
| `npm run build`           | Builds the production site to `./dist/`          |
| `npm run preview`         | Previews the production build locally            |

## 📄 License
This portfolio’s codebase is open-source, but personal assets, images, and specific research data remain the property of Ibad-ur-Rehman Rashid.