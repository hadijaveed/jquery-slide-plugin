# jquery-slide-plugin
Jquery plugin that slides the menu from top of the navbar. Initialise slide from top menu function on your
menu with the following parameters.
  ```javascript
  $(document).ready(function() {
    $('.mobile-side-menu').slideFromTop({
    menuBtn: $('.toggleMenu'),  // button that opens your menu
    navbar: $('.navbar'),      // nav bar on the top of the menu
    menuSpeed: 500,           // animation speed
    bodyOverlay: $('.overlay') // a modal like overlay to throw on the body
    });
  });
  ````
