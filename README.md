CSS Media Queries are used to apply different styles based on the characteristics of the user's device or screen, such as width, height, orientation, or resolution. 
They are a core part of responsive web design, enabling a website to adapt its layout and appearance to various devices like smartphones, tablets, and desktops.
A media query consists of:
A media type (e.g., screen, print).
Optional media features (e.g., width, orientation) that define the conditions for applying the styles.
The CSS rules that will be applied if the conditions are met.
@media media-type and (media-feature) {
  /* CSS rules */
}
//
//
//
\\
\\
\\
Eg:
@media screen and (max-width: 768px) {
  body {
    background-color: lightblue;
  }
}
This example changes the background color of the body to light blue if the screen width is 768px or smaller.

