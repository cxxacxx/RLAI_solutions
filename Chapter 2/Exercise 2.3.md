# Exercise 2.3

## Question:
In the comparison shown in Figure 2.2, which method will perform best in the long run in
terms of cumulative reward and cumulative probability of selecting the best action? How much better will it be?

## Answer:
In terms of cumulative probability of selecting the best action, ε=0.01 will select the best action 99.1% (0.99+0.01\*0.1) of the time versus ε=0.1, which is 91% (0.9+0.1\*0.1).

$\bar{q}_ s$ represents the average Q value of suboptimal values.

ε=0.01 will have an average reward of $0.01 * \bar{q}_ s + 0.99 * q_ {opt}$

ϵ=0.1 will have an average reward of $0.1 * \bar{q}_ s + 0.9 * q_ {opt}$