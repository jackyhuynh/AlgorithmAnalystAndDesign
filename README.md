# Algorithm and Design

## Introduction

This repository covers essential concepts related to algorithms and software design fundamentals (SDF), focusing on:

- **Concepts and properties of algorithms**
- **The role of algorithms in problem-solving**
- **Key problem-solving strategies**
- **Separation of behavior and implementation**

### Algorithm Definition

An **algorithm** is:
- A well-defined procedure that follows a sequence of unambiguous instructions.
- Used for solving a specific computational problem.
- Designed to obtain the desired output from any valid input.
- Guaranteed to complete in a finite amount of time.

### Verifying Algorithm Correctness

To ensure that an algorithm functions correctly, we can apply the following methods:

1. **Testing**:
   - Running the algorithm on various test cases to validate outputs.
   
2. **Correctness Proof**:
   - Formal proof to establish that the algorithm works as intended for all inputs.

3. **Confidence in Algorithms**:
   - Build confidence through rigorous testing and correctness proofs.

4. **Recursive Algorithms**:
   - Correctness is often demonstrated using **induction**.

5. **Iterative Algorithms**:
   - Prove correctness through **loop invariants** and **induction**.

---

## Problem-Solving Strategies

### Divide and Conquer

This strategy involves:
1. **Breaking the problem into smaller sub-problems**.
2. **Solving each sub-problem independently**.
3. **Combining the solutions** to solve the original problem.

---

## Convex Hull Problem

A **Convex Hull** is the smallest polygon that encloses all given points. Common algorithms used to solve the convex hull problem include:

- **Graham Scan** – Time Complexity: **O(n log n)**
- **Jarvis March** – Time Complexity: **O(nh)**

---

## Merge Sort

Merge Sort is a classic divide-and-conquer algorithm with the following properties:

- **Time Complexity**: **T(n) = Θ(n log n)**
- It outperforms simpler algorithms like **insertion sort** (which has a time complexity of **Θ(n²)**).

---

## Conclusion

This repository provides a foundation in algorithms and design, offering insights into algorithm efficiency, problem-solving techniques, and correctness proofs. Stay tuned for more advanced topics in future updates.