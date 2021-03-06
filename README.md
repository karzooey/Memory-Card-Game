
# <p align="center">[Use Your Brain!](https://karzuin.github.io/MS2/)</p>

A memory card game featuring images of Star Wars characters in lego form which I found amusing, fun and cute. The game is for users of all ages who 
would like to improve their memory whilst also enjoy looking at the images too.
The website consists of the main page with beautiful quality photos, pleasing to the eye, inspiring to look at and simple, not too 
much text, as for myself I don’t like busy looking websites, I like simplicity and beauty. As too much information gets confusing, messy 
and overwhelming.

Reasons users may be want to play this game:
- To improve their memory. 
- To pass the time. 
- Like the humorous quality images. 

# UX

A simple and clean looking website that introduces the user to a single player memory card game consisting of one page:
- A clean, simple look, with succinct instructions.
- The cards are quite large in order to enjoy the images better.
- When the player has finished/won the game, a popup modal matching the colours of the images appears
giving the user the time it took for them to finish and how many moves they made and the choice to play again.
- At the bottom of the card images is a simple and clean scoreboard consisting of a moves counter, minutes and seconds timer 
and the restart button.

## User journey:
1. The user begins at the Home page, reading the simple instructions of 'Click the cards to find the matching pairs' under the 
main heading 'Use Your Brain!'.
    
<p align="center"><img width="200" height="250" src="readme-images/homepage.png"></p>

2. The user then sees the deck of 16 cards in a 4 by 4 grid, all displaying a photo image of the words "USE YOUR BRAIN",
these are the cards to be clicked.

3. Scrolling down the page further and user sees the scoreboard underneath the images which consists of three features:
Firstly, a counter to keep track how many clicks the user makes, secondly, a timer displaying in minutes and seconds how long it takes
for the user to find all the matching pairs to finish the game and finally a restart button where they can choose to start again whenever they want,
if they get distracted during the game, get frustrated, or leave the game for any other reason to start again.

4. As soon as the first card is clicked the moves counter and timer begin until all the matching pairs are found or the restart button is clicked.

5. When all the pairs of cards have been matched a victory popup modal appears with a congratulating message and displays the time it took for 
the player to finish and how many moves they made and a button to click if the player chooses to play again. The popup appears under the card deck
instead of on top because then the user can enjoy looking at all the images when they have finished.

<p align="center"><img width="200" height="250" src="readme-images/homepage_victory.png"></p>

## User stories:

- As a user, I want a simple and clean looking website as messy, busy pages with lots of information overwhelms me.

- As a user, I want an easy to navigate website to save time and not get frustrated or lost.

- As a user, I want to be able to use it on desktop, tablet and mobile devices.

- As a user, I want to have a counter to keep track of how many moves I make to finish the game.

- As a user, I want to have a timer to keep track of how long it takes to finish the game.

- As a user, I want to have a restart button that resets all the features whenever I want.

- As a user, I want a victory popup message to tell me when I've finished the game, displaying how many moves I made and the time it took
for me to finish the game. It should also have a button to play the game again.

- As a user, I want to see interesting, quality images.

- As a user, I don't want the popup message to cover the images when I've finished the game so I can see them all properly.

- As a user, I want to see interesting and fun images some easy to memorise and some not so easy.

- As a user, I want simple instructions.

- As a user, I want to challenge my brain and exercise my memory.

