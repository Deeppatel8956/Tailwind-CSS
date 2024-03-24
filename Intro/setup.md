## How to setup TailwindCSS

Step 1 :Run follow the command
```
npm init -y
npm install -D tailwindcss
npx tailwindcss init
```
Step 2: Tailwind.config.js
``` 
content: ["*.html"],
```
Step 3: Create input.css
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
Step 4: Create output.css
```
<link rel="stylesheet" href="src/output.css">
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```
