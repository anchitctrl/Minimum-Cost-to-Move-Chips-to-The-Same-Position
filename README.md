# Minimum-Cost-to-Move-Chips-to-The-Same-Position

We have n chips, where the position of the ith chip is position[i].

We need to move all the chips to the same position. In one step, we can change the position of the ith chip from position[i] to:

position[i] + 2 or position[i] - 2 with cost = 0.
position[i] + 1 or position[i] - 1 with cost = 1.
Return the minimum cost needed to move all the chips to the same position.

![image](https://user-images.githubusercontent.com/70264806/120930649-dd854b00-c70b-11eb-9776-9b5539df4fe4.png)

Input: position = [1,2,3]

Output: 1

Explanation: First step: Move the chip at position 3 to position 1 with cost = 0.
Second step: Move the chip at position 2 to position 1 with cost = 1.
Total cost is 1.
