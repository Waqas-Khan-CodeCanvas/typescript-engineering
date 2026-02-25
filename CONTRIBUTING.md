# Contributing to TypeScript Engineering Repository.

First off — thank you! Every contribution makes this resource better for everyone.

## Ways to Contribute

- 🐛 Fix a typo or incorrect code
- 💡 Add a real-world example to an existing topic
- 📝 Improve explanations in a README
- 🧩 Add an exercise with a solution
- 🆕 Propose a new topic (open an issue first)
- ⭐ Star the repo and share it

## Getting Started
```bash
# 1. Fork the repo, then clone your fork
git clone https://github.com/Waqas-Khan-CodeCanvas/typescript-engineering.git

# 2. Create a feature branch
git checkout -b feat/add-mapped-types-example

# 3. Install dependencies
npm install

# 4. Make your changes, then type-check
npm run typecheck

# 5. Lint and format
npm run lint
npm run format

# 6. Commit using conventional commits
git commit -m "feat(intermediate): add real-world mapped types example"

# 7. Push and open a Pull Request
git push origin feat/add-mapped-types-example
```

## Commit Message Convention

We follow [Conventional Commits](https://www.conventionalcommits.org/):
```
feat(section): short description
fix(beginner): correct typo in generics example
docs(readme): update getting started section
chore: update dependencies
```

## Code Style Rules

- All code must pass `npm run typecheck` with zero errors
- Keep examples beginner-friendly — add explanatory comments
- Each `index.ts` must be a standalone, runnable file
- Each topic needs both `index.ts` and `README.md`

## Code of Conduct

Be kind, inclusive, and constructive. Beginners are especially welcome here.