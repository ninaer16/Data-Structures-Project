# Data-Structures-Project
Knapsack Algorithm for Diet Planning

For Data Structures & Algorithm II course, my groupmates and I are assigned to create a program using any algortihm that we learned and add some modifications to make it an "original" idea. 

The Knapsack Algorithm is used by our group to plan diets. The given pseudocode utilizes the knapsack algorithm to optimize diet planning by selecting food items that maximize nutritional value while adhering to constraints on calories and budget. The algorithm dynamically considers each food item and checks whether including it would result in a higher nutritional value without exceeding the specified calorie and budget limits. By comparing the potential nutritional benefit of including or excluding each item, the algorithm constructs an optimal set of food items that meet the dietary constraints. This approach is effective for balancing nutritional intake against caloric and financial constraints, providing a practical solution for diet planning.

How it works: 
By comparing the potential nutritional value of including or excluding each item while iterating through possible calorie and budget limits, the algorithm ensures that every decision made contributes to achieving the optimal solution. 
Why it’s good:
 This meticulous decision making process enhances the algorithm’s capability to maximize nutritional value, making it an effective tool for dietary planning where both calorie intake and budget are critical factors.

Original Knapsack Problem:
- Has single constraint (weight).
- Each item has a value and weight. (2D list)
- The goal is to maximize the total value of items included in the knapsack without exceeding its weight capacity.

Modifications made:
- Two constraints which are max calories and budget.
- Each item has calories, cost, and nutrition value.  (3D list)
- The goal is to not only stay within a maximum calorie limit and budget, but , it is also to maximize the nutritional value of the items selected.

The advantages or good point of the adjusted algorithm compared to original knapsack algorithm :
- It is more versatile and powerful optimization tool, capable of  handle multiple constraints simultaneously.  
- The ability to handle multiple problems in real- life problems where single constraint is insufficient most of the time.
- This adaptability allows it to be applied in various fields, providing more comprehensive solutions where multiple factors need to be balanced
