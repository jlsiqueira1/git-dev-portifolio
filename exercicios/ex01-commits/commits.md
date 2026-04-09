# Semantic Commits Documentation

## What are Semantic Commits?
Semantic commits are a convention for writing commit messages that convey meaning. This practice helps team members understand the purpose, impacts, and scope of changes made in a codebase.

## Why Use Semantic Commits?
- **Clarity**: Provides clear information about what changes were made and why.
- **Tools Compatibility**: Works well with tools for generating change logs, automating releases, or verifying code quality.
- **Collaboration**: Facilitates collaboration among team members by establishing a common language.

## Commit Message Format
The format for a semantic commit message consists of three parts:

1. **Type**: Indicates the type of change (e.g., `feat` for new features, `fix` for bug fixes).
2. **Scope**: Optional section that provides context about the change (e.g., `UI`, `API`, etc.).
3. **Subject**: A brief description of the change in the imperative mood. For example, `feat(UI): add new button component`.

## Types of Commits
- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Changes that do not affect the meaning of the code (white-space, formatting, etc.)
- `refactor`: A code change that neither fixes a bug nor adds a feature
- `test`: Adding missing tests or correcting existing tests
- `chore`: Changes to the build process or auxiliary tools and libraries such as documentation generation.

## Conclusion
By adopting semantic commits, teams can ensure that their commit history is meaningful and easier to understand, which aids in maintaining and scaling the project effectively.