# Contributing to Moon7 Libraries

Thank you for your interest in contributing to the Moon7 ecosystem! This document outlines the process for contributing to our TypeScript libraries and tools.

## Code of Conduct

By participating in this project, you are expected to uphold our code of conduct. Please report unacceptable behavior to the project maintainers.

## Getting Started

1. **Fork the Repository**: Start by forking the repository you wish to contribute to.

2. **Clone Your Fork**: 
   ```bash
   git clone https://github.com/your-username/repository-name.git
   cd repository-name
   ```

3. **Install Dependencies**:
   ```bash
   pnpm install
   ```

4. **Create a Branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## Development Workflow

### Coding Standards

- Follow TypeScript best practices
- Maintain consistent code style with existing codebase
- Use meaningful variable and function names
- Write comprehensive comments for complex logic

### Testing

All changes should include appropriate tests:

```bash
pnpm test
```

For coverage reporting:

```bash
pnpm test:coverage
```

### Linting

We enforce code quality and consistency through linting:

```bash
pnpm lint
```

This will show all linting warnings and errors. If you only want to see errors (warnings are acceptable):

```bash
pnpm lint:errors
```

Please fix all errors before submitting your pull request. Warnings should be addressed when possible, but are not blockers for contribution.

### Building

Build the project to verify your changes:

```bash
pnpm build
```

## Pull Request Process

1. **Update Documentation**: Ensure README.md and other documentation are updated.

2. **Run Tests**: Make sure all tests pass.

3. **Lint Code**: Ensure `pnpm lint:errors` passes without errors. 

4. **Submit PR**: Create a pull request with a clear title and description.

5. **Code Review**: Address any feedback from maintainers.

6. **Merge**: Once approved, your PR will be merged.

## Commit Guidelines

We follow a structured commit message format:

```
type(scope): short description

Longer description if needed
```

Types include:
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Formatting changes
- `refactor`: Code refactoring
- `test`: Adding or modifying tests
- `chore`: Maintenance tasks

## Release Process

Releases are managed by the project maintainers following semantic versioning:

- **Major**: Breaking changes
- **Minor**: New features without breaking changes
- **Patch**: Bug fixes and minor improvements

## Questions?

If you have any questions, feel free to open an issue in the relevant repository.

Thank you for contributing to moon7 libraries!