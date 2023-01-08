# Max-Points-on-a-Line

Given an array of points where points[i] = [xi, yi] represents a point on the X-Y plane, return the maximum number of points that lie on the same straight line.

Example 1:

![plane1](https://user-images.githubusercontent.com/88260025/211197773-6b1a90c9-6463-457a-b9ba-83c5501345d4.jpg)

Input: points = [[1,1],[2,2],[3,3]]
Output: 3

Example 2:

![plane2](https://user-images.githubusercontent.com/88260025/211197778-75e1021d-b699-4381-a66f-61a686196207.jpg)

Input: points = [[1,1],[3,2],[5,3],[4,1],[2,3],[1,4]]
Output: 4
 

Constraints:

1 <= points.length <= 300
points[i].length == 2
-104 <= xi, yi <= 104
All the points are unique.
