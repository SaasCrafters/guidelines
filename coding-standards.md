# Coding Standards

This folder contains guidelines related to coding styles and standards that we follow in our organization. Adhering to these standards ensures consistent and maintainable code across all our projects.

1. Indentation and Formatting
  - Use spaces for indentation (4 spaces per level).
  - Use consistent casing for variables (camelCase), functions (camelCase), and classes (PascalCase).
  - Limit line length to 80 characters to enhance code readability.

2. Naming Conventions
  - Use meaningful and descriptive names for variables, functions, and classes.
  - Avoid single-letter variable names, except for loop iterators.

3. Comments
  - Use comments to explain complex logic, algorithms, or non-obvious code.
  - Keep comments up-to-date with code changes.
  - Avoid excessive commenting for self-explanatory code.

4. Code Organization
  - Break large functions into smaller, more manageable ones.
  - Group related functions together within classes or modules.
  - Organize imports alphabetically and separate them into sections (standard library, third-party, local imports).

5. Error Handling
  - Handle exceptions gracefully and provide helpful error messages.
  - Use specific exception types when raising exceptions.

6. Testing
   - Backend
       - TDD => `pytest`, `unittest`, `bug-bear`
   - Frontend
       - TDD => `jest`, `react-testing`, `playwright`.
  - Write unit tests for critical functions and classes.
  - Ensure test coverage for major features and functionalities.
  - Use descriptive test function names that reflect the tested behavior.

7. Version Control and Git Workflow
  - Use version control (Git) for all projects.
  - Create feature branches for new developments and bug fixes.
  - Regularly commit and push changes to the remote repository.
  - Create clear and descriptive commit messages following the standard commit guide.

8. Documentation
  - Include inline comments for complex code to explain its purpose and functionality.
  - Write clear and detailed docstrings for classes and functions.
  - Provide a README file with instructions on how to set up and run the project.

9. Code Reviews
  - Conduct code reviews for all significant changes before merging into the main branch.
  - Use code review feedback to improve code quality and adherence to standards.

10. Language-Specific Standards

  - Follow language-specific best practices and idioms for the programming language used in each project.
  Remember, these coding standards are crucial for maintaining a cohesive and collaborative codebase. By adhering to these guidelines, we ensure that our code is clean, efficient, and easy to maintain, ultimately contributing to the success of our projects.

