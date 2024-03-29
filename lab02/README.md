# 🔶 The objective of the exercise 🔶

<p> The exercise involved implementing the Graham and Jarvis algorithms for computing convex hulls. Then, it was necessary to test their performance on different datasets and measure their execution time. </p>
<p> The algorithms for computing convex hulls were the topic of my semester project on Geometric Algorithms course. 
   For more implemented convex-hull-search algorithms, visualizations and further information, you can explore <a href="https://github.com/YoC00lig/Convex-Hull">this repository</a>. </p>

# 🔶 Results for example dataset 🔶

<h3> 🔸 Graham </h3>
<p> The Graham algorithm, also known as the Graham scan, first finds the point with the lowest y-coordinate (or the leftmost point in case of a tie). It then sorts the remaining points based on their polar angle with respect to this point and constructs the convex hull using a stack.</p>
<img src="graham.gif">

<h3> 🔸 Jarvis </h3>
<p> The Jarvis algorithm, also known as the gift wrapping algorithm, is a simple approach for computing the convex hull. It starts with the leftmost point and iteratively selects the next point that forms the smallest angle with the current edge. </p>
<img src="jarvis.gif">
