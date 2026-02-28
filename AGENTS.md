```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure the consistent, high-quality, and maintainable development of the AGENTS repository. Adherence to these principles will maximize productivity and minimize development overhead.

## 1. DRY (Don't Repeat Yourself)

- All code within the repository should be self-contained and reusable.
- Avoid duplicating logic or data structures.
- Refactor duplicate code into reusable components.
- Prioritize creating new features and updates over modifying existing code.

## 2. KISS (Keep It Simple, Stupid)

-  Strive for the simplest possible solution that effectively addresses the problem.
-  Avoid unnecessary complexity.
-  Prioritize readability and understandability.
-  Favor clear and concise code over obscure or convoluted logic.

## 3. SOLID Principles

- **Single Responsibility Principle:** Each class or module should have one primary responsibility.
- **Open/Closed Principle:** The system should be extensible without modification.  New functionality should be added through new classes/modules.
- **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
- **Interface Segregation Principle:** Client code should not be required to know the identity of methods it does not use.
- **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules. They should depend on abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

-  Do not implement features that are not currently required.
-  Avoid adding functionality that may become obsolete in the future.
-  Focus on delivering the minimum viable product (MVP) for each iteration.

## 5. Code Structure & Organization

- **File Names:** Use descriptive names that clearly indicate the purpose of the file.  Follow a consistent naming convention (e.g., `[ModuleName]_[Functionality].py`).
- **Comments:**  Provide clear, concise comments explaining *why* the code is written a certain way, not just *what* it does.  Avoid redundant comments.
- **Modularization:** Break down large functions and classes into smaller, manageable units.
- **Data Structures:** Choose appropriate data structures to optimize performance and maintainability.  Use standard libraries where possible.
- **Error Handling:**  Implement robust error handling with appropriate logging and informative error messages.  Avoid exposing internal implementation details in error messages.

## 6.  Code Quality & Testing

- **Maximum Code Length:**  Each file must have a maximum of 180 lines of code.
- **Code Reviews:** All changes must undergo a thorough code review by at least two team members.
- **Unit Tests:**  Implement comprehensive unit tests to verify the functionality of each component.  Focus on edge cases and boundary conditions.
- **Test Coverage:**  Aim for at least 80% test coverage.  Utilize existing test frameworks (e.g., pytest, unittest) to ensure adequate test coverage.
- **Maintainability:**  Code should be written in a way that makes it easy to understand and modify.
- **Documentation:**  Provide documentation for each function, class, and module, adhering to established documentation standards.
- **Static Analysis:** Utilize static analysis tools (e.g., pylint, flake8) to automatically identify potential issues.

## 7. Specific Requirements - AGENTS (Example - this will need adaptation)

-  **Model Design:**  Clearly define the data models for each agent type.
-  **API Definitions:** Document all APIs, including input/output formats, error handling, and usage examples.
-  **Data Storage:** Define the data storage strategy (database, file system, etc.).
-  **Communication Protocols:** Describe any communication protocols used between agents.
-  **Logging:** Implement a robust logging system for debugging and monitoring.

## 8.  General Practices

-   **Version Control:** Use Git for version control.  Follow established Git branching and merging practices.
-   **Git Commit Messages:** Write meaningful and descriptive commit messages.
-   **Documentation Updates:** Keep the documentation up-to-date with the codebase changes.
-   **Dependency Management:** Use a dependency management tool (e.g., pip, Poetry) to manage project dependencies.

## 9.  Frameworks and Libraries**

- Adhere to the established conventions and best practices for the chosen frameworks/libraries.
- Ensure proper integration and usage of these libraries.

These guidelines are designed to promote a standardized and high-quality development process.  Regularly review and update these guidelines as the project evolves.
```