# 🚀 Configuração com ⚛️ TypeScript & ⚡ Vite

Este 📁 guia a configuração inicial de um **projeto** utilizando **⚛️ TypeScript + ⚡ Vite**, com suporte a **🎨 Tailwind CSS**, **🔗 Axios**, **✨ Phosphor Icons**, **🛣️ React Router**, **⏳ React Loader Spinner**, **🎭 React Icons** e **💫 Framer Motion**.

## 📌 Requisitos

- [🟢 Node.js](https://nodejs.org/)
- [🧶 Yarn](https://yarnpkg.com/)

## 🏗️ Inicializando o Projeto

```sh
npm create vite projeto --template react-ts

cd projeto
```

## ▶️ Executando o Projeto

```sh
yarn
yarn dev
```

## 🎨 Configurando Tailwind CSS

Instale o 🎨 Tailwind CSS e seu plugin para ⚡ Vite:

```sh

npm install tailwindcss @tailwindcss/vite

```

Edite o arquivo **vite.config.ts** para incluir o plugin:

```ts
import { defineConfig } from 'vite';
import tailwindcss from '@tailwindcss/vite';

export default defineConfig({
  plugins: [tailwindcss()],
});
```

No arquivo **index.css**, importe o 🎨 Tailwind:

```css
@import "tailwindcss";
```

## 📦 Instalando Dependências Adicionais

```sh
yarn add axios
yarn add phosphor-icons
yarn add react-router-dom
yarn add react-loader-spinner
yarn add @types/react-icons
yarn add framer-motion
```

## 📂 Estrutura Recomendada

```
projeto/
├── src/
│   ├── 🏗️ components/   # 🔄 Reutilizáveis
│   ├── 📄 pages/        # 📜 Principais
│   ├── 🛣️ routes/       # 🚦 Rotas
│   ├── 🎨 styles/       # 🎭 Estilos
│   ├── 🔹 App.tsx       # 🔑 Componente principal
│   ├── 🚀 main.tsx      # 🎯 Entrada
│
├── 📂 public/
│
├── 📜 package.json
├── ⚙️ vite.config.ts
├── 📑 tsconfig.json
└── 📘 README.md
```

Agora seu **projeto** está pronto para ser desenvolvido! 🚀🎉

