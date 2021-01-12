
## Interactive function plotter
  
<html lang="en"> 
<head>
  <title>Plotting functions in JavaScript using the 
    function plot library</title>
  <meta charset="utf-8"/>
  <script src="https://d3js.org/d3.v3.min.js"></script>
  <script src="https://mauriciopoppe.github.io/function-plot/js/function-plot.js"></script>
  <link rel="stylesheet" href="style.css">
  <script src="script.js"></script>
</head>
<body onload="plot();">
  <h2>Interactive function plotter</h2>
  <section id="plotSettings">
  	<label for="xMin">xMin: </label>
  	<input type=number id="xMin" value=0 step=0.5 oninput="plot();">
  	<p></p>
  	<label for="xMax">xMax: </label>
  	<input type=number id="xMax" value=6.28 step=0.5 oninput="plot();">
  	<p></p>
  	<label for="yMin">yMin: </label>
  	<input type=number id="yMin" value=-1 step=0.5 oninput="plot();">		
  	<p></p>
  	<label for="yMax">yMax: </label>
  	<input type=number id="yMax" value=1 step=0.5 oninput="plot();">
  	<p></p>
  	<label for="color">Color: </label>
  	<input type=color id="color" onchange="plot();">
   	<p></p>
   	<label for="function">Function to plot: </label>
   	<input id="function" type="text" value="sin(x)" onchange="plot();">
    <p></p>
  </section>
  <section id="plot">
     <div id="myFunction"></div>
  </section>
</body>
</html>

