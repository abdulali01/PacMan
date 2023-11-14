# PacMan
## Free form of pacman going from right to left and reverse.

Overview:  This is first program that mimic the classic game of Pacman.  Pacman is triggred once a page is uploaded.  It will continue to run until you can close your browser or referesh it.

Technical Spec:
  Simple start to showcase capabilities of HTML, CSS, Javascript.

Language Used:
1. Pacing pacman from left to right using Javascript build into HTML.

  iteration 1 - 9/09/2023
  HTML and Javascript, CSS

  _____________________________________________________________

How to access the repo:
1. To execute it in your current browser <a href="https://abdulali01.github.io/PacMan/"> PacMan</a>
2. Locally down the files and review the information by visiting <a href="https://github.com/abdulali01/"> Github HomePage</a> -> Go to repositoriess


HTML:
Body contains an img tag.
    ID, SRC, width, onclick, & style.
Javascript:
    currently in the HTML with scripts tags.

    pos: starting position of the image
    pageWidth = window.innerWidth // avoided static windows width.
    Array to capture the images.  Right facing and left facing.
    Direction: if 0 moving right, if 1 moving left.  Boolean value.
    Focus is set to zero as well.
    Run Function is used to validate based on a click.
    SetInterval contains two arguments Run and time.

    Key function - checkPageBounds => means travel righ to left or left to right.  It will detect windows inner width.

    in a very simple way to validate and check if the position + image widht is > Windows Width.  If it is, direction will be 1.  1 means going from right to left.
    If the pos is < 0 => direction is 0.  Moving from right to left.  
    
  Future Iteration - Q1 2024
  expansion of HTML and Javascription code to include flexiblity to interaction from the user
    Moving forward and backward
    Moving up and down
    still have the ability to run and auto detect end of screen.

  Future Iterration - Q2 - 2024
    obsticles where pacman need to avoid the obsticles like balls, arrows, bumps etc.
    
