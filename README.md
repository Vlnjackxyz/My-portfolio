# Chandan Sharma, Portfolio

    npm install
    npm run dev      # local
    npm run build    # production build in dist/

## Where to edit
- Text, links, resume, form endpoint: `src/data/portfolio.js`
- Skills: `src/data/skills.js`   Projects: `src/data/projects.js`
- Colors and fonts: `@theme` block in `src/index.css`
- Animation timing: `src/motion.js` (entrances), `src/App.jsx` (tab transition), `src/components/AnimatedBackground.jsx`

## Deploy on Vercel
1. `git init && git add . && git commit -m "Portfolio"`; create a GitHub repo and push.
2. On vercel.com choose Add New > Project, import the repo. Framework: Vite (auto-detected). Deploy.
3. Contact form: create a Formspree form and paste its URL into `formEndpoint`.
