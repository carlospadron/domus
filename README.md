# domus
A system to make data accessible

## webapp

### create
```bash
npx create-next-app@latest webapp
cd webapp
npm install
npm i -D daisyui@latest
npm install maplibre-gl
```

### develop
```bash
npm run dev
```

### Deploy to github pages
Read https://github.com/nextjs/deploy-github-pages/blob/main/README.md
Adjust next.config.ts using this template: https://github.com/nextjs/deploy-github-pages/blob/main/next.config.ts
Set github pages using action on the repo.
Go to https://carlospadron.github.io/domus/