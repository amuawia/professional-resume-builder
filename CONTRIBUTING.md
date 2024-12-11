# Contributing to Professional Resume Builder

## Code of Conduct

We are committed to providing a friendly, safe, and welcoming environment for all contributors. Be kind, respectful, and considerate of others.

## How to Contribute

1. **Fork the Repository**
   - Fork the main repository to your GitHub account
   - Clone your forked repository locally

2. **Set Up Development Environment**
   - Ensure you have Docker and Docker Compose installed
   - Set up required environment variables
   - Run `docker-compose up --build` to start the development environment

3. **Branch Naming Convention**
   - Use descriptive branch names
   - Format: `type/description`
   - Examples:
     - `feature/add-resume-templates`
     - `bugfix/login-authentication`
     - `docs/update-readme`

4. **Commit Messages**
   - Use clear and concise commit messages
   - Follow the conventional commits format:
     ```
     <type>(<optional scope>): <description>
     
     <optional body>
     ```
   - Example: `feat(frontend): add new resume template design`

5. **Pull Request Process**
   - Create a pull request from your fork to the main repository
   - Ensure all CI/CD checks pass
   - Provide a clear description of changes
   - Request a review from maintainers

6. **Code Style**
   - Frontend (React): Follow Airbnb React/JSX Style Guide
   - Backend (Node.js): Follow Google JavaScript Style Guide
   - Use ESLint and Prettier for consistent code formatting

7. **Testing**
   - Write unit tests for new features
   - Ensure 80% test coverage for new code
   - Run `npm test` before submitting a pull request

8. **Security**
   - Do not commit sensitive information like API keys
   - Use environment variables for secrets
   - Report security vulnerabilities privately

## Reporting Bugs

- Use GitHub Issues to report bugs
- Provide a clear title and description
- Include steps to reproduce
- Add your environment details (OS, browser, etc.)
- If possible, include a code snippet or screenshot

## Feature Requests

- Open a GitHub Issue for feature suggestions
- Describe the proposed feature in detail
- Explain the use case and potential benefits

## Questions?

- Join our Discord community
- Open an issue for project-related questions

Thank you for contributing to Professional Resume Builder!