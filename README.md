# Blu's Custom Character Card
This repository gives you all the needed code and CSS to add your own custom char card, including recoloring the FS3 dots both on the card and on the character profile.

## Components
There are two components to this repository--first is the CSS styling additions you will need to add to your CSS style file, and the second is the custom card code itself that you will add to the custom-char-card.hbs file in the ares-webportal directory.

## CSS Style Information
This style information assumes that you are using all components of FS3--abilities, skills, background skills, and advantages. If you are not using Advantages, you shouldn't need to remove the Advantages styling code, but you could without actually breaking anything. I have left spaces to put your own font styling for the char card headers.

Want to pair this with Tat's amazing SimpleInventory plugin? Code is available for that, too!

I have also added the dot-coloring for both char card and char profile. If you don't want to color-code those, you can just remove that segment of code without breaking anything in either the location. At present, the colors match the FS3 colors. You'll also get my full muted rainbow colors! BONUS!

## Custom Character Card
To add the character card update, you will need to go into the shell, and add the char code to this directory: ares-webportal/app/templates/components/char-card-custom.hbs
