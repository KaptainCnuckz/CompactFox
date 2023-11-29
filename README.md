# CompactFox

### Dark Theme Preview:
![Showcase img](https://raw.githubusercontent.com/KaptainCnuckz/CompactFox/main/Images/compact%20fox%20update%20preview%20DARK.png)

### Light Theme Preview:
![Showcase img](https://raw.githubusercontent.com/KaptainCnuckz/CompactFox/main/Images/compact%20fox%20update%20preview%20LIGHT.png)

Small update to Compact Fox for minor tweaks I've made for my own personal use. 
- Fixed the font of URLs in the location bar being cut-off
- Removed the garish color swap for inactive tabs so they'll use your theme colors
- Hid the star in the location bar, as a work around for its misalignment

Forked it publically in case anyone wanted to use the same improvements. Enjoy!

## Install
1. Go into the "about:profiles" page of your Firefox.
2. Under your person profile, to the right of the "Root Directy" listing, click "Open Folder."
3. In this folder, create a new folder named "chrome" if there isn't one.
4. Extract userChrome.css and powerUser.css into the chrome folder.
5. (Optional) In userChrome.css, uncomment "/* @import "powerUser.css"; */" (aka delete the forward slash and asterix).
6. Go into "about:config" page of your Firefox, and set "toolkit.legacyUserProfileCustomizations.stylesheets" to "true"
