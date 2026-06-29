# Omkar Dhole — Digital Marketing Portfolio

A modern, responsive portfolio website built with **React**, **Vite**, and **Tailwind CSS**, showcasing the skills, services, and projects of Omkar Dhole — a passionate Digital Marketing Enthusiast.

---

## 🚀 Features

- **Single-page design** with smooth-scroll navigation
- **Responsive layout** — looks great on desktop, tablet & mobile
- **Animated sections** using CSS keyframes & Intersection Observer
- **Skill bars** with animated progress indicators
- **Project showcase** with key results & metrics
- **Contact form** with validation & submission feedback
- **Testimonials** section for social proof
- **Gradient accents** & modern dark theme
- **SEO-friendly** semantic HTML structure

---

## 📸 Sections

| Section       | Description                              |
|---------------|------------------------------------------|
| **Hero**      | Introduction with stats & CTAs           |
| **About**     | Personal bio & expertise tags            |
| **Skills**    | Animated skill bars (8 core skills)      |
| **Services**  | 6 digital marketing service offerings    |
| **Portfolio** | 4 featured projects with results         |
| **Testimonials** | Client feedback & reviews             |
| **Contact**   | Contact form + contact info              |

---

## 🛠️ Tech Stack

- **React 19** — Component-based UI
- **Vite 7** — Lightning-fast dev server & build
- **Tailwind CSS 4** — Utility-first styling
- **TypeScript** — Type-safe development
- **clsx + tailwind-merge** — Conditional class utilities

---

## 📦 Getting Started

### Prerequisites

- **Node.js** (v18 or later)
- **npm** (v9 or later)

### Installation

```bash
# Clone the repository
git clone <repo-url>
cd omkar-dhole-portfolio

# Install dependencies
npm install

# Start development server
npm run dev
```

The app will be running at **http://localhost:5173**

### Build for Production

```bash
npm run build
```

Output will be in the `dist/` folder, ready for deployment.

---

## 📁 Project Structure

```
├── index.html                 # Entry HTML file
├── package.json               # Dependencies & scripts
├── vite.config.ts             # Vite configuration
├── tsconfig.json              # TypeScript configuration
├── README.md                  # This file
└── src/
    ├── main.tsx               # React entry point
    ├── App.tsx                # Main application component
    ├── index.css              # Tailwind imports & custom styles
    └── utils/
        └── cn.ts              # className utility (clsx + twMerge)
```

---

## 🎨 Customization

- **Colors** — Edit the `@theme` block in `src/index.css` to change the color palette
- **Content** — Update text, stats, skills, projects, and testimonials directly in `src/App.tsx`
- **Contact info** — Replace the email and social links in the Contact section

---

## 📄 License

This project is open-source and available for personal use.

---

## 👤 Author

**Omkar Dhole** — Digital Marketing Enthusiast

- 📧 omkar.dhole@email.com
- 📍 Maharashtra, India
