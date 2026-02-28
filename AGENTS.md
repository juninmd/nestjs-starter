```markdown
# AGENTS.md - AI Coding Agent Guidelines

These guidelines outline the specific principles and rules for development of AI coding agents within this repository. Adherence to these principles is mandatory for all development efforts.

## 1. DRY (Don't Repeat Yourself)

*   All code within a file should be a reusable component.
*   Implement generic logic and abstractions whenever possible to minimize duplication.
*   When a function or module is reused, provide clear documentation explaining its purpose and inputs/outputs.

## 2. KISS (Keep It Simple, Stupid)

*   Prioritize readability and maintainability.
*   Avoid overly complex logic.
*   Use straightforward constructs and avoid unnecessary abstraction.
*   Strive for minimal code complexity, making it easy to understand and modify.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module should have a single, well-defined purpose.
*   **Open/Closed Principle:** The system should be extensible through public interfaces, without modifying the internal structure.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Each interface should have only those methods required by the consuming code.
*   **Dependency Inversion Principle:** Dependencies should be hidden through abstraction.

## 4. YAGNI (You Aren't Gonna Need It)

*   Only implement functionality that is currently required.
*   Avoid premature optimization.
*   Focus on delivering working solutions and deferring non-essential features to future iterations.

## 5. Testing & Code Coverage

*   **All development must be productive.**  No modifications to the core codebase should be made without a prior, thoroughly tested implementation.
*   **Mocks ONLY for testing.**  All testing should focus on verifying the expected behavior of the agents, not the underlying implementation details.
*   **Unit Tests:**  All unit tests should pass with high confidence. Test coverage should be at least 80%.
*   Test cases should cover edge cases, boundary conditions, and potential failure scenarios.
*   Test suites should be organized logically and clearly labeled.
*   Focus on testing critical functionality and potential failure paths.

## 6. File Length & Structure

*   Each file should be no more than 180 lines of code.
*   File structure:  Modularize code into logical components with clear responsibilities.
*   Use descriptive filenames and comments.
*   Maintain consistent coding style and formatting (e.g., using a code formatter).
*   Consider using a dedicated directory structure.

## 7.  Specific Guidelines for Agent Components

*   **AgentData:**  A dedicated component to handle agent data, ensuring consistency and preventing data corruption.
*   **AgentLogic:**  A component for implementing core agent logic, designed for reusability.
*   **AgentInterface:** A flexible component for defining common interfaces for agent interactions.
*   **Configuration:** Separate configuration files for different environments/settings.
*   **Logging:**  Implement robust logging to track agent actions and errors.

## 8.  Code Style & Conventions

*   Use a consistent code style (e.g., PEP 8).
*   Employ meaningful variable and function names.
*   Document code clearly with docstrings.
*   Use consistent commenting practices.

## 9.  Repository & Collaboration

*   All code must be committed to the designated repository.
*   Use a version control system (e.g., Git) for tracking changes.
*   Utilize pull requests for code review and collaboration.
*   Follow established coding standards and best practices within the project.

## 10.  Documentation

*   Provide comprehensive documentation for each component.
*   Document APIs and data formats used.
*   Include examples of usage.

These guidelines are intended as a framework.  Further clarification and refinements may be required as the project evolves.  Any deviation from these guidelines will be subject to review and potential rejection.
```