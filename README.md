# Plotting Prime Gaps
The script plots the gaps between primes in a heatmap. ```width``` and ```height``` of the plot can be defined by the user. The script then calculates the first ```width*height+1``` primes. In the next step, the gaps between the primes are calculated and stored in a 2D array with the specified width and height. The array is then visualized as a heat map.

![alt text](https://github.com/antonroesler/prime-gaps/blob/master/primeplot.png)

The darkest box at the top left is the gap between 2 and 3. Following are the dark gaps between 3 and 5 and between 5 and 7. The gap between 7 and 11 is the first slightly lighter gap. The brightest gap is the gap with distance 34 between 1327 and 1361

A plot with higher granularity is the following:

![alt text](https://github.com/antonroesler/prime-gaps/blob/master/primeplot-fine.png)
