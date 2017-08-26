Instructions for Website Optimization Project:
=============================================
1. Download the zip file: Perf-optimization.
2. Go to the extracted folder, Perf-optimization, and open the'dist' folder.
3. Start a web server to run the command: $ python -m SimpleHTTPServer 8000.
4. Open the browser and go to http://localhost/8000 and open index.html

Optimization of index.html:
=============================================
1. Loading Google Fonts Asynchronously For Page Speed
2. Inlined both stylesheets: style.css and print.css 
3. Made Google Analytics script asynchronous.

Optimization made to views/js/main.js:
=============================================
1. Modfied the changePizzaSizes function to select randomPizzaContainer elements by class name
2. Removed the determine dx and moved the randomPizza variables outside of the loop.
3. Modified the updatePositions function to select the mover elements by class name.
4. Moved the scrolltop variable outside of the loop.
5. Moved the declaration of the pizzaDivs variable outside of the for loop.
6. Changed the querySelector call for selecting movingPizzas1 element to getElementById.
