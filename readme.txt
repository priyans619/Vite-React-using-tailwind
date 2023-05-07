//how to run script from third party 

Enable execution policy from restricted .ps1(powershel)
- Run powershell as administrator
- "get-executionpolicy" // to know current status
- "set-executionpolicy remotesigned" // to run script
- execute "set-executionpolicy unrestricted"  //for running usnsigned script 
- To set the execution policy "restricted" run "set-executionpolicy restricted"

//setting vite + React

open terminal-> yarn create vite
                project name- (choose any)
                select framework-'any'
                choose script- js,ts

open new terminal-> cd "project path"
                 -> yarn add tailwindcss postcss autoprefixer
                 -> npx tailwindcss init -p  (#p is postcss)

//remove app.css and index.css content acc to your project

// add tailwind dependency in index.css 
   add-> @tailwind base;
         @tailwind components;
         @tailwind utilities

yarn run start // start the the server and build project