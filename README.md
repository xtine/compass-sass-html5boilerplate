# Description #
This is currently my setup for a bootstrapping a static web HTML/CSS/JS project using the Compass Framework and SASS. I opted to not use Compass' reset and instead use the HTML5 Boilerplate CSS stylesheet for a base reset.

## How to Use ##
All Compass+SASS related files are in the /compass folder.
The config file is set up to be ready to go. For your edits in /compass/sass/ css to be compiled automatically, run the watcher command `compass watch` within the /compass folder. Then all your changes in the SASS files will be compiled into the css folder.

### CSS Files (/css) ###
You can either create an empty /css directory at trunk level or it will be created with the initial SASS to CSS compilation.

### Image Files (/img) ###
Create a folder named /img at trunk level and place your images there. Create additional folders for the fancy Compass spriting engine to do the work for you (after a @import "sprites/*.png" in base stylesheet)!

## Documentation for Libraries ##
* <a href="http://html5boilerplate.com/">HTML5 Boilerplate</a>
* <a href="http://compass-style.org/">Compass Framework</a>
* <a href="http://sass-lang.com/">SASS</a>
