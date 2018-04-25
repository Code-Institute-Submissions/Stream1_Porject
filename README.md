# Project1: Gabriel Knight Website
 
## Overview
 
### What is this website for?
 
This is a fan site for those who have played the Gabriel Knight games and provides in depth details and fun activities about each of the three games in the series. The site could also function as an introduction to the Gbariel Knight games for new players.
 
### What does it do?
 
This site has a separate page for each game that details the overall premise of the game, provides a full timeline of events for each game, and lists the name, voice actor/actor, and short description of the main characters of the games. The site also contains 3 short quizzes on each game that informs you of which quiz you complete and your final score.
 
### How does it work
 
This site uses simple HTML and CSS. The site is also styled with **Bootstrap**. The quiz has been created using **Javascript** to provide a total score and send an alert message when completed. Github was used to deploy this web page. **Javascript** was also used for the automatic typing on the welcome page. The site can be viewed [HERE](https://rmschrader1994.github.io/Stream1_Porject/)

## Features
 
### Existing Features
- Welcome page with automated typing and redirect to home page
- Home page with multiple links to each page.
  - Navbar to navigate to other pages
- Sliding, horizontal timeline of events
- Pictures with changing opacity when hovered over (tapped on when using mobile)
- Professional palette used throughout
    - Changed from a color palatte designed for those who know the games
- Quiz page for viewers to test their knowledge
    - Form for viewers to input their answers or check the correct box
    - Submit button so viewers can see how they scored on the quiz

### Features Left to Implement
- Return correct answers after submitting quiz


## Tech Used

### Some the tech used includes:
- **HTML**, **CSS** and **Javascript**
  - Base languages used to create website
- [Bootstrap](http://getbootstrap.com/)
    - We use **Bootstrap** to give our project a simple, responsive layout
- [JQuery](https://jquery.com)
    - Use **JQuery** for boostrap and displaying modal
- **FontAwesome**
    - Fa fa icons used on Navbar

## Testing
- All code used on the site has been tested to ensure everything is working as expected
- Site viewed and tested in the following browsers:
  - Google Chrome
  - Microsoft Edge
  - Mozilla Firefox
- Site link sent to and tested on multiple machines on different continents

## Contributing
 

## Credits

### Media
The photos used in this site were obtained from various locations over google and screen shots of the games
All game info and names created by Jane Jensen and games all produced by Sierra and Pinkerton Road Studios

### Complicated Code
- Automated typing Javascript code for the welcome page:
    - https://codepen.io/gavra/pen/tEpzn
- Timeline of events:
    - https://bootsnipp.com/snippets/a3BjR


## Git Commits
Previously I did have a full line of commits for this project, but I recreated my site to look more professional. My full history of commits can be seen [HERE](https://github.com/RMSchrader1994/project1)

## Planning
All wireframes and planning documents can be found in the stream1Project folder here in the repository. The comments page was replaced by the quiz page.

### Difficulties

## Color Palette
Originally the site had a more colorful palette. The home page had a background image that can be found towards the bottom of the page now, the game pages all had different colors to match their respective games (Sins of the Father was purple, The Beast Withing was blue, and Blood of the Sacred Blood of the Damned was orange), and the quiz page had its own stylized background. After presenting the project during Careers Week I toned down the colors and kept them constant throughout the entire page, as to follow the helpful advice of Jim Cassidy.

## Quiz
When I first started this course I had no experience with **Javascript**. I based the code for the quizzes on the maths game we created during Stream 1 and extensive google searches. The radio buttons were the easiest to score, but I had also used text fields checkboxes. The text fields were the easier of the two, all I had to do was compare the entered value to a pre defined correct answer. The checkboxes were extremley challenging and took a couple weeks and extensive google searches to find the answer. It would have been easier to ask for help, but I wanted to find the answer myself and I did in the end. In the end I created 2 arrays. One contained the correct answers to the question and the other was empty. The later would be used to store the user's answers. If the arrays matched then the user would get the point.  