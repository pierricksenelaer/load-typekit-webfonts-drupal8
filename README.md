# load-typekit-webfonts-drupal8
Drupal 8 module to load the web fonts kit generated with Typekit


# USAGE

If you use Typekit (https://typekit.com/) to serve web fonts on your Drupal 8, then you may find this module useful

__`git clone`__ this repo and look for the __`<kitId>`__ placeholder which should be replaced with whatever ID, your kit you generated from Typekit has.

Typically, this ID can be found at __`kits > select your kits > embed-code`__

### D8 INTEGRATION
Folder structure and installation may differ from one developer/company to another but this module would tytpically be saved at 

__`<repo_name>/docroot/modules/custom/`__

OR

__`<repo_name>/web/modules/custom/`__

Use the command line or the GUI to enable this module

### THAT'S IT?
No. You need to declare your web fonts in your stylesheet. An example would be -

__`@font-face {
  font-family: ProximaNova-Light;
  src: url("../fonts/ProximaNova-Light.otf") format("opentype");
}`__

__`@font-face {
  font-family: ProximaNova-Regular;
  src: url("../fonts/ProximaNova-Regular.otf") format("opentype");
}`__

__`@font-face {
  font-family: ProximaNova-Semibold;
  src: url("../fonts/ProximaNova-Semibold.otf") format("opentype");
}`__
