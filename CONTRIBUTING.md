# Contributing to LinkedIn Portfolio Generator

Thank you for considering contributing to the LinkedIn Portfolio Generator! This document provides guidelines and instructions for contributing to the project.

## Table of Contents
- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Development Setup](#development-setup)
- [Pull Request Process](#pull-request-process)
- [Coding Standards](#coding-standards)
- [Testing Guidelines](#testing-guidelines)
- [Documentation](#documentation)
- [Community](#community)

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [conduct@example.com](mailto:conduct@example.com).

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the issue tracker to see if the problem has already been reported. When you are creating a bug report, please include as many details as possible:

- Use a clear and descriptive title
- Describe the exact steps to reproduce the problem
- Provide specific examples to demonstrate the steps
- Describe the behavior you observed and what you expected to see
- Include screenshots if applicable
- Include details about your configuration and environment

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion:

- Use a clear and descriptive title
- Provide a detailed description of the suggested enhancement
- Explain why this enhancement would be useful
- Include any relevant examples or mockups

### Your First Code Contribution

Unsure where to begin? Look for issues labeled "good-first-issue" or "help-wanted":

- **Good First Issue** - Issues that should be relatively easy to address
- **Help Wanted** - Issues that may be more involved but are good for contributors

### Pull Requests

- Fill in the required template
- Follow the coding standards
- Include appropriate tests
- Update documentation as needed
- Link to any related issues

## Development Setup

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Git

### Local Development Environment

1. Fork the repository on GitHub
2. Clone your fork locally:
   ```bash
   git clone https://github.com/your-username/linkedin-portfolio-generator.git
   cd linkedin-portfolio-generator
   ```

3. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

4. Set up environment variables:
   ```bash
   cp .env.example .env
   # Edit .env with your local configuration
   ```

5. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

6. Create a branch for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## Pull Request Process

1. Update the README.md or documentation with details of changes if appropriate
2. Update the CHANGELOG.md with details of changes
3. The PR should work with the CI/CD pipeline without errors
4. Ensure all tests pass
5. Get at least one code review from a maintainer
6. Once approved, a maintainer will merge your PR

## Coding Standards

### JavaScript/TypeScript

- We follow the [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
- Use ESLint to ensure code quality
- Use Prettier for code formatting

### CSS/SCSS

- Follow BEM (Block Element Modifier) methodology
- Use variables for colors, spacing, etc.
- Ensure responsive design principles are followed

### Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line

Example:
```
feat: add LinkedIn profile validation

- Add regex pattern for LinkedIn URLs
- Implement validation function
- Add unit tests for validation

Fixes #123
```

## Testing Guidelines

### Types of Tests

- **Unit Tests**: Test individual functions and components
- **Integration Tests**: Test interactions between components
- **End-to-End Tests**: Test the application as a whole

### Running Tests

```bash
# Run all tests
npm test

# Run unit tests
npm run test:unit

# Run integration tests
npm run test:integration

# Run e2e tests
npm run test:e2e

# Run tests with coverage
npm run test:coverage
```

### Test Coverage

We aim for at least 80% test coverage for all new code. Coverage reports are generated when running `npm run test:coverage`.

## Documentation

### Code Documentation

- Use JSDoc comments for functions and classes
- Document complex algorithms and business logic
- Keep comments up-to-date with code changes

### Project Documentation

- README.md: Overview of the project
- CONTRIBUTING.md: This file
- SECURITY.md: Security policies and procedures
- ARCHITECTURE.md: System architecture details
- DEPLOYMENT.md: Deployment instructions
- docs/: Additional documentation

## Community

### Communication Channels

- GitHub Issues: For bug reports and feature requests
- Discussions: For questions and community interaction
- Slack/Discord: For real-time communication (links provided to contributors)

### Recognition

Contributors are recognized in the following ways:
- Listed in the CONTRIBUTORS.md file
- Mentioned in release notes for significant contributions
- Opportunity to become a project maintainer after sustained contributions

---

Thank you for contributing to the LinkedIn Portfolio Generator! Your efforts help make this project better for everyone.
