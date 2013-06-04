simple-framework
================

Usage
----------------

Using Simple is just as easy as the name suggests. After putting a link to simple.css in the "<head>" of your HTML page, insert a div with a class of .container and then add another div with a class of .grid. Add columns by specifying a class of col1 through col12. So for instance if you want a 3 column grid, you would use a 3 divs, each with a class of col4. See below for an example.

	<div class="container">
		<div class="grid">
			<div class="col4">
				Content
			</div>	
			<div class="col4">
				Content
			</div>	
			<div class="col4">
				Content
			</div>								
		</div>	
	</div>

Grid
----------------

Simple uses a 12 column, fluid 960 grid that scales gracefully with any screen size.

Typography
----------------

A set of base styles are used to create a strong typographical hierarchy. The typographical hierarchy is defined by specifying a percentage-based font-size for "<h1>" through "<h6>". 

Media Queries
----------------

Simple uses a set of media queries at 960px, 767px, & 480px. To change the size of your content adjust the .container values using the max-width CSS property. It's best to use percentages at each of the sizes so the grid stays fluid.