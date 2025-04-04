# Knowledge Representation and Reasoning: Homework Assignment 1

## Overview

This assignment focuses on Bayesian Networks and conditional independence. It consists of three problems that test your understanding of probabilistic graphical models.

## Problem Set

### Problem 1 (4 points)
Analysis of a student performance Bayesian network model where:
- Variables include: Intelligence (I), Hard Work (H), Test-Taking Ability (G), Understanding (U), and Exam Score (E)
- All variables are Boolean (true/false)

Tasks:
- Manually derive P(I=t|E=t) with algebraic steps
- Verify your answer using Junction Tree implementation
- Analyze conditional independence statements

### Problem 2 (3 points)
Medical diagnosis scenario with:
- Three independent diseases (D1, D2, D3)
- Four symptoms (S1, S2, S3, S4) with specific dependency relationships

Tasks:
- Draw the Bayesian network
- Calculate the number of independent parameters
- Compare with parameters needed without conditional independence
- Identify the Markov Blanket of S2

### Problem 3 (3 points)
Astronomy measurement scenario where:
- Two astronomers make star count measurements (M1, M2)
- Possibility of small errors in either direction
- Possibility of telescope focus issues (F1, F2) causing systematic undercounting

Tasks:
- Evaluate four given Bayesian network structures
- Identify which correctly represent the scenario
- Determine the most efficient network

## Submission Requirements

- Complete all problems
- Show all work, especially algebraic derivations
- For Problem 1(b), include your Junction Tree implementation results

## Prerequisites

- Understanding of Bayesian Networks
- Knowledge of conditional independence
- Familiarity with Junction Tree algorithm implementation from lab sessions

## Resources

- Use the Junction Tree implementation developed in lab sessions
- Reference course materials on Markov Blankets and conditional independence
