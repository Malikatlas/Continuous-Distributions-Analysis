# Continuous Probability Distributions – Analytical Practice

This project covers advanced problems involving continuous probability distributions, including:
- **Uniform Distribution**
- **Exponential Distribution**
- **Gamma Distribution**

Each question explores theoretical concepts, symbolic formulas, and probability evaluations for real-world scenarios in machine learning and server operations.

---

### 📌 Problem Breakdown

#### ✅ Q1: Uniform Distribution (Model Processing Time)
- Scenario: Processing time \( X \sim \text{Uniform}(5, 15) \)
- Tasks:
  - Define PDF of \( X \)
  - Calculate \( P(7 \leq X \leq 12) \)
  - Compute \( \mathbb{E}[X] \) and \( \text{Var}(X) \)
  - Probability that **both** independent calls exceed 10s

#### ✅ Q2: Exponential Distribution (AI Server Request Interval)
- Scenario: Time between requests \( T \sim \text{Exponential}(\lambda = \frac{1}{6}) \)
- Tasks:
  - Define PDF
  - Find \( P(T > 10) \)
  - Compute median of \( T \)
  - Calculate \( P(3 \leq T \leq 8) \)

#### ✅ Q3: Gamma Distribution (Waiting Time for Third Event)
- Scenario: Waiting time \( W \sim \text{Gamma}(k=3, \lambda=0.5) \)
- Tasks:
  - Write the Gamma PDF
  - Compute \( \mathbb{E}[W] \) and \( \text{Var}(W) \)
  - Calculate \( P(W \leq 5) \) using CDF/incomplete Gamma
  - Conceptual difference between Gamma and Exponential distributions

---

### 📊 Concepts Explained

| Distribution | Application                        | Key Parameters     |
|--------------|-------------------------------------|--------------------|
| Uniform      | Equal likelihood between bounds     | \( a, b \)         |
| Exponential  | Time between Poisson events         | \( \lambda \)      |
| Gamma        | Time until k-th Poisson event       | \( k, \lambda \)   |

---

### 📁 Files Included
- `Question.pdf` – Assignment description with all problem statements
- `Solution.pdf` – Detailed hand-written/typed solution with step-by-step derivations

---

### 🧠 When to Use Each Distribution

- **Uniform**: Constant probability over an interval (e.g., random delays)
- **Exponential**: Time between consecutive random events (e.g., server requests)
- **Gamma**: Generalized wait time for multiple events (e.g., third call arrival)

---

### 📬 Contact

For corrections, suggestions, or collaborative improvement, feel free to open an issue or pull request.
