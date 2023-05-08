Download Link: https://assignmentchef.com/product/solved-softcomputing-assignment-10-aco-based-optimization-system-for-tsps
<br>
<h1>ACO Based Optimization System for TSPs</h1>

Use programming tools to development an ACO optimization system for the traveling salesman problem. Particularly, you are asked to implement ACS.

Conduct necessary system requirement analysis before implementing your system: to design your data structured and user interfaces for solving the TSP. You are given a library (.dll) and a set of TSP benchmarks. The lab class will instruct you how to use the library to take advantages of accessing and displaying a TSP benchmark. Your system should have basic yet friendly user interfaces for benchmark selections, ACO parameter settings, and stopping condition settings, etc.

You may follow the assignment structure of the GA solver to implement your ACO system. For example, you can design a GenericACO solver and an ACS system to derive it.

In your project video demo, run the benchmark taiwan50 and att48.

<strong>Travelling Salesman Problems: </strong>

A travelling salesman need to visit <em>n</em> cities and exactly once for each. The planar Cartesian coordinates of the cities are given and the Euclidean distances between cities can be computed accordingly. A TSP is therefore, to find a sequence of city visiting that has the shortest length (including the distance from the lastly routed city back to the first one).

<em>n </em>: number of cities,

(<em>x<sub>i </sub></em>, <em>y</em><em><sub>i </sub></em>): Cartesian coordinates of city<em>i </em>; <em>i </em>=0,1,L,<em>n</em>−1 <em>d<sub>i</sub></em><sub>, <em>j </em></sub>: distance from city<em>i </em>to city <em>j </em>;

<em>d</em><em>i</em>, <em>j </em>= (<em>x</em><em>i </em>−<em>x</em><em>j </em>)2 +(<em>y</em><em>i </em>−<em>y</em><em>j </em>)2

<em>n</em>−2

min <em>f </em>(<strong>z</strong>)=<em>d</em><em>z</em><em>n</em>−1,<em>z</em>0 +<em>d</em><em>z</em><em>i </em>,<em>z</em><em>i</em>+1 , where

<em>i</em>=0

<h1>z=<em>z</em><sub>0</sub>,<em>z</em><sub>1</sub>,L,<em>z</em><em><sub>n</sub></em><sub>−</sub><sub>1</sub>,<em>z</em><em><sub>k </sub></em>0,1,L,<em>n</em>−1,<em>z</em><em><sub>k </sub></em> <em>z</em><em><sub>k</sub></em><sub></sub></h1>




The benchmarks for TSP are in extended file name “tsp”. Sample file:




The optimal solutions to TSP benchmarks are in extended file name “opt.tour”. Note that the node IDs start from 1 to <em>n</em>; you must convert them to 0~<em>n</em>-1. Sample file:




Wiki: <a href="https://en.wikipedia.org/wiki/Travelling_salesman_problem">http://en.wikipedia.org/wiki/Travelling_salesman_problem</a>  TSPLIB: <a href="http://comopt.ifi.uni-heidelberg.de/software/TSPLIB95/">http://comopt.ifi.uni</a><a href="http://comopt.ifi.uni-heidelberg.de/software/TSPLIB95/">–</a><a href="http://comopt.ifi.uni-heidelberg.de/software/TSPLIB95/">heidelberg.de/software/TSPLIB95/</a>




Sample class