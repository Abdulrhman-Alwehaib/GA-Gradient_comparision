# Gradient Descent (GD) VS Decaying Mutation Genetic Algorthim (DM-GA)

This project implements Perceptron, Gradient Descent (GD) and a modified Genetic Algorithm (which i devoloped and call it DM-GA) from scratch to train the Perceptron using GD and compared it to using DM-GA on a **non-convex** loss function regression proplem

GA-DM: I modified the standard Genetic Algorthim by adding a **dynamic Mutation** which decreases as generations improve which helped with faster convergence

## Key Features:
- **Decaying Mutation Genetic Algorithm:** which is a Genetic Algorthim but modified to have Decaying Mutation
- **Performance comparision:**: by running both algorthims 10 times and taking the average, DM-GA achived faster convergence than GD by **63.02** while achiving Lower Loss (DM-GA: 0.2487, GA: 0.3793)
- **Non-Convex loss function**: This expriment shows how affective DM-GA on a **non-convex** loss function compared to GD

The code implemented everything from scratch, using **torch tensors**, **math library** and **random library**
