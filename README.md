# Visualization 1: Nightingale’s Rose Chart
  
## Description:
The visualization is achieved using ‘d3.js’ JavaScript library, CSS and HTML. All the SVG elements are created using d3.js. Steps involved in building the visualization are:
1. Created the SVG element.
2. Started appending arcs using ‘arc’, ‘attr’ and ‘translate’ functions for:
a. Displaying month and year
b. People died because of disease (Annual Mortality Rate)
c. People died because of wounds (Annual Mortality Rate)
d. People died because of other reasons (Annual Mortality Rate)
3. Added relevant title to all the arcs. (e.g. For disease arc, used number of people died because of disease)
4. Added legends to provide information regarding colors and associated categories.
5. Implemented interaction on hover of legends to view data related to the same category. 6. Implemented a slider to zoom in and zoom out the visualization.
7. Experimented with dragging and ‘viewBox’.



# Visualization 2: Minard’s Map
 
## Description:
The visualization is again achieved using ‘d3.js’ JavaScript library, CSS and HTML. Steps involved in building the visualization are:
1. Created the SVG element.
2. Started with building axis for longitude and latitude.
3. Implemented three groups for division 1, division 2 and division 3.
4. Arrival and retreat path are plotted using line and stroke, with stroke width representing the
number of survivors.
5. Cities data denoted using white dots and city names above it.
6. Interactive legends for divisions to view respective division’s arrival and retreat path.
7. Added temperature axis and plotted temperature data.
