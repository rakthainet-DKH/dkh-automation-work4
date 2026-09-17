# Contributing to DKH Automation Work 4

## How to Contribute

1. Fork the repository
2. Create a feature branch from `DKH` branch
3. Make your changes
4. Write or update tests
5. Submit a pull request

## Branch Naming

- `feature/description` - For new features
- `fix/description` - For bug fixes
- `docs/description` - For documentation
- `refactor/description` - For code refactoring

## Code Style

### Java
- Follow Google Java Style Guide
- Use Spring conventions
- Add proper JavaDoc

### Go
- Follow Go Code Review Comments
- Use `golangci-lint` for linting
- Add proper comments

## Commit Messages

```
type(scope): subject

body

footer
```

Examples:
- `feat(workflow): add new workflow type`
- `fix(api): resolve authentication issue`
- `docs(readme): update installation guide`

## Testing

```bash
# Java
cd java-services
mvn test

# Go
cd go-services
go test ./...
```

## Pull Request Process

1. Update README.md with any new features
2. Ensure all tests pass
3. Provide clear description of changes
4. Link related issues
5. Wait for code review

## Questions?

Open an issue or discussion in the repository.
