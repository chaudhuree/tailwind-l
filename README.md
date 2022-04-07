## To setup tailwind css, run these commands

1.  npm init -y// This initializes the directory as a NodeJs project
2.  npm install -D tailwindcss postcss autoprefixer vite // installs required packages
3.  npx tailwindcss init -P
4.  Create a css file "input.css", add it to your html and edit it with this content:
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
5.  In your tailwind.configjs file replace content: [ ], with content: ["\*"],
6.  Add "start": vite" to your scripts in package.json
7.  Run npm run start command to start a dev server
