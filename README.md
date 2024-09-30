# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

React no pages

1. Vincule o projeto local ao repositório remoto:

git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/seu-usuario/meu-projeto.git
git push -u origin main

2. Instale o pacote gh-pages:

npm install --save-dev gh-pages

3. Configure o package.json:

Abra o arquivo package.json do seu projeto e adicione as seguintes propriedades:
"homepage": "https://seu-usuario.github.io/meu-projeto",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}

4. Construa a aplicação para produção:

npm run build

5. Faça o deploy:

npm run deploy

6. Acesse sua aplicação:

https://seu-usuario.github.io/meu-projeto
