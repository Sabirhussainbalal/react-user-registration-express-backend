# React User Registration Form with Express Backend

## A responsive user registration form built with React and styled using Tailwind CSS. The form validates user input with react-hook-form and communicates with an Express backend to handle submissions.



## Technologies Used
- React
- Tailwind CSS
- Express.js
- Axios
- react-hook-form


## Features
- User input validation
- Responsive design
- Integration with a backend API
- Error handling for existing usernames


## Getting Started

### Prerequisites
- Node.js
- npm

-----
## The following commands in your terminal:

```bash
npm create vite@latest
```
```bash
npm install -D tailwindcss postcss autoprefixer
```
```bash
npx tailwindcss init -p
```
```bash
npm i axiosr
```
```bash
npm i react-hook-form
```

## Paste this in tailwind.config.js

```
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

## Paste this in index.css

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```


### Run (Frontend Terminal)
```bash
npm run dev
```

---
## Create a my-backend Folder


### Open this folder in VS Code:

```bash
npm init -y
```

```bash
npm install express body-parser cors
```

```bash
npm install body-parser
```

### Run (Backend Terminal)

```bash
npm start
```


---
---
### If it does not work, I have included a video named *React-Form.mp4*. You can watch it and install the necessary modules.
---
---



