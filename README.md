# STEP 1
First Make a Git repository from your logged in account and in your local machine make a Project Folder.
Inside the folder, make react project boilerplate with "npx create-react-app app_name" or "npm create vite@latest"
Now, open the terminal inside the folder and run all the following commands to add the project on github so that we can track the codebase,
1. git init
2. git add .
3. git commit -m "first commit"
4. git branch -M main
5. git remote add origin "your_github_repo_link"
6. git push -u origin main
   
After running all the commands succesfully your project will be added to github.

# STEP 2
Now setup tailwindcss in your project, go to the project terminal
1. npm i -D tailwindcss
2. npx tailwindcss init
3. Add the paths to all of your template files in your tailwind.config.js file.
   
   /** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js,jsx,ts,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
}

4. Add the @tailwind directives for each of Tailwind’s layers to your main CSS file.
   
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   
5. Now run "npm run dev"

# STEP 3
Now install the dependencies for this project.
run the following command to the terminal----
npm install @redux/toolkit 
react/redux 
react-router-dom
react-icons 
react-chartjs-2 
chart.js 
daisyui 
axios 
react-hot-toast 
@tailwind/line-clamp

