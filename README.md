# Candy Factory Exercise

This exercise is designed to practice and understand the design pattern through the development of a candy factory simulation. You will work with various candy-related classes and complete the implementation of a `CandyFactory` class. The main challenge is to dynamically create specific candy objects based on input, demonstrating the Factory Method's ability to handle object creation without specifying the exact class of the object that will be created. This exercise is adopted from [design-patterns-examples](https://github.com/ZapDos7/design-patterns-examples) on GitHub.

## Instructions

### 1. Study Candy-Related Classes

Begin by familiarizing yourself with the provided candy-related classes. Understand their hierarchies, properties, and methods. These classes represent different types of candies that the factory can produce.

### 2. Complete the `CandyFactory` Class

Implement the `CandyFactory` class, ensuring it can dynamically decide which type of candy to create at runtime based on provided criteria. This part of the exercise simulates a scenario where the `candyStore` (client) does not know in advance which exact candy objects (products) need to be created.

#### Requirements:

- The `CandyFactory` should have a method that accepts criteria (e.g., candy type) and returns a new instance of the corresponding candy class.
- Ensure that adding new candy types in the future adheres to the Open/Closed Principle, meaning the factory can support new types without modifying its existing code structure.

## Objectives

- Practice the principles of object-oriented design, particularly in relation to object creation.
- Enhance your ability to extend software functionalities while keeping it open for extension but closed for modifications.

