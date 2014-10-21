# NodeBB Custom Font Plugin

This NodeBB plugin allows Admins to specify custom fonts that aren\'t available through Google Fonts or other online avenues.

## Installation

    Fork this plugin to your own repo and rename. (This plugin is on npm to avoid anyone uploading it accidentally, however the plugin WILL NOT WORK)
    Open the following files: plugin.json, package.json & style.less.
    If you have a webfont already and all required versions of that font, you're good to go, if not, use [this website](http://www.fontsquirrel.com/tools/webfont-generator)
    to create your webfont package. Add the files you downloaded with these extensions to the src folder: eot, woff, woff2, ttf and svg. You can ignore all other files and folders.
    Within style.less, do a Find & Replace on `WebFont` and replace it with the name of your font as displayed in the src folder. (you can use the style.css file that font squirrel gives you and just paste this in instead if you prefer)
    Double check you've changed all references & issue URLs of the plugin and all associated links to issues etc, and push to your github.
    Navigate to your node_modules folder and run  `git clone` followed by the https Clone URL found on the github repo on the right hand side.
    You can either specify what should use this font in custom ACP under Appearance > Custom HTML & CSS by doing something along the lines of `.h1 { font-family:WebFont }

    If someone would like to extend this, adding an ACP and allowing people to chose their webfonts, then you're welcome to.

##Changes
    0.0.1:
     - Initial Commit with Dummy Data (this will not work as is, please read the above first before cloning.)