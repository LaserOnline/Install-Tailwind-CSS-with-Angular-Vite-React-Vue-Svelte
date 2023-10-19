
## Install Tailwind CSS with Vite React, Vue, Svelte
[Vite React Vue Svelte Tailwind](https://tailwindcss.com/docs/guides/vite)


Create your project
```bash
  npm create vite@latest
  cd my-project
```

Install Tailwind CSS    
```bash
  npm install -D tailwindcss postcss autoprefixer
  npx tailwindcss init -p
```

tailwind.config.js
```bash
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    './index.html', './src/**/*.{vue,js,ts,jsx,tsx,svelte}'
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

index.css
```bash
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Start your build process   
```bash
  npm run dev
```

Test
```bash
  <h1 className="text-3xl font-bold underline">
      hello world!
  </h1>
```

---
