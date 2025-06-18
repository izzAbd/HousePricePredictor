# HousePricePredictor
House price prediction system using design patterns
AI-Powered Factory Pattern Project

This project is a practical implementation of software design principles in Python, showcasing how to structure a scalable and maintainable codebase using classic object-oriented design patterns.
Overview:
The goal of the project is to simulate a modular AI pipeline, where different components (strategies, templates, factories) can be dynamically switched or extended without modifying core logic.

Key patterns used:
Factory Pattern
Strategy Pattern

Template Method Pattern
These patterns ensure flexibility, testability, and clean separation of concerns.

Design Patterns in Action
1.Factory Pattern
Used to create different types of model handlers based on input or config.
Helps decouple object creation from logic.


2. Strategy Pattern
Applied to implement different data processing or model selection strategies.
Easily extendable with new strategies without touching core logic.

3. Template Method
Used to define a base pipeline structure (e.g., train → validate → evaluate) where specific steps can be customized in subclasses.

Key Features

Plug-and-play architecture for AI model workflows

Scalable design for adding new models or strategies

Pattern-based structure for maintainability

This project emphasizes clean code architecture over model performance. The goal is to demonstrate the power of design patterns in data/ML applications.
