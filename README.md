# Portfolio-Website

**Overview**

_My personal portfolio website to give the viewer a quick glimse on what tooling and technology I use, a little about me, a few of my current projects, and allows them to fetch my resume to see a bigger picture of my skills and capabilities._

**How it was built**

I built this portfolio website using VS Code as my development enviroment. The 4 types of technology that I decided to use to build this project was:

- HTML
- SASS
- JavaScript
- NPM
- Netlify

Starting out, I layouted out the foundation with HTML, which is a large portion of the codebase for creating this project. I thought about using css to build this project, but knew if I used a preprocessor like SASS I could use I could use features like Partials to modularize the project, and that way I could compartmentalize the styling sections individually which could make styling easier. I also wanted to stay away from using a framework like bootstrap or tailwind, because I wanted seperation of concern, and I knew this project was going to be extremely customized. I also knew in order to compile the SASS code I needed to use the NPM which would allow me to install a library to do this.
I also created a JavaScript file, but have not implemented any JavaScript code because it will only be used in a future release. This is because there will be a feature in which I will need JavaScript to listent to an event, and execute the code when the action happens.

**Developer Notes**

This project was challenging because I wanted to create a reponsive design that would fit in a large display, laptop, and on a mobile device. Because parts of this website was complex, I knew that just flexbox and rem units alone would not solve the problem. In order to achieve responsiveness in the desired display sizes, I had to apply media queries so I can adjust any element that did not fit or was distored in the given demensions. I kept the largest screen size as a default and set 2 media queries for the desired size screens. I had to keep going back and forth when adjusting sizes, because every time I would adjust something, it would throw something else off. I did this until eventially everything worked okay. I had to post pone a couple of features like "dark-mode" because I wanted to completed the website, and launch it quick. I also wanted to make sure that everything worked 100% when the site was launched, and did not want a feature to break or to not work. There are still some hicups with the "view height" where it grows to much if I adjust the screen, which I might need to give it a fixed size and go away from using rems. I will AB test this first on one seciton before emplementing this.
