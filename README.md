
  
## Interactive function plotter
  
<section id="plotSettings">
  	<label for="xMin">xMin: </label>
  	<input type="number" id="xMin" value="0" step="0.5" oninput="plot();">
  	
  	<label for="xMax">xMax: </label>
  	<input type="number" id="xMax" value="6.28" step="0.5" oninput="plot();">
  	
  	<label for="yMin">yMin: </label>
  	<input type="number" id="yMin" value="-1" step="0.5" oninput="plot();">		
  	
  	<label for="yMax">yMax: </label>
  	<input type="number" id="yMax" value="1" step="0.5" oninput="plot();">
  	
  	<label for="color">Color: </label>
  	<input type="color" id="color" onchange="plot();">
   	
   	<label for="function">Function to plot: </label>
   	<input id="function" type="text" value="sin(x)" onchange="plot();">
    
  </section>
  <section id="plot">
     <div id="myFunction"></div>
  </section>

