# **Subject: Algorithm Analysis (CS-605)**

## **Week 1**

### **1. Introduction to Algorithms**

- **What is an Algorithm?**  
  An **algorithm** is a **finite sequence of well-defined instructions** used to solve a specific problem or perform a computation.  
  Each step must be clear, executable, and lead to a solution within a finite amount of time.

- **Why Study Algorithms?**  
  Studying algorithms helps to:

  - Improve **efficiency** of programs.
  - Compare different solutions to a problem.
  - Understand **time and space complexity**.
  - Develop logical thinking and problem-solving skills.

- **Algorithm Definition (Formal)**  
  An algorithm is a step-by-step procedure for solving a problem in a **finite number of steps**, transforming **input** into **output**.

---

### **2. Units & Use**

- **Time Complexity:**  
  Measures the amount of **time an algorithm takes to execute** as a function of input size `n`.

- **Space Complexity:**  
  Measures the **memory used** by an algorithm to execute completely.

- **Common Applications:**
  - **Sorting Algorithms** (e.g., Bubble Sort, Merge Sort, Quick Sort).
  - **Searching Algorithms** (e.g., Linear Search, Binary Search).

---

### **3. Algorithm Types**

1. **Brute Force Algorithms** – Try all possible solutions (e.g., Linear Search).
2. **Divide and Conquer** – Break problem into smaller parts (e.g., Merge Sort).
3. **Greedy Algorithms** – Make the best choice at each step (e.g., Dijkstra’s Algorithm).
4. **Dynamic Programming** – Store intermediate results to avoid recomputation (e.g., Fibonacci using memoization).
5. **Backtracking** – Systematically explore all possibilities (e.g., N-Queens Problem).
6. **Randomized Algorithms** – Use random inputs for decisions (e.g., QuickSort with random pivot).

---

## **Week 2**

### **1. Asymptotic Analysis**

Used to describe **growth rate of algorithm’s running time** as input size `n` increases.

- **Big O (O)** → _Worst Case_  
  Represents the upper bound — maximum time an algorithm can take.  
  Example: `O(n^2)` for Bubble Sort.

- **Omega (Ω)** → _Best Case_  
  Represents the lower bound — minimum time an algorithm can take.  
  Example: `Ω(n)` for Linear Search (when element is first).

- **Theta (Θ)** → _Average Case_  
  Represents both upper and lower bounds — typical performance.  
  Example: `Θ(n log n)` for Merge Sort.

---

### **2. Notations and Calculations**

- **Running Time Expression Example:**  
  `T(n) = 4n^2 + 2n + 5`  
  Here, as `n` grows large, lower-order terms and constants are ignored.  
  ⇒ `T(n) = O(n^2)`

- **What is n₀ (n-not)?**  
  It is the **minimum input size** after which the asymptotic relationship holds true.  
  For all `n ≥ n₀`, `f(n) ≤ c·g(n)` (for Big O).

---

### **3. Growth of Functions**

| Type        | Function Example | Growth Rate | Description               |
| ----------- | ---------------- | ----------- | ------------------------- |
| Constant    | f(n) = 1         | O(1)        | Independent of input      |
| Linear      | f(n) = n         | O(n)        | Grows directly with input |
| Quadratic   | f(n) = n^2       | O(n^2)      | Common in nested loops    |
| Cubic       | f(n) = n^3       | O(n^3)      | Triple-nested loops       |
| Exponential | f(n) = 2^n       | O(2^n)      | Very fast growth          |
| Factorial   | f(n) = n!        | O(n!)       | Extremely fast growth     |

---

### **4. Finding n₀ and c (Example Problems)**

1. **Example 1:**  
   `f(n) = 2n^2 + n` belongs to `O(n^2)`  
   ⇒ For `n ≥ 1`, `f(n) ≤ 3n^2`  
   Here, `c = 3`, `n₀ = 1`.

2. **Example 2:**  
   `f(n) = n^2 + n^3` belongs to `O(n^3)`  
   ⇒ For `n ≥ 1`, `f(n) ≤ 2n^3`  
   Here, `c = 2`, `n₀ = 1`.

---

## 🧠 **Exam Tips**

- Always write **definition, example, and diagram** if applicable.
- When analyzing algorithms, remember:
  1. Focus on **dominant term** (highest power of n).
  2. Ignore constants and smaller terms.
  3. Justify **why** you drop certain terms.

## **Week 3**

- Class Miss

## **Week 4**

<!--
. **Topic**
   - SubTopics
   - SubTopics
   - SubTopics
 -->
