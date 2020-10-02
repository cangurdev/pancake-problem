# Pancake Problem

## CSE3111/CSE3213 Artificial Intelligence Homework #1

<h3 align=center> Fall 2019</h3>

### 1. Objective

The purpose of this homework is to teach you how to apply uninformed and informed search algorithms while solving a real problem and how to evaluate the performance of these algorithms.

### 2. Specification

In this homework, you will formulate and develop a solution to the below problem by applying uninformed and informed search algorithms discussed in class: _Breadth First Search, Depth First Search, Depth Limited Search, Iterative Deepening Search, Uniform Cost Search, Greedy Best First Search, and A\* Search._

### Pancake sorting problem

This famous problem is usually stated as follows: Pancake sorting is sorting a disordered stack of pancakes in order of size when a spatula can be inserted at any point in the stack and used to flip all pancakes above it.

## Task 1 – Implementation

In this homework, you will use source codes provided by AIMA textbook. You are free to use Java or Python as your programming language. After importing the AIMA libraries into your workspace, your job is to formulate and develop a solution to the pancake problem.

1. Your program should have a simple console-based menu which takes the number of pancakes(𝑁) from the user. You should also provide two options to the user for the initial ordering of 𝑁 pancakes:

   - The program randomly generates a permutation of 𝑁 pancakes as the initial ordering.

   - The initial ordering of 𝑁 pancakes is determined by the user.

2. You are also provided the base Java file to be used for testing. Your job is to implement the empty methods in this demo file (PancakeProblemDemo). (If you are using Python, write a similar script)

3. You have to use the classes and methods for searching provided in AIMA. Do not implement your own search algorithms.

4. You can get help from NQueensDemo.java and EightPuzzleDemo.java applications located under the package aima.gui.demo.search.(Python users, see test_search.pyfile under tests directory.)

5. At least, you will need to create your own classes for the following:

   - PancakeState(representing the state)
   - PancakeActionwhich extends aima.core.agent.impl.DynamicAction(representing possible actions)
   - PancakeProblem which implements aima.core.search.framework.problem.Probleminterface (representing the problem formulation for the pancake sorting problem).
