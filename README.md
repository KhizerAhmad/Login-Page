# Login Page — Multi-Step Registration System 🔐

A modern authentication UI built with React and TypeScript. Not just a plain login form — it includes a full 3-step signup flow, form validation, a MUI stepper, and a dashboard landing page, all wrapped in a clean gradient theme.</br>
Live Link: https://forms-five-sigma.vercel.app/

---

## What it does

- Login page with form validation
- 3-step signup flow (personal info → account details → confirmation)
- MUI Stepper to guide users through registration steps
- Real-time validation powered by Formik & Yup
- Dashboard page after successful login/signup
- Smooth animations and gradient UI throughout

---

## Why I built this

Multi-step forms are everywhere in real products and they're surprisingly tricky to get right — managing state across steps, validating only the current step, and keeping the UX smooth. Built this to get solid with Formik + Yup and understand how to handle complex form flows properly.

---

## Tech Stack

| Technology | Usage |
|------------|-------|
| React | UI and component structure |
| TypeScript | Type safety |
| Formik | Form state management |
| Yup | Schema-based form validation |
| Material UI (MUI) | Components, Stepper, and layout |
| Vite | Build tool and dev server |
| CSS | Custom gradient themes and animations |

---

## How to run it locally

```bash
git clone https://github.com/KhizerAhmad/Login-Page.git
cd Forms
npm install
npm run dev
```

Then open [http://localhost:5173](http://localhost:5173) in your browser.

---

## Project Structure

```
Forms/
│
├── public/              # Static assets
├── src/
│   ├── components/      # Reusable UI components
│   ├── pages/           # Login, Signup steps, Dashboard
│   ├── validation/      # Yup schemas
│   └── assets/          # Images and icons
├── index.html
├── vite.config.ts
└── package.json
```

---

## Features at a glance

- **Login page** — email/password form with validation
- **3-step signup** — split across steps with per-step Yup validation
- **MUI Stepper** — visual progress indicator through signup flow
- **Formik** — handles all form state, touched/error tracking, and submission
- **Yup schemas** — clean, readable validation rules per step
- **Dashboard** — landing page after auth is complete
- **Gradient UI** — consistent visual theme with smooth transitions
- **Fully responsive** — works across all screen sizes

---

## Available Scripts

```bash
npm run dev        # Start dev server
npm run build      # Build for production
npm run preview    # Preview production build
npm run lint       # Run ESLint
```

---

## Screenshot

<img width="1911" height="945" alt="image" src="https://github.com/user-attachments/assets/9978da11-3bbb-4377-b2fe-5f6ba8d0a832" />


---

## Author

**Khizer Ahmad** — built this to get hands-on with multi-step form flows, Formik, and Yup validation in a real React + TypeScript project.

Feel free to fork it or use it as a base for your own auth UI.
