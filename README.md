# ⚛️ React.js Complete Developer Guide

<div align="center">

<img src="https://raw.githubusercontent.com/github/explore/main/topics/react/react.png" width="150"/>

### 🚀 Learn React From Beginner To Advanced

Modern Frontend Development with React, Vite, Hooks, Routing, API Integration, State Management & Deployment

</div>

---

# 📚 What is React?

React is a JavaScript library developed by Meta for building fast, interactive and reusable User Interfaces.

### Key Features

✅ Component Based Architecture

✅ Virtual DOM

✅ Reusable Components

✅ Fast Rendering

✅ SEO Friendly (Next.js)

✅ Huge Community Support

✅ Easy API Integration

✅ Cross Platform Development

---

# 🛠️ Install Requirements

## Install Node.js

```bash
node -v
npm -v
```

## Update npm

```bash
npm install -g npm
```

---

# ⚡ Create React App (CRA)

### Create Project

```bash
npx create-react-app my-app
```

### Run Project

```bash
cd my-app
npm start
```

### Build Project

```bash
npm run build
```

### Run Test

```bash
npm test
```

### Eject

```bash
npm run eject
```

---

# ⚡ React With Vite (Recommended)

### Create React Project

```bash
npm create vite@latest my-react-app
```

### Create React TypeScript Project

```bash
npm create vite@latest my-app -- --template react-ts
```

### Enter Project

```bash
cd my-react-app
```

### Install Dependencies

```bash
npm install
```

### Run Development Server

```bash
npm run dev
```

### Production Build

```bash
npm run build
```

### Preview Build

```bash
npm run preview
```

---

# 📦 Dependency Commands

### Install Package

```bash
npm install package-name
```

Example:

```bash
npm install axios
npm install react-router-dom
npm install redux
npm install redux-toolkit
```

---

### Install Dev Dependency

```bash
npm install -D package-name
```

Example:

```bash
npm install -D eslint
npm install -D prettier
```

---

### Remove Package

```bash
npm uninstall package-name
```

Example:

```bash
npm uninstall axios
```

---

### Update Package

```bash
npm update
```

---

### View Installed Packages

```bash
npm list
```

---

# 🔥 React Router

### Install

```bash
npm install react-router-dom
```

### Common Imports

```jsx
import {
 BrowserRouter,
 Routes,
 Route,
 Link,
 NavLink
} from "react-router-dom";
```

---

# 🌐 Axios API

### Install Axios

```bash
npm install axios
```

### Example

```jsx
import axios from "axios";

axios.get("https://api.example.com/users")
.then(res => console.log(res.data));
```

---

# 🎨 Tailwind CSS Setup

### Install

```bash
npm install tailwindcss @tailwindcss/vite
```

### Configure

```js
import { defineConfig } from 'vite'
import tailwindcss from '@tailwindcss/vite'

export default defineConfig({
  plugins: [tailwindcss()],
})
```

### Import CSS

```css
@import "tailwindcss";
```

---

# 🎯 React Hooks

## useState

```jsx
import { useState } from "react";
```

## useEffect

```jsx
import { useEffect } from "react";
```

## useRef

```jsx
import { useRef } from "react";
```

## useMemo

```jsx
import { useMemo } from "react";
```

## useCallback

```jsx
import { useCallback } from "react";
```

## useContext

```jsx
import { useContext } from "react";
```

## useReducer

```jsx
import { useReducer } from "react";
```

---

# 📁 Recommended Project Structure

```text
src/
│
├── assets/
├── components/
├── pages/
├── layouts/
├── routes/
├── hooks/
├── services/
├── context/
├── redux/
├── utils/
├── styles/
├── App.jsx
└── main.jsx
```

---

# 🧠 React Snippets

### Functional Component

```jsx
function Home() {
  return (
    <h1>Home Page</h1>
  );
}

export default Home;
```

---

### Props

```jsx
function User({name}) {
  return <h1>{name}</h1>;
}
```

---

### State

```jsx
const [count,setCount] = useState(0);
```

---

### Event

```jsx
<button onClick={handleClick}>
 Click
</button>
```

---

### Conditional Rendering

```jsx
{
 isLogin
 ? <Dashboard/>
 : <Login/>
}
```

---

### List Rendering

```jsx
{
 users.map(user=>(
   <h3 key={user.id}>
      {user.name}
   </h3>
 ))
}
```

---

# ⚙️ Environment Variables

### Create

```env
VITE_API_URL=https://api.example.com
```

### Use

```jsx
const api = import.meta.env.VITE_API_URL;
```

---

# 🔥 Redux Toolkit

### Install

```bash
npm install @reduxjs/toolkit react-redux
```

### Create Store

```jsx
import { configureStore } from "@reduxjs/toolkit";

export const store = configureStore({
 reducer:{}
});
```

---

# 🧪 Testing

### Install

```bash
npm install vitest
```

### Run

```bash
npm run test
```

---

# 🚀 Deployment

## Vercel

```bash
npm install -g vercel
vercel
```

## Netlify

```bash
npm run build
```

Upload:

```text
dist/
```

---

# 🐙 Git Commands

### Initialize

```bash
git init
```

### Add

```bash
git add .
```

### Commit

```bash
git commit -m "Initial Commit"
```

### Branch

```bash
git branch -M main
```

### Remote

```bash
git remote add origin REPOSITORY_URL
```

### Push

```bash
git push -u origin main
```

---

# 📦 Useful React Packages

```bash
npm install react-router-dom
npm install axios
npm install sweetalert2
npm install react-icons
npm install framer-motion
npm install react-hook-form
npm install zod
npm install yup
npm install date-fns
npm install recharts
npm install chart.js
npm install react-chartjs-2
npm install firebase
npm install socket.io-client
npm install @reduxjs/toolkit
npm install react-redux
npm install react-query
npm install zustand
npm install jspdf
npm install react-toastify
npm install swiper
npm install react-select
```

---

# 🏆 React Learning Roadmap

### Beginner

- HTML
- CSS
- JavaScript ES6
- JSX
- Components
- Props
- State
- Event Handling

### Intermediate

- Hooks
- Routing
- API Fetching
- Context API
- Forms
- Validation

### Advanced

- Redux Toolkit
- Authentication
- JWT
- Performance Optimization
- Code Splitting
- Lazy Loading
- React Query
- Zustand
- Testing
- CI/CD

### Expert

- Next.js
- SSR
- SSG
- Micro Frontend
- Docker
- Kubernetes
- GraphQL
- TypeScript
- System Design

---

# 👨‍💻 Developer

**Moklasur Rahman Rahat**

Full Stack Web Developer | Mobile App Developer | Software Engineer

GitHub: **codexvisual**

⭐ Star this repository if it helps you learn React.
