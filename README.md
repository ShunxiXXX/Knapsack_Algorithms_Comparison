# Knapsack_Algorithms_Comparison
This project compares the running time of three knapsack problem algorithms and visualizes them.
## Introduction
In this project, we use three different backtracking algorithms to solve the 01-knapsack problem, compare the running time of the three algorithms and visualize them.
### Introduction of the algoithms
The three algorithms are introduced as follows:
#### I. General Backtracking
The general algorithm explores all possible subsets of items and calculate the total value and weight to get the optimal solution. Obviously, this algorithm has high time complexity.
#### II. Bounding
In this algorithm we use the solution of fractional knapsack problems which based on a greedy approach as the boundding function to complete pruning in the backtracking process on the decision tree. Compared with the general algorithm, this strategy can greatly reduce the running time.
#### III. Branch and Bound
Instead of calculating the total value for every combination of items in Bounding, we use a bound to estimate the maximum value we can achieve with the remaining capacity. This strategy can solve the 01-knapsack problem with less running time in some cases.
### Introduction of the testing and visualization
We wrote a function to generate a large number of data groups that meet the 01-knapsack problem, input these data groups into each algorithm to get the solution, and use another function to count the running time of each algorithm and draw it as a line graph like the following:
![](""D:\Github\Knapsack_Algorithms_Comparison\pic.png"")
## File information
You can find that we divide the Python code of each algorithm block into different files.
knapsack_report.ipynb is a Jupyter Notebook file, it describes the whole process of implementing each algorithm and visualizing its runtime, and includes all the python code and detailed interpretation for the codes. At the same time, you can modify and run the code in this file to complete the visualization process.
Here is also a PDF file generated from the jupyter notebook file which can be used in study.
**You are wlcome to use them!😉**