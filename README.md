# AverageDistances
This is a technical query utilising self joins. I was to find the average distances between two points given they are duplicates with different distances between each point.
[Img1.pdf](https://github.com/user-attachments/files/19852448/Img1.pdf)

STEPS
1. Find the sum of the distances and group by the sources
2. Use the window function rownumber to order it so we can properly self join
3. Create a CTE using the query I created
4. Query the CTE by a self-join
   ![Screenshot 2025-04-22 162658](https://github.com/user-attachments/assets/30b2e233-f7bf-4e9a-9a9a-a8f1a32dabfe)

