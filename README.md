# Challenge S19 LocalExpress
[Lien vers le challenge](https://github.com/O-clock-Skaven/S19-LocalExpress/tree/main)

Tu vas coder ton premier e-commerce 😱 Enfin… il sera un peu simplifié sinon ça tiendrait pas en 7 jours 😅

## Cahier des charges fonctionnel
[Cahier des charges fonctionnel](https://github.com/O-clock-Skaven/S19-LocalExpress/blob/main/__docs/challenges/CDCF.md)

## Technologies utilisées

Vite + React + Typescript
SCSS
CI/CD
API REST
Vitest
Énoncés
Jour 1

## Compétences visées

 - [x] CP 1 : Installer et configurer son environnement de travail en fonction du projet
 - [x] CP 2 : Développer des interfaces utilisateur
 - [x] CP 3 : Développer des composants métier
 - [x] CP 4 : Contribuer à la gestion d'un projet informatique
 - [x] CP 5 : Analyser les besoins et maquetter une application
 - [ ] CP 6 : Définir l'architecture logicielle d'une application
 - [ ] CP 7 : Concevoir et mettre en place une base de données relationnelle
 - [ ] CP 8 : Développer des composants d'accès aux données SQL et NoSQL
 - [x] CP 9 : Préparer et exécuter les plans de tests d'une application
 - [x] CP 10 : Préparer et documenter le déploiement d'une application
 - [x] CP 11 : Contribuer à la mise en production dans une démarche DevOps
# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default tseslint.config({
  languageOptions: {
    // other options...
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
})
```

- Replace `tseslint.configs.recommended` to `tseslint.configs.recommendedTypeChecked` or `tseslint.configs.strictTypeChecked`
- Optionally add `...tseslint.configs.stylisticTypeChecked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and update the config:

```js
// eslint.config.js
import react from 'eslint-plugin-react'

export default tseslint.config({
  // Set the react version
  settings: { react: { version: '18.3' } },
  plugins: {
    // Add the react plugin
    react,
  },
  rules: {
    // other rules...
    // Enable its recommended rules
    ...react.configs.recommended.rules,
    ...react.configs['jsx-runtime'].rules,
  },
})
```
