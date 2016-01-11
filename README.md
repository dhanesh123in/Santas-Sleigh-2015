# Santas-Sleigh-2015

2optSwap-var2.ipynb:

Best submission, uses most of Kaggle scripts (sorting by Lat, Long and neighbor switches) with a custom 2-opt search

mtz_opt.ipynb:

The MTZ formulation for a standard TSP problem. Not very scalable even for standard TSP's.

Model02-tsp-opt.ipynb:

Includes a subtour elimination TSP (tsp_solve). The weight function is approximate, so doesn't really solve the Kaggle problem correctly. But just a brilliant technique to solve TSPs (works nicely for a 70 TSP problem)


myopt_tst3.ipynb:

A test script trying out my own formulation. Number of variables is order n^3. With small number of cities, around 10, these gave nice exact solutions but with 70 odd cities, PuLP took forever to generate the lp file for GLPK solver. A dual formulation may have been more scalable - did not get a chance to derive it.

