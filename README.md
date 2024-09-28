# rumos-projeto-dicionario

Tailwind is installed with:

npm install -d tailwindcss@latest postcss@latest autoprefixer@latest

created style.css with the tailwind imports

npx tailwindcss init -> generates tailwind.config.js

added, a script in package.json -> "build-css": "tailwindcss build -i style.css -o css/style.css"

in tailwind.config.js added ''./*.html' to content so that tailwind styles are applied to html files

to run the script we use -> npm run build-css
