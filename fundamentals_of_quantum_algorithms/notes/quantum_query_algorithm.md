# Quantum Query Algorithms
[Qiskit - fundamentals of quantum algorithms](https://quantum.cloud.ibm.com/learning/en/courses/fundamentals-of-quantum-algorithms/quantum-query-algorithms/introduction)

## Introduction
- standard abstraction of computation:
  - input -> computation -> output
  - Turing machines
  - Boolean circuits 
- input is a string of bits
- **time complexity**: measure speed by counting every single step the CPU takes (adding numbers, moving memory, etc.). 
- Standard Model: Measures total work.
- Query Model: Measures how many times the algorithm have to look at the input.
  - use superposition to query the black box for all possible inputs at the same time.
  - **Grover's Search Algorithm**: Finding a specific item in an unsorted database of N items takes N queries classically. A quantum computer does it in $\sqrt{N}$ queries.
  - **Deutsch-Jozsa Algorithm**: Finding a specific property of a function takes multiple queries classically, but exactly 1 query quantumly.

## The query model of computation
- also known as **Black-Box** or **Oracle model**
- input is a function, which then be accessed by making queries 
  - input/oracle/black-box -- queries --> computation --> output
  - makes a query = evaluates the function f for value x and string f(x) provided
  - efficiency of query algorithms = number of queries to the input 
- **Query**: asking the input for information 
- Query model: a simplified model where we study how many times an algorithm needs to ask for information. 

## Deutsch's algorithm

## The Deutsch-Jozsa algorithm

## Simon's algorithm