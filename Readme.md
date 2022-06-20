# Personal project "PINK"

“PINK”. Adaptive Website. The project was implemented HTML&CSS, Adaptive Website Coding and Automation. Less, Gulp, JS, Figma, Webstorm. 

Adaptability of the grid: mobile, tablet and desktop versions ("fix" or "rubber").
Adaptive graphics: retinization, vector images.
Methodology used: BEM.
The preprocessor used is Less or Sass.
The automation tool used is Gulp.
Libraries in use: None.
CrossBrowser: Chrome, Firefox, Safari.
Font used: Open Sans.

With a fixed grid, the content area is centered and cannot already be layout width. Backgrounds that rest on the edges of the layout is stretch the entire page.
The logo on the inside pages is a link to the home page.
The main menu in the mobile and tablet versions appears under the site header.
The mobile menu can be implemented in two ways:
  JS-free implementation;
  implementation using JS.
When implementing without using JS, the main menu of the mobile and tablet versions should always be open, and the icon with a cross is hidden.
When implemented using JS, the main menu block in the mobile and tablet versions should open when you click on the "hamburger" icon. When the menu is open, the "hamburger" icon is replaced with a cross. When you click on the icon with a cross, the menu closes
All states of elements when hovering and pressing are specified in the stylegide.
The Academy logo and the HTML Academy link in the footer lead to the intensive landing "Professional HTML and CSS, Level 2."

---
**Main**

**Mobile version (Index > Mobile):**

The logo consists only of the name of the Pink application.
The button in the "Download Application" block leads to the default market (App Store).
Icons in the "Download application" block are also links and lead to the corresponding markets.
Application Characteristics unit (phone unit): the image on the screen must be static, without scrolling through the images on the screen.
The "Reviews" block: scrolling through reviews is not necessary to implement. A sufficient implementation will be a rolled-up 1 review and feedback switching buttons.
Unit "Tariffs": scrolling through tariffs is not necessary to implement. Sufficient implementation will be reduced 3 tariffs.
Map block: the necessary implementation is an interactive map (Google map), the width is adjusted to the width of the viewport (but not already the content width of the layout), a marker is placed on the map (can be both custom and default), the center of the map corresponds to the center of the block in the layout.

**Tablet version (Index > Tablet):**

Blocks resize and reposition according to layout.
New elements are added to the logo.
The Tariffs block is located in the center of the page and does not have controls for switching.
A basement block is added after the map.


**Desktop version (Index > Desktop):**

Blocks resize and reposition according to layout.
New elements are added to the logo.
The main menu is always open regardless of its state on the mobile and tablet versions.
In the "Feedback" block, the controls for switching are changed.

---

**Form**

**Mobile version (Form > Mobile):**

Custom elements of forms shall be implemented.
The phone and mail input fields must have the appropriate types for easy filling from the phone.
When you try to send a form in which the fields for entering phone or mail are filled with data in the wrong format, an error message embedded in the browser appears.

**Tablet (Form > Tablet) and Desktop versions (Form > Desktop):**
Blocks resize and reposition according to layout.

---

**Page with photos and videos (Catalog)**

**Mobile version (Photo > Mobile):**

All images are links to the full-size version (opening a full-size image does not need to be implemented).
There is no need to implement an image processing tool in the block in front of the basement, only a string is enough.
Each image processing element has its own slider for adjustment, but only the active one is shown in the mobile version.
The Post button sends a form with parameter values.
The Cancel button resets all filter settings to their original state.

**Tablet version (Photo > Tablet) and Desktop version (Photo > Desktop):**
Blocks resize and reposition according to layout.



