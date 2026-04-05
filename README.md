# Vedant Shah — Portfolio Website

Personal portfolio for **Vedant Shah**, an AI & ML Developer. Built with React, TypeScript, and interactive 3D graphics powered by Three.js.

---

## Tech Stack

| Category | Technology |
|----------|-----------|
| Framework | React 18 + TypeScript |
| Build Tool | Vite |
| 3D / WebGL | Three.js, React Three Fiber, Drei |
| Physics | React Three Rapier, Cannon |
| Post-Processing | @react-three/postprocessing |
| Animation | GSAP + @gsap/react |
| Styling | Tailwind CSS v4, PostCSS |
| UI Utilities | react-icons, react-fast-marquee |
| Analytics | Vercel Analytics |
| Linting | ESLint + TypeScript-ESLint |

---

## Getting Started

### Prerequisites

- Node.js 18+
- npm

### Install dependencies

```bash
npm install
```

### Run development server

```bash
npm run dev
```

The site will be available at `http://localhost:5173` (or the next available port).

### Build for production

```bash
npm run build
```

Output goes to `dist/`.

### Preview production build

```bash
npm run preview
```

### Lint

```bash
npm run lint
```

---

## Project Structure

```
.
├── index.html              # HTML entry point
├── src/                    # React application source
│   └── main.tsx            # App entry point
├── public/                 # Static assets served as-is
├── scripts/                # Utility / scratch scripts
├── vite.config.ts          # Vite configuration
├── tsconfig.json           # TypeScript project references
├── tsconfig.app.json       # App TypeScript config (strict, ES2020)
├── tsconfig.node.json      # Node/build-tools TypeScript config
├── eslint.config.js        # ESLint v9 flat config
└── package.json
```

---

## GSAP Notice

This project uses `gsap-trial` (trial versions of GSAP Club plugins).

> **Trial plugins cannot be used for production hosting.**
> For deployment, replace with official GSAP Club plugins: https://gsap.com/docs/v3/Installation/

---

## Assets

Some 3D assets in this repository are free-to-use for learning.

- The custom 3D avatar used on the live site is **not included** — it is a proprietary asset (~1 month of work) and is not available for reuse.
- Extracting, copying, or redistributing the avatar from the live website is strictly prohibited.

---

## License

Licensed under the **Personal Portfolio License (PPL) v1.0** — see [LICENSE](./LICENSE) for full terms.

**In short:** you may study and learn from this code, but you may not clone the design, use it commercially, or redistribute it. Attribution is required for any code reuse.

---

## Contact

**Vedant Shah** — AI & ML Developer