## Wireframes
I used [Pencil](https://pencil.evolus.vn/) to create [wireframes](https://github.com/karzuin/MS2/tree/master/wireframes) in desktop, tablet and phone view.

# Features

The homepage consists of the main heading and the simple, clear instructions of how to play in a smaller heading underneath.
The card game appears under the heading in a 4 x 4 grid displaying 16 images of a photo with the text saying 'Use Your Brain'
which inspired me to name the game the same name.

The card sizes are larger than most card games seen online, as I wanted the images to be seen and appreciated.

The scoreboard is underneath the grid featuring three tools: 
- A counter that keeps track of how many moves/ clicks a player makes.
- A timer in mintues and seconds that keeps track of how long it takes for the player to finish the game.
- A restart button, which allows the player to restart the game whenever they want by reloading the page.
Underneath is the copyright information.

I chose a simple clean font that matched the image I found with the text Use Your Brain! called 'Quicksand' to stay consistent with the overall look. 

The font colours are black, pink and blue which matches the colours of the images. The background colour is white.

The victory popup appears when all the card pairs are matched. Initially it appeared on top of the card deck but decided to move it below the card
deck so that the player could admire the cards when finished. I added a black border around it so it can be seen when the player finished the game.
The font colours of the popup are also the pink and blue that are used in the heading and scoreboard to keep the overall look consistent.

# Features Left to Implement

- To be able to have difficulty levels, with harder images to memorise and more cards to match.

- To keep your score and try to beat it next time.

# Technologies Used

- [Gitpod](https://gitpod.io/) 
  - IDE (Integrated Development Environment).

- [GitHub](github.com/) 
  - The remote hosting platform. 

- [HTML 5](https://en.wikipedia.org/wiki/HTML5), [CSS 3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) and 
[JavaScript](https://www.javascript.com/)
  - The programming languages used for this project.

- [Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools) 
  - To see visually the elements of what each code produced, what happens if code is changed, and responsiveness of different device sizes.

- [Autoprefixer](https://autoprefixer.github.io/)
  - To check CSS browser compatibility.

- [Jigsaw](https://jigsaw.w3.org/css-validator) 
  - To check for any errors in the CSS code.

- [W3C Markup Validator](https://validator.w3.org/) 
  - To check for any errors in HTML code.

- [Font Awesome](https://fontawesome.com/) 
  - This library was used for the copyright icons.

- [Google Fonts](https://fonts.google.com/) 
  - This is where I found the Quicksand font family.

- [Favicon](https://favicon.io) 
  - To include a lego icon on the web browser tab.

# Testing 
Testing information is found on a separate file [TESTING.md](TESTING.md)

# Deployment

  
### How I deployed my MS2 memory game project remotely to Github pages:

1. Go to [GitHub.com](https://github.com/)

2. Log into my account

3. Click on ‘Repositories’

4. Click on ‘MS2’

5. Click on ‘Settings’

6. Scroll down to the ‘Github Pages’ section.

7. Under the ‘Source’ heading there is a dropdown menu click on ‘None’, and select ‘Master Branch’. Click on save.

8. The page refreshes and goes back to the top of the page, scroll down to ‘Github Pages’ section and find ‘Your site is ready to be published at ________’ with your link. The website is deployed.

   [Follow this link](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
on how to deploy to Github pages.

### How to run code from my MS2 memory game project by cloning in Github to Repl:

1. Go to [GitHub.com](https://github.com/)

2. Log into my account

3. Click on ‘Repositories’

4. Click on ‘MS2’

5. Click on the green button ‘Clone or download’

6. Click on ‘Download Zip’

7. Open IDE [Repl.it](https://repl.it/)

8. Upload folder or files

### How to run code from my MS2 by cloning in Github to Gitpod:

1. Go to [GitHub.com](https://github.com/)

2. Log into my account

3. Click on ‘Repositories’

4. Click on ‘MS2’

5. Click on the green button ‘Clone or download’

6. Click on the icon that looks like a clipboard on the right side of the URL (this copies URL link)

7. Open repo or create new repo

8. Open terminal

9. Type `git clone` and paste URL link and press enter.

# Credits

### Content

#### Text for the index.html:

- Is written by me.

### Media

#### Images for index.html:

- Card images Lego characters from [Unsplash](https://unsplash.com/@danielkcheung)

- Card image 'Use Your Brain' from [Unsplash](https://unsplash.com/photos/Iod3vdjKE1E)

#### Image for web browser tab:

- [ICONS8](https://icons8.com/icons/set/lego)

### Code

- The memory card game template code is from [Tania Rascia](https://www.taniarascia.com/how-to-create-a-memory-game-super-mario-with-plain-javascript/).

- [W3 Schools](https://www.w3schools.com/css/css3_3dtransforms.asp) to keep cards visible when matched.

- [Sandra Israel Ovirih](https://scotch.io/tutorials/how-to-build-a-memory-matching-game-in-javascript) pointed me in the right direction of how to create code for 
the timer, counter and popup modal features.

- [Stack Overflow](https://stackoverflow.com/questions/952924/javascript-chop-slice-trim-off-last-character-in-string) 
to use slice method for timer.


# Acknowledgements

Also thank you to the [Code Institute](https://codeinstitute.net/) slack channel, [CI](https://codeinstitute.net/) tutors and mentor [Precious Ijege](https://www.linkedin.com/in/precious-ijege-908a00168/).
