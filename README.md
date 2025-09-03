# 🧠 Particle Swarm Optimization (PSO) – Modeling & Optimization

## 📌 Description
This project demonstrates the use of **Particle Swarm Optimization (PSO)** on different optimization problems.  
All implementations are provided as **Jupyter Notebooks (.ipynb)** to allow direct execution and visualization.  

Implemented problems:
1. **Travelling Salesman Problem (TSP)**  
2. **Sum of Squares Function**  
3. **Neural Network Optimization (hidden neurons with PSO)**  

---

## 🛠️ Tools & Technologies
- Python 3.9+
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🚀 Implementations

### 1️⃣ PSO on TSP – `PSO_TSP.ipynb`
- Discrete PSO applied to the Travelling Salesman Problem.  
- Finds the best path with minimum travel cost.  

---

### 2️⃣ PSO on Sum of Squares – `PSO_Sum_Square.ipynb`
- Benchmark function: minimize `f(x) = Σ xi²`.  
- Classic PSO with inertia, cognitive & social components.  

---

### 3️⃣ PSO for Neural Networks – `PSO_NeuralNetwork.ipynb`
- Dataset: Wine (from sklearn).  
- Uses PSO to find the **optimal number of hidden neurons** in an MLP classifier.  
- Compares accuracy with and without PSO optimization.  

---

## 📊 Results
- **TSP** → Optimized paths with reduced travel cost.  
- **Sum of Squares** → Convergence near zero.  
- **Neural Network** → Improved accuracy with optimal hidden neurons.  

---

## 📚 References
- [Swarm Intelligence – Tutorials](http://www.swarmintelligence.org/tutorials.php)  
- [PSO for TSP Research Paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.258.7026&rep=rep1&type=pdf)  
