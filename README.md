# 2770942M_Final_Assignment
Lewis mawer, mechanical engineering skills, Computing assignment markdown file report

This report follows the code made for the assignment; 'Numerical Integration - Rectangular Rule and Trapezoidal Rule', the codes initial and main aim is to calculate the area under a given function using trapezoid rule, aswell as either leftside rule or midpoint rule and to find data over specific inputs.

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
The midpoint and leftpoint methods for this were quite straight forward as they were bar graphs, so the trapezium rule was done first, giving us this. Second image below shows code for both midpoint and trapezium rules.

<img src="https://github.com/trevorbake24-gif/2770942M_Final_Assignment/blob/4076e3c19e2e296781b37f88821890f0881982e3/Screenshot%20(211).png" width="400" height="900"> <img src="https://github.com/trevorbake24-gif/2770942M_Final_Assignment/blob/bf3d0ca949af49e70268b1ce4ef97645f5bd8614/Screenshot%20(213).png" width="400" height="900">


After that the graphs were tidied with titles, colours, clear lines and put into subplots to make more appealing and easy to compare.

<img src="https://github.com/trevorbake24-gif/2770942M_Final_Assignment/blob/9ca7ac6f16a31dd88cbf4f4f1231abd1db5e5d89/Screenshot%20(214).png" width="800" height="900">


For the function set to x, sin(x) & e^(-x) *sin(x) each with the value of aproximation, n increasing, results as shown;

<img src="https://github.com/trevorbake24-gif/2770942M_Final_Assignment/blob/1a3066b7d8af41d6b68198ec9b3ea7a9ed55863b/Screenshot%20(224).png" width="1000" height="1200">

Images of graphs at n=2 for f(x)= x, sin(x), and e^(-x) *sin(x), diplayed left to right.

<img src="https://github.com/trevorbake24-gif/2770942M_Final_Assignment/blob/fd0003024dc3c41529b3092253da0fa48e330f43/Screenshot%20(215).png" width="300" height="900"> <img src="https://github.com/trevorbake24-gif/2770942M_Final_Assignment/blob/2e0c73c840c495eca71b4e04cb0a26d9a731a684/Screenshot%20(219).png" width="300" height="900"> <img src="https://github.com/trevorbake24-gif/2770942M_Final_Assignment/blob/87d87ae79683b7555f4c53c35b1d04d45ce2f325/Screenshot%20(221).png" width="300" height="900">


<img src="" width="300" height="900">
<img src="" width="300" height="900">
<img src="" width="300" height="900">
