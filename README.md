# TEMPLATE-SYSTEM
Template System - Turn Your Template Into A Static Website


## HOW TO INCLUDE YOUR STYLESHEETS INTO THE SYSTEM

1: Place all of your .scss stylesheets inside the vendor folder.
  - Make sure each has an underscore added to the front of the name.
  - Example: stylesheet.scss becomes _stylesheets.scss
2: Enter the stylesheet includes below.
  - Example: @include 'vendor/style';
  - Leave the .scss out of the include.

