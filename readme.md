# Shayan's Portfolio Website

## About This Project

This is my personal portfolio website for my INFR3120 Assignment 02. I created this website to introduce myself, share some of the projects I have worked on, and provide a way for people to contact me.

For this assignment, I rebuilt my portfolio using Node.js, Express, and EJS instead of using the HTML pages from Assignment 01. I used the Express Generator method from class to create the initial project structure and then added the different pages, routes, styling, and content.

I wanted to keep the website simple and clean, so I used a light background with white content cards, a dark navigation bar, and blue accents throughout the website.

## Pages

The website has four main pages:

**Home** – Introduces me and includes links to the other pages.

**About Me** – Includes information about my education, goals, and interests.

**Projects** – Shows some of the projects I have worked on and the technologies used.

**Contact Me** – Includes my email address, GitHub, and LinkedIn information.

There is also an error page that is displayed when a page that does not exist is requested.

## Project Structure

The project was created using Express Generator with EJS views.

`app.js` contains the main Express application setup.

`routes/index.js` contains the routes for the different pages.

`views/` contains the EJS files used to display each page.

`views/layout.ejs` contains the shared layout, including the navigation bar and footer.

`public/stylesheets/style.css` contains the main CSS used throughout the website.

`public/images/` contains images used by the website.

## Technologies Used

- Node.js
- Express
- EJS
- Express EJS Layouts
- Bootstrap
- Font Awesome
- CSS
- Git and GitHub

## Express and EJS

I used the Express Generator method covered in class to create the initial project structure.

I then changed the project to use EJS for the views and created separate EJS pages for the Home, About Me, Projects, and Contact Me sections.

The routes are handled in `routes/index.js` using Express `app.get()` style routes and `res.render()` to display the EJS pages.

I also used a shared EJS layout so that the navigation bar and footer are consistent across the different pages.

## Styling

I used CSS along with Bootstrap to style the website.

The main design uses:

- Light gray background
- White content cards
- Dark navigation bar and footer
- Blue buttons and accents
- Simple hover effects
- Spacing and responsive Bootstrap classes

I tried to keep the design simple instead of adding too many effects or colours.

## Git and Version Control

I used Git throughout the development of the project and pushed the project to GitHub.

I made commits at different stages of development instead of only committing the final version. This allowed me to keep track of changes while building the different pages and fixing issues.

I also used GitHub to store the project and make the repository available for the assignment.

## Testing and Troubleshooting

I tested each page locally while developing the website and checked that the different routes were working correctly.

I had a few issues while setting up Express and EJS. For example, I had to fix problems with the old Express Generator view files, remove unused routes, and make sure the EJS layout and error page were working correctly.

I also had some issues with Git and making sure changes were being pushed correctly to GitHub.

I used ChatGPT as a troubleshooting tool when I was stuck on errors or was unsure how to fix something. I mainly used it to help me understand error messages, find problems in my code, and figure out the steps needed to fix issues. I still made the changes and tested the website myself to make sure everything worked.

## Sources and Acknowledgements

I used the Express, EJS, and other code examples covered in class and tutorials to build the website.

I used Bootstrap for some of the page layout, spacing, buttons, and responsive design.

I used Font Awesome for the icons throughout the website.

I also used ChatGPT for troubleshooting, understanding errors, and getting help when I was stuck during development.

Bootstrap: https://getbootstrap.com/

Font Awesome: https://fontawesome.com/

## Website Links

GitHub repository: https://github.com/shayan1201/infr3120-assignment-02

GitHub profile: https://github.com/shayan1201

LinkedIn: https://www.linkedin.com/in/shayan-hussain-315a5a407/

Email: shayanhussain471@gmail.com
