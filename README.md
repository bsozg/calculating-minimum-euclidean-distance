## Calculating Minimum Euclidean Distance


Euclidean distance is the "ordinary" straight line distance between two points in Euclidean space. This formula finds the distance between two points in the plane or in three-dimensional space.


![image](https://github.com/user-attachments/assets/de0ef40b-53ee-4de0-9094-ef7dd2c1047e)

Explanations:

* Points: Four points are defined in the points list in 2D space. These points are represented by tuples in the form of (x, y).
* euclideanDistance Function: To calculate the Euclidean distance between two points, the formula (x₂ - x₁)² + (y₂ - y₁)² is used and the square root of the result is taken.
* Calculating Distances: The distance between each pair of points is calculated with a nested for loop. These distances are collected in the distances list.
* Finding the Minimum Distance: The smallest distance in the distances list is found with the min() function and printed.

Output:

When the program is run, the Euclidean distances for each pair of points defined in the points list will be calculated and the minimum distance will be printed on the screen.
