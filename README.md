# 2770942M_Final_Assignment
Lewis mawer, mechanical engineering skills, Computing assignment markdown file report

This report follows the code made for the assignment; 'Numerical Integration - Rectangular Rule and Trapezoidal Rule', the codes initial and main aim is to calculate the area under a given function using trapezoid rule, aswell as either leftside rule or midpoint rule.

The starting point was figuring out on paper the best way to implament the midpoint rule, this led to the equations shown below. 
This was tidied up, and the Trapezoidal rule was added, both proved with many variables and functions. This is the main objective, of assignment, but it is just the base of the code.


<img src="https://github.com/trevorbake24-gif/2770942M_Final_Assignment/blob/38ec5c1e6795712d9089240fb85950aaba37c088/Screenshot%20(202).png" width="400" height="900"> <img src="https://github.com/trevorbake24-gif/2770942M_Final_Assignment/blob/5bf7a8cc3f12d12351ae999afa868a10ad9c983e/Screenshot%20(203).png" width="400" height="350">

The leftside rule was mostly calculated here due to the midpoint equations, so it was added aswell. Then the function's graph was added to display the shape in the calculations, this also meant the slice lines needed to be visible, so they were added using the grid, but omitting the horizontal lines, and basing it on the slice input, n.


<img src="https://github.com/trevorbake24-gif/2770942M_Final_Assignment/blob/28972b38739eb7ac4513fef75e04a6a99dd59501/Screenshot%20(208).png" width="400" height="700"> <img src="https://github.com/trevorbake24-gif/2770942M_Final_Assignment/blob/d088ebc9dd5816a8d1f6e774ad0253f827f9bb32/Screenshot%20(209).png" width="400" height="1200">


To make the code easier to use with different functions and variables, it was changed so these were all inputs at the start, being; the function, the x axis limits and the number of slices, n. This was disabled except for n for the data collection requested for assignment, but useful for code outwith.


<img src="https://github.com/trevorbake24-gif/2770942M_Final_Assignment/blob/2e75e6455250a00b3274832fa43e953f60341fb1/Screenshot%20(207).png" width="400" height="900">


The next objective was to fill in the area under the graph, as this was what these methods were to calculate.

<img src="https://github.com/trevorbake24-gif/2770942M_Final_Assignment/blob/f446bcbefb4f40c8def16e6af2bc0449ead9dd15/Screenshot%20(210).png" width="400" height="900"> 

However once this was done it was clear that a graph of each method and their actual shape was needed.
The midpoint and leftpoint methods for this were quite straight forward as they were bar graphs, so the trapezium rule was done first, giving us this.

<img src="https://github.com/trevorbake24-gif/2770942M_Final_Assignment/blob/4076e3c19e2e296781b37f88821890f0881982e3/Screenshot%20(211).png" width="400" height="900"> <img src="https://github.com/trevorbake24-gif/2770942M_Final_Assignment/blob/bf3d0ca949af49e70268b1ce4ef97645f5bd8614/Screenshot%20(213).png" width="400" height="900">


After that the graphs were tidied with titles, colours, clear lines and put into subplots to make more appealing and easy to compare.

<img src="" width="400" height="900">


For the function set to x, sin(x) & e^(-x) *sin(x) each with the value of aproximation, n increasing, results as shown;

<img src="" width="400" height="900">

<img src="" width="400" height="900">
<img src="" width="400" height="900">
<img src="" width="400" height="900">
<img src="" width="400" height="900">
<img src="" width="400" height="900">
<img src="" width="400" height="900">
