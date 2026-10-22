# AIML Experiment 10: Decision Tree Classifier from Scratch

This repository contains a clean, simplified implementation of a **Decision Tree Classifier** built entirely from scratch using Python, Pandas, and NumPy. 

## 📌 Project Overview
A Decision Tree mimics human decision-making by creating a flowchart of "If-Else" rules to segment data. This implementation constructs a maximum depth-2 tree (a root node and its primary branches) to classify the famous **Iris Flower Dataset** based on petal and sepal measurements.

## 🛠️ Key Concepts Implemented
- **Gini Impurity**: Programmed the mathematical calculation used to measure data mixture/impurity at any given split.
- **Data Splitting**: Developed helper functions to dynamically divide datasets based on feature thresholds.
- **Root Node Selection**: Scans all 4 features and values to select the partition yielding the highest information gain.
- **Tree Visualization**: Displays the final structure of the tree with details of the resulting branch distributions.

## 📊 Results Summary
- **Selected Root Feature**: `petal.length` (Threshold: `3.0`)
- **Left Branch**: 50 flowers (*Iris setosa* completely separated)
- **Right Branch**: 100 flowers (*Iris versicolor* and *Iris virginica*)
- **Inference**: `petal.length` is identified as the most crucial feature for classification since splitting on it yields the highest reduction in overall impurity.
