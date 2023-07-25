# SaasCrafter's Commit Guide
Commit Message Format
Each commit message should follow the format:
```
<type>: <description>

[optional body]

[optional footer(s)]
```

## Type
The type indicates the category of the commit. Choose one from the following list:

- feat: A new feature or enhancement.
- fix: A bug fix.
- docs: Documentation-related changes.
- style: Code style/formatting changes (no production code changes).
- refactor: Code refactoring (neither adding features nor fixing bugs).
- test: Adding or updating tests.
- chore: Routine tasks, build-related changes, or other changes that don't fit into the above categories.

## Description
The description is a brief summary of the changes made in the commit. It should be clear and descriptive, written in the present tense (imperative mood).

## Body (Optional)
The body of the commit message provides more detailed information about the changes. It should be used when the description alone is not sufficient to explain the commit's purpose. Use bullet points or paragraphs as needed.

## Footer (Optional)
The footer is used to reference related issues or pull requests, if applicable. You can use phrases like "Closes #123" or "Fixes #456" to automatically close issues or link pull requests when the commit is merged.

## Examples
Here are some example commit messages following this format:

```
feat: Add user authentication functionality

Adds user registration and login features to the application.

Closes #123
```
```
fix: Fix null pointer exception in data parsing

The 'data' variable could be null when no response is received from the server.
This fix ensures proper handling of null data.

Fixes #456
```

```
docs: Update README with API documentation

Adds API usage examples and clarifies the installation instructions.
```  
## Guidelines
Make commits focused and granular, addressing only one issue per commit.
Use the imperative mood in the description (e.g., "Fix bug" instead of "Fixed bug").
Keep the description concise and to the point.
Use the body to provide additional context, if needed.
Use the footer to reference issues or pull requests when relevant.
Following this standard commit guide helps keep the commit history clean, searchable, and easy to understand. It encourages good collaboration and efficient code review processes within the organization.
