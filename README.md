#Prototype Website for RED with Foundation 5

Visit the [Live Site](http://redproto.herokuapp.com)

###Design Concept

Red promises to bring simplicity back to programming. 

This design concept underlines that promise by stripping away extraneous elements and uses solid colors with typography to present key information.

1. The color palette is simply red and grey, with black text on white for readability. 
2. Key headers are oversized to emphasize their importance. 
3. Calls to action uses red/grey buttons


###Prototype implementation

The design prototype is created with Ruby on rails 4 for expediency. To ease future porting to Quartermaster (or any other REBOL framework) the following methods are used:

1. Use of Partials is limited to topbar, page content, and footer.
2. Use of Rails helper methods is limited to image_tags for the logo and asset includes.
3. Foundation.css instead of scss.
4. Customization of foundation design elements is kept to a minimum. 


1. js and css files in ../assets/ folder (jquery.js in /vendor/assets/javascripts to ensure it loads first)
2. html files in ../views/ folder

 
