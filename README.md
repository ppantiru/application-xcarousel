application-xcarousel
=================

Application that allows to create carousels.

For each carousel you create you have a variety of settings:

For the general carousel:

 * Auto-sliding on/off
 * The interval for automatic sliding
 * The width of the carousel
 * The height of the carousel
 * The background color (with a color picker or by hand if you know the css id for the color)

For each slide you can set:

 * A different image (doh)
 * A caption title
 * The size for the caption title
 * The color for the caption title (with a color picker or by hand if you know the css id for the color)
 * Some caption text
 * The size for the caption text
 * The color for the caption text (with a color picker or by hand if you know the css id for the color)
 * And a link for the caption title

Usage
=====

After installing the extension with EM, go to XCarousel.WebHome

Here click the ADD NEW ENTRY from the Actions section on the right, and give a name to your new carousel.
You will then be prompted to the carousel's edit mode, where you can set it up as you like.
By default the auto-sliding optin will be enabled, and 3 empty slides will be created automatically.
Create or delete as many slides as you want using "Add new slide/Delete Slide" buttons, and set an image for each of your slides.

* Adding an image for each slide is the only mandatory thing to do for the carousel to function.

After the setup is done, you can insert the new carousel into any page using the display macro.

ex: `{{display reference="XCarousel.Demo" type="document"/}}`

