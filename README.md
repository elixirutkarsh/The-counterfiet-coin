# The-counterfiet-coin
You are given a set of 12 coins, out of which one is counterfeit. All the genuine coins weigh the same, but the counterfeit coin is either lighter or heavier than the rest. You also have a balance scale.

Your task is to determine which coin is counterfeit and whether it is lighter or heavier in just three weighings using the balance scale.

Can you find the counterfeit coin with only three weighings? If so, explain the steps you would take to identify it.

Solution:
To solve this puzzle, we can use a technique called "Ternary Search."

Step 1:
Divide the 12 coins into three groups: A, B, and C, with four coins each.

Step 2:
Weigh group A against group B using the balance scale:
a) If they balance, the counterfeit coin is in group C.
b) If one side is heavier, the counterfeit coin is in the heavier group.
c) If one side is lighter, the counterfeit coin is in the lighter group.

Step 3:
Take the three coins from the relevant group identified in Step 2 (heavier or lighter). Divide them into three individual coins and weigh any two of them:
a) If they balance, the third coin is the counterfeit coin.
b) If one side is heavier, that coin is the counterfeit and its weight (heavier).
c) If one side is lighter, that coin is the counterfeit and its weight (lighter).

With these three weighings, you can identify the counterfeit coin and whether it is heavier or lighter than the genuine coins.
