# Introduction to Test-Driven Design (TDD)

Test-Driven Design (often called Test-Driven Development) is a software development approach where you write tests **before** writing the implementation code.

The core TDD cycle is:

1. **Red**: Write a test for a behavior you want, and watch it fail.
2. **Green**: Write the smallest amount of code needed to make the test pass.
3. **Refactor**: Improve the code while keeping all tests passing.

This process helps you define expected behavior up front and build software in small, verifiable steps.

## Why TDD Matters

TDD offers several practical benefits for students and professional developers:

- **Clear requirements**: Writing tests first forces you to think about what the code should do.
- **Fewer bugs**: Problems are caught early, before they spread into larger systems.
- **Safer refactoring**: Tests act as a safety net when improving or reorganizing code.
- **Better code design**: Small testable units often lead to cleaner, more modular code.
- **Living documentation**: Tests show exactly how code is expected to behave.
- **More confidence**: Passing tests make it easier to ship changes with less fear.

## Your Exercises

Complete the notebooks in this order:

1. `unittest_tdd_lesson.ipynb` (guided example)
2. `calculator_tdd_exercise.ipynb` (independent practice)

After you finish `unittest_tdd_lesson.ipynb`, open `calculator_tdd_exercise.ipynb` and complete the full TDD cycle on your own.

As you work through both notebooks, focus on:

1. Defining behavior first with tests.
2. Observing failing tests as part of the process.
3. Implementing only enough code to pass tests.
4. Re-running tests after each change.

By the end, you will have practiced the full TDD workflow using Python’s built-in `unittest` framework across both a guided example and an independent calculator exercise.
