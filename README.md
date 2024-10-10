

## Overview

This project is a basic page made with Next.js. The goal of this assignment is to help
you become acquainted with Next.js framework and navigate its file structure. This application
introduces us to Next.js combined with the power of React with it's additional features like sever-side rendering 
and static site generation. 

## Screenshot of Home Page
![Home Page](<homePage.png>)

## Screenshot of About Me

![About Me](<aboutMe.png>)

### Set Up

- In your system terminal make sure you are in the directory that you want your Next app to go. To see where you are you can run:

        pwd

- If you need to navigate somewhere else, to see the files in your current directory, you can run:

        ls

- You can move into the correct directory by running:

        cd <desired directory>

- Create a New Next.js Application
    * Run - NOTE: if we run w/out a project name, the terminal will ask us to enter a project name. 

            npx create-next-app@latest
    
- You will then be asked a series of questions...

![terminal questions](<terminal.png>)

- Navigate to your new project by running:

        cd next-assignment-1

- Then you can open a VScode window by running: 

        code .

- Explore the file structure and the directories.
- Start the dev server by running:

        npm run dev

- Open your browser and navigate to http://localhost:3000 to view your home page and see the changes you make in real-time. NOTE: you can ctrl+click(windows) the link directly from your terminal in VScode.

- Navigate to src/pages/index.js in your editor. 

- Replace the existing content with a simple custom message, such as a welcome message or your favorite quote.

- Add a New Page:
    * Create a new directory called "about". Make this directory inside the "pages" directory that is inside the "src" directory. 
    * Create a new file in your "about" directory called "index.js".
    * In index.js, create a functional component that returns a brief about me page or any content you prefer.
    * Example of this component:

        ```js
            export default function AboutMe() {
                let myName = "Jennifer Tarleton";
                    return (
                        <div>
                            <h1>About Me</h1>
                            <p>
                                My name is {myName}, I am a Junior Software Developer 
                                and I'm interested in creating things that have a real
                                impact. I love the challenge of turning an idea into 
                                a working reality, and pushing that idea even further. 
                            </p>
                        </div>
                    );
                }
            
        ```
- Start the Development Server:
    * Run: 

            npm run dev
            
    * Navigate to http://localhost:3000 in your browser to view your home page, and http://localhost:3000/about to view your about page. 

- Add you Next app to your new repository by running:

        git remote add origin https://github.com/yourusername/your-repository.git
        git branch -M main
        git push -u origin main


