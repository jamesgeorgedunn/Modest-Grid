#Modest-Grid

Modest Grid is a super lightweight grid system developed to create responsive prototypes. With the CSS weighing in at just over 1kB, it truly is a super lightweight.

What really sets Modest Grid apart are its naming conventions for the column classes it uses.

###.dt-[1 to 12/16] Desktop (1024px and up).

###.tl-[1 to 12/16] Tablet landscape (1024px).

###.tp-[1 to 12/16] Tablet portrait (768px).

###.ml-[1 to 12/16] Mobile landscape (568px).

###.mp-[1 to 12/16] Mobile portrait (320px).

A great option that comes with Modest Grid is the ability to change the gutter width using the gutter variable written in SASS. This way you don't have to worry if you have set the correct padding and margins. This is much more reliable than the find and replace method is it won't replace any code that you may want left such as the width of an element.

##12 or 16 columns
Modest Grid has two separate CSS files.

	modestgrid-12.css
	modestgrid-16.css

This allows you to choose a grid system that works best with your design. Instead of going adding from 1 to 12 you are able to go all the way to 16. This nice little extra allows you to work in eighths.

#Compatibility
Modest Grid is still in its early stages and thus hasn't been fully tested. It will however work fine in more up to date web browsers.