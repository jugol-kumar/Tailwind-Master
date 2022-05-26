# Tailwind Css v3 Install Gide
##how to install Tailwind with cli.


npm init -y

install -D tailwindcss postcss autoprefixer

npx tailwindcss init
```angular2
    module.exports = {
      content: ["./src/**/*.{html,js}"],
      theme: {
        extend: {},
      },
      plugins: [],
    }
```

######pest it tailwindcss.config.js file

create src dir in main preject file
create input.css file in src directory
```css
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
```
pest it input.css file

######@npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
run this comand in terminal. 
---