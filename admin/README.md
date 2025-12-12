This is a very simple admin panel starter made with React + Vite.

npm create vite@latest admin -- --template react
cd admin

npm run dev

npm install react-router-dom

npm install axios
========================================================
npm install tailwindcss

npm install @tailwindcss/vite

import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react-swc'
import tailwindcss from '@tailwindcss/vite'

@import "tailwindcss";

// https://vite.dev/config/
export default defineConfig({
  plugins: [
    react(),
    tailwindcss()
  ],
  server: { port: 5174 }
})
=========================================================
npm install react-toastify

npm install react
npm install react-dom

npm install -D @vitejs/plugin-react-swc

npm install -D eslint

npm install -D @eslint/js

npm install -D eslint-plugin-react-hooks

npm install -D eslint-plugin-react-refresh

npm install -D @types/react @types/react-dom

npm install -D vite

npm install -D globals

VITE_BACKEND_URL = 'http://localhost:4000'
=============================================================
