# Piyush Singh — The Series

> A cinematic, streaming-inspired portfolio for **Piyush Singh** — a full-stack and AI/ML developer who enjoys turning useful ideas into polished products.

![Portfolio preview](public/assets/og-image.png)

[▶ Watch the portfolio walkthrough](Portfolio_Video.mp4)

This portfolio reframes the usual one-page résumé as a show to explore. Visitors move through an opening sequence, select a viewing profile, browse projects as “Originals,” and open detailed project and résumé experiences—all within a responsive, motion-led interface.

## Portfolio walkthrough

See the complete experience—from the opening sequence and profile selection to project exploration and résumé viewing—in the [portfolio video](Portfolio_Video.mp4).

## Highlights

- **Cinematic first impression** with an opening sequence and profile selector
- **Four tailored viewing profiles**—Piyush, Recruiter, Developer, and Creative—each with a different section order
- **Project originals** with technology stacks, build notes, outcomes, and links
- **Interactive résumé experience** with in-app viewing and PDF download
- **Portfolio story** covering education, experience, skills, certifications, and achievements
- **Smooth, accessible interactions** including reduced-motion support, lazy-loaded overlays, custom cursor effects, and responsive layouts

## Built with

- [React](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vite.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Framer Motion](https://www.framer.com/motion/) for transitions and layout animation
- [Lenis](https://lenis.darkroom.engineering/) for smooth scrolling

## Featured work

| Project | Focus | Core technologies |
| --- | --- | --- |
| **AURA Finance Controller** | Explainable, AI-assisted financial reconciliation | React, FastAPI, Python, Pandas, Docker, Three.js |
| **AI Learning Platform** | Multilingual document intelligence and study tools | React, Vite, FastAPI, SQLAlchemy, JWT |
| **AI-Based Project Management System** | Role-aware project tracking for students and faculty | React, Node.js, Express, MongoDB, JWT |
| **AutoML Studio** | Data profiling, preprocessing, and model comparison | Python, Streamlit, Pandas, scikit-learn, XGBoost |

## Run locally

### Prerequisites

- Node.js 18 or later
- npm

### Installation

```bash
git clone https://github.com/Piyushsingh0216/Portfolio.git
cd Portfolio
npm install
```

### Development

```bash
npm run dev
```

Vite will print the local URL (usually `http://localhost:5173`).

### Production build

```bash
npm run build
npm run preview
```

## Available scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the Vite development server |
| `npm run build` | Type-check the project and create an optimized production build |
| `npm run preview` | Serve the production build locally |
| `npm run images` | Generate optimized image assets with Sharp |

## Project structure

```text
src/
├── components/       # Portfolio sections, cards, modals, and UI effects
├── data/             # Portfolio content and display configuration
├── hooks/            # Smooth scroll, media-query, and section-progress hooks
├── App.tsx           # Application flow and overlay state
└── index.css         # Global styles and Tailwind imports
public/assets/        # Portraits, social image, and downloadable résumé
scripts/              # Asset-generation utilities
```

## Personalising the portfolio

Most portfolio copy and content lives in [`src/data/portfolio.ts`](src/data/portfolio.ts). Update the profile, projects, skills, experience, achievements, and viewer profiles there. Place replacement images and a résumé PDF in `public/assets`, then update the corresponding asset paths in the same file.

## Connect

- GitHub: [@Piyushsingh0216](https://github.com/Piyushsingh0216)
- LinkedIn: [Piyush Singh](https://www.linkedin.com/in/piyush-singh-66478029a)
- Email: [piyushsingh.0216@gmail.com](mailto:piyushsingh.0216@gmail.com)

## License

Distributed under the [MIT License](LICENSE). © 2026 Piyush Singh.
