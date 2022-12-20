# Firefox 

## This are my personalized userChrome.css and betterfox json file.

These are my personalized userChome.css and betterfox json file. The userChrome file is basically oneliner from MrOtherGuy/firefox-csshacks with some edits and the user.js file is from Betterfox.

## How to use these?
- At first install git.
- then open a terminal and type git clone https://gitlab.com/asifakonjee/firefox.git
- cd firefox/
- Here, you have two files name userChrome.css and user.js

### Now, follow these steps to use these files:
1. First open your firefox and type about:config in the address bar. Accept the risk and continue. 
2. Type legacy in the search bar. 
3. change toolkit.legacyUserProfileCustomizations.stylesheets to True.
4. Type about:profiles in the address bar.
5. Profile: default-release is the profile that is default. Open the root directory.
6. Make a new folder with the name "chrome".
7. Open that folder and copy the userChrome.css file in it.
6. Copy the user.js file to the chrome folder.
8. Restart firefox and enjoy.

## Reference:
1. https://github.com/MrOtherGuy/firefox-csshacks
2. https://github.com/yokoffing/Betterfox
3. Video Tutorial for userChrome.css: https://www.youtube.com/watch?v=aCdFs6rgeNI
4. Video Tutorial for Betterfox: https://www.youtube.com/watch?v=w0SJFED5xK0
