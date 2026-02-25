<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/4/4c/Typescript_logo_2020.svg" width="100" alt="TypeScript Logo" />

# 🚀 TypeScript Mastery — From Zero to Production

**A structured, real-world TypeScript learning journey for MERN Stack Developers**

[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Node.js](https://img.shields.io/badge/Node.js-20.x-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)](CONTRIBUTING.md)

---

*Built with 💙 by a MERN developer, for MERN developers — and every developer who wants to write safer, smarter code.*

[📖 Get Started](#-getting-started) • [🗺️ Roadmap](#%EF%B8%8F-learning-roadmap) • [🤝 Contribute](#-contributing)

</div>

---

## 📌 Why This Repository Exists

I'm a **MERN Stack developer** who decided to level up by mastering TypeScript — not just the basics, but the patterns used in real production systems.

This repo is my **public learning journal and structured reference guide** designed for:

- 📚 **Beginners** — zero to confident with TypeScript fundamentals
- ⚙️ **Intermediate** — generics, utility types, real-world patterns
- 🧠 **Advanced** — deep-dive into TypeScript's type system internals
- ⚛️ **Frontend devs** — React + TypeScript (hooks, Redux, forms, API)
- 🖥️ **Backend devs** — Node.js + Express + TypeScript

---

## 🗺️ Learning Roadmap
```
TypeScript Mastery
│
├── 🟢 BEGINNER
│   ├── 01 — Types & Variables
│   ├── 02 — Functions
│   ├── 03 — Arrays & Tuples
│   ├── 04 — Objects & Interfaces
│   ├── 05 — Type Assertions
│   ├── 06 — Enums
│   └── 07 — Union & Intersection Types
│
├── 🟡 INTERMEDIATE
│   ├── 01 — Generics
│   ├── 02 — Utility Types
│   ├── 03 — Decorators
│   ├── 04 — Modules & Namespaces
│   ├── 05 — Error Handling
│   ├── 06 — Type Guards
│   ├── 07 — Mapped Types
│   └── 08 — Conditional Types
│
├── 🔴 ADVANCED
│   ├── 01 — Advanced Generics
│   ├── 02 — Template Literal Types
│   ├── 03 — The Infer Keyword
│   ├── 04 — Recursive Types
│   ├── 05 — Declaration Files (.d.ts)
│   └── 06 — Performance Optimization
│
├── ⚛️  FRONTEND — React + TypeScript
│   ├── 01 — React with TypeScript
│   ├── 02 — Hooks Typing
│   ├── 03 — Context API
│   ├── 04 — Redux Toolkit
│   ├── 05 — Form Handling (React Hook Form + Zod)
│   └── 06 — API Calls (Axios + typed responses)
│
└── 🖥️  BACKEND — Node.js + Express + TypeScript
    ├── 01 — Node.js + Express Setup
    ├── 02 — RESTful API
    ├── 03 — Database Integration (Prisma / Mongoose)
    ├── 04 — Authentication (JWT)
    ├── 05 — Middleware
    └── 06 — Validation (Zod)
```

---

## 📁 Project Structure
```
typescript-mastery/
│
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md
│   │   └── feature_request.md
│   └── workflows/
│       └── ci.yml
│
├── src/
│   ├── 01-beginner/
│   │   ├── 01-types-and-variables/
│   │   │   ├── index.ts
│   │   │   └── README.md
│   │   ├── 02-functions/
│   │   ├── 03-arrays-and-tuples/
│   │   ├── 04-objects-and-interfaces/
│   │   ├── 05-type-assertions/
│   │   ├── 06-enums/
│   │   └── 07-union-and-intersection/
│   │
│   ├── 02-intermediate/
│   │   ├── 01-generics/
│   │   ├── 02-utility-types/
│   │   ├── 03-decorators/
│   │   ├── 04-modules-and-namespaces/
│   │   ├── 05-error-handling/
│   │   ├── 06-type-guards/
│   │   ├── 07-mapped-types/
│   │   └── 08-conditional-types/
│   │
│   ├── 03-advanced/
│   │   ├── 01-advanced-generics/
│   │   ├── 02-template-literal-types/
│   │   ├── 03-infer-keyword/
│   │   ├── 04-recursive-types/
│   │   ├── 05-declaration-files/
│   │   └── 06-performance-optimization/
│   │
│   ├── 04-frontend/
│   │   ├── 01-react-with-typescript/
│   │   ├── 02-hooks-typing/
│   │   ├── 03-context-api/
│   │   ├── 04-redux-toolkit/
│   │   ├── 05-form-handling/
│   │   └── 06-api-calls/
│   │
│   └── 05-backend/
│       ├── 01-nodejs-express/
│       ├── 02-restful-api/
│       ├── 03-database-integration/
│       ├── 04-authentication/
│       ├── 05-middleware/
│       └── 06-validation/
│
├── exercises/
│   ├── beginner/
│   ├── intermediate/
│   └── advanced/
│
├── projects/
│   ├── frontend/
│   ├── backend/
│   └── fullstack/
│
├── resources/
│   └── cheatsheet.md
│
├── .eslintrc.json
├── .gitignore
├── .prettierrc
├── tsconfig.json
├── tsconfig.strict.json
├── package.json
├── CONTRIBUTING.md
├── CHANGELOG.md
├── LICENSE
└── README.md
```

---

## 🚀 Getting Started
```bash
# Clone the repository
git clone https://github.com/Waqas-Khan-CodeCanvas/typescript-engineering.git
cd typescript-engineering

# Install dependencies
npm install

# Run any example file
npx tsx src/01-beginner/01-types-and-variables/index.ts

# Type check everything
npm run typecheck
```

---

## 📖 How Each Topic Is Structured

Every topic folder follows this consistent pattern:
```
01-generics/
├── index.ts      → Annotated, runnable TypeScript code
├── README.md     → Explanation with real-world context
└── exercises.ts  → Practice problems (solutions in /exercises)
```

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| TypeScript 5.x | Core language |
| tsx | Run `.ts` files directly without compiling |
| ESLint + @typescript-eslint | Linting with TS-aware rules |
| Prettier | Consistent code formatting |
| Zod | Runtime validation (used in backend + frontend examples) |

---

## 📈 Progress Tracker

| Module | Status |
|---|---|
| 🟢 Beginner | 🔄 In Progress |
| 🟡 Intermediate | 📋 Planned |
| 🔴 Advanced | 📋 Planned |
| ⚛️ Frontend | 📋 Planned |
| 🖥️ Backend | 📋 Planned |

---

## 📚 Recommended External Resources

| Resource | Type | Level |
|---|---|---|
| [Official TypeScript Docs](https://www.typescriptlang.org/docs/) | Docs | All |
| [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html) | Guide | Beginner–Intermediate |
| [Total TypeScript](https://www.totaltypescript.com/) | Course | All |
| [Type Challenges](https://github.com/type-challenges/type-challenges) | Practice | Intermediate–Advanced |
| [TypeScript Deep Dive](https://basarat.gitbook.io/typescript/) | Free Book | All |
| [Matt Pocock on YouTube](https://www.youtube.com/@mattpocockuk) | Videos | All |

---

## 🤝 Contributing

Contributions are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">

**If this helped you, please give it a ⭐ — it means a lot!**

*"TypeScript isn't just JavaScript with types — it's JavaScript with confidence."*

</div>