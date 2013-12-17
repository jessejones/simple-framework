simple-framework
================

Usage
----------------

Using Simple is just as easy as the name suggests. After putting a link to simple.css in the &lt;head&gt; of your HTML page, insert a div with a class of .container and then add another div with a class of .row. Add columns by writing w— stands for width—followed by a fractional value such as 1-3. So for instance if you want a 3 column grid, you would use 3 divs, each with a class of w1-3. See below for an example.

	<div class="container">
		<div class="row">
			<div class="w1-3">
				Content
			</div>	
			<div class="w1-3">
				Content
			</div>	
			<div class="w1-3 lastCol">
				Content
			</div>								
		</div>	
	</div>

Grid
----------------

Simple uses a fluid 960 grid that scales gracefully with any screen size. The container element can be changed to any width desired and percentage based columns will adjust accordingly.

Typography
----------------

A set of base styles are used to create a strong typographical hierarchy. The typographical hierarchy is defined by specifying a percentage-based font-size for &lt;h1&gt; through &lt;h6&gt;. This ensures that even if someones enlarges their type your layout will stay typographically sound.

Media Queries
----------------

Simple uses a set of media queries at 960px, 767px, '& 480px. To change the size of your content adjust the .container values.
