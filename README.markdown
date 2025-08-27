# Genetic Algorithm for Training Neural Network Weights

This project implements a **Genetic Algorithm (GA)** to optimize the synaptic weights of a feedforward neural network with a **3-2-1 architecture** (3 input neurons, 2 hidden neurons, 1 output neuron) using **ReLU activation functions**. The GA optimizes the weights to minimize error on a given input-output pair, with visualizations to track fitness progression over generations.

![Main Input Window](screenshots/neural_network.png)

---

## 🧩 Features

- **Genetic Algorithm Operations**:
  - Random population initialization
  - Fitness evaluation based on error minimization
  - Roulette wheel selection for parent selection
  - One-point crossover for recombination
  - Mutation to introduce diversity
  - Elitism to preserve the best solutions
- **Visualization**: best fitness progression over generations
- Fully implemented in Python, optimized for **Google Colab** and **Jupyter Notebook**

---

## ▶️ Usage

1. Open `GA_Neural_Network.ipynb` in **Google Colab** or **Jupyter Notebook**.
2. Configure **GA parameters** in the notebook:
   - Population size (e.g., 100)
   - Mutation rate (e.g., 0.01)
   - Crossover rate (e.g., 0.8)
   - Number of generations (e.g., 1000)
3. Run all cells to train the neural network using the GA.
4. **Outputs**:
   - The **best chromosome** (optimal weights) found
   - A **fitness progress plot** showing the best fitness over generations

---

## 📊 Visualization

Best Fitness Plot: Displays the fitness of the best chromosome across generations.
   ![Main Input Window](screenshots/fitness_plot.png)

---

## ⚡ Future Improvements

- Support for **multiple hidden layers** to handle more complex problems
- Inclusion of **bias neurons** in input and hidden layers for increased flexibility
- Training on a **bigger dataset** 
- Implementation of **parallel computation** to accelerate GA evaluation
- Addition of **alternative selection methods** (e.g., tournament selection) for improved diversity
- Integration of **hyperparameter tuning** for mutation and crossover rates

---

## 📌 Author

👩‍💻 **Eya Zaoui**\
AI & Software Engineer | Passionate about Machine Learning, Expert Systems, and Optimization Algorithms\
📧 Contact: zaouieya2@gmail.com