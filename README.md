# Tailwind CSS in HTML

## Installing Tailwind in a project.
```bash
npm install -D tailwindcss postcss autoprefixer
```

## Initialize Tailwind in Project
```bash
npx tailwindcss init
```

## Declare Tailwind in "input.css"
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## Compilign Tailwind to vanila CSS
### Translate the tailwind to css manually
```bash
npx tailwindcss -i ./src/input.css -o ./build/css/style.css
```

```bash
npm i -D prettier-plugin-tailwindcss
```

### Change style.css at each change in html automatically 
```bash
npx tailwindcss -i ./src/input.css -o ./build/css/style.css --watch
```

## Running Tailwind
```json
"tailwind": "npx tailwindcss -i ./src/input.css -o ./build/css/style.css --watch" //package.json/script
```
```bash
npm run tailwind 
```