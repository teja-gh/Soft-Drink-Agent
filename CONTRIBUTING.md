# Contributing to Soft Drink Agent

Thank you for your interest in contributing to the Soft Drink Agent project! This document provides guidelines and instructions for contributing.

## Code of Conduct

Please be respectful and constructive in all interactions with other contributors and maintainers.

## How to Contribute

### Reporting Bugs

If you find a bug, please create an issue with:
- A clear, descriptive title
- A detailed description of the issue
- Steps to reproduce the problem
- Expected behavior
- Actual behavior
- Screenshots (if applicable)

### Suggesting Enhancements

Feature requests are welcome! Please include:
- A clear description of the feature
- Why this enhancement would be useful
- Possible implementation approach (if you have ideas)

### Pull Requests

1. **Fork the repository** and create your feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes** following the coding standards:
   - Run `npm run prettier` to format code
   - Run `npm run lint` to check for issues
   - Write or update tests as needed

3. **Commit your changes** with clear, descriptive messages:
   ```bash
   git commit -m "Add feature: description of changes"
   ```

4. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

5. **Open a Pull Request** with:
   - A clear title describing the change
   - A detailed description of what was changed and why
   - Reference to any related issues (e.g., "Closes #123")

## Coding Standards

### Apex
- Follow Salesforce Apex naming conventions
- Use meaningful variable and method names
- Add comments for complex logic
- Write unit tests for new functionality

### Lightning Web Components (LWC)
- Follow ES6+ standards
- Use descriptive component names
- Keep components focused and reusable
- Include JSDoc comments for public methods

### General
- Keep methods and functions focused and concise
- Write self-documenting code
- Use consistent indentation (2 spaces)
- Avoid code duplication (DRY principle)

## Running Tests

Before submitting a PR, ensure all tests pass:

```bash
npm run test:unit
npm run test:unit:coverage
```

## Code Review Process

1. Your PR will be reviewed by maintainers
2. Feedback will be provided if changes are needed
3. Once approved, your PR will be merged
4. Your contribution will be included in the next release

## Questions?

Feel free to open an issue or discussion if you have questions about the project or contribution process.

Thank you for contributing! 🎉
