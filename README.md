# Gradient Descent (GA) VS Decaying Mutation Genetic Algorthim (DM-GA)

This project implemented Perceptron, Gradient Descent and a modified Genetic Algorthim (i called it DM-GA) from scratch to train the Perceptron using GD and compared it to using DM-GA on a **non-convex** loss function regression proplem

## Key Features:
- **Decaying Mutation Genetic Algorthim:** which is a Genetic Algorthim but modified to have Decaying Mutation
- **Performance comparision:**: by running both algorthims 10 times and taking the average, DM-GA achived faster convergence than GD by **63.02** while achiving Lower Loss (DM-GA: 0.248780, GA: 0.379397)
  - **Non-Convex loss function**: This expriment shows how affective DM-GA on a **non-convex** loss function compared to GD

**The code implemented everything from scratch, using **torch tensors**,**math library** and **random** library
