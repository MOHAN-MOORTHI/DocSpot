1. Create Vite React Project
---------------------------------
npm create vite@latest frontend -- --template react
cd frontend

npm run dev

Tailwind CSS
npm install tailwindcss

Tailwind Vite Plugin
npm install @tailwindcss/vite

Axios
npm install axios

React Router DOM
npm install react-router-dom

React Toastify
npm install react-toastify

React (already installed but adding for safety)
npm install react
npm install react-dom

Vite React Plugin
npm install -D @vitejs/plugin-react

Vite React SWC Plugin
npm install -D @vitejs/plugin-react-swc

ESLint
npm install -D eslint

ESLint JS Rules
npm install -D @eslint/js

ESLint React Hooks
npm install -D eslint-plugin-react-hooks

ESLint React Refresh
npm install -D eslint-plugin-react-refresh

TypeScript React Types (works for JS too)
npm install -D @types/react

TypeScript ReactDOM Types
npm install -D @types/react-dom

Globals
npm install -D globals

Vite
npm install -D vite

==============================================================
How to create Razorpay API Key Id 

1) Sign in to the Razorpay Dashboard

Open https://dashboard.razorpay.com
 and log in with your merchant account. 
Razorpay
+1

2) Switch mode: Test or Live

For development use Test mode (sandbox).

When ready for real payments, switch to Live mode and generate live keys.
Use the mode toggle at the top of the Dashboard. 
Razorpay

3) Generate API keys

In the Dashboard go to Account & Settings → API Keys (often under Website and app settings or Developer).

Click Generate Key (or Generate new key).

A popup will show the Key ID and Key Secret — copy them now. The secret is shown only once in the popup. 
Razorpay

Important: Save the secret securely immediately. If you lose it you must regenerate the keys and update them wherever used. 
Razorpay

4) Extra security steps for Live keys

Generating/regenerating live keys usually requires an OTP / 2-factor confirmation to your registered mobile/email. Keep access to that device. 
Razorpay
+1

5) Keep the Key Secret secret (never in frontend)

Key ID can appear in client code if needed, but Key Secret must only live on your server (environment variables, secrets manager). Exposing the secret allows anyone to make API calls on your account. 
Razorpay

6) Quick Node.js example — create an Order (server side)

Install Razorpay package:

npm install razorpay
============================================================
