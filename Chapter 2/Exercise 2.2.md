# Exercise 2.2

## Question:
_Bandit example_ Consider a k-armed bandit problem with k = 4 actions, denoted 1, 2, 3, and 4.
Consider applying to this problem a bandit algorithm using ε-greedy action selectioni,
sample average action-value estimates, and initial estimates of Q<sub>1</sub>(a) = 0, for all a. Suppose
the initial sequence of actions and rewards is A<sub>1</sub> = 1, R<sub>1</sub> = -1, A<sub>2</sub> = 2, R<sub>2</sub> = 1, A<sub>3</sub> = 2, R<sub>3</sub> = -2, A<sub>4</sub> = 2, R<sub>4</sub> = 2, A<sub>5</sub> = 3, R<sub>5</sub> = 0. On some of these time steps the ε case may have ocurred, causing an action to be selected at random. On which time steps did this definitely occur? On which time steps could this possibly have occurred.

## Answer:

To sum up, the cases where the ε case definitely occurred are steps 4 and 5. The rest of the cases could ε case possibly have occurred.

