# Contributing

Thank you for your interest in contributing to go-appsec/interactsh-lite!

## Getting Started

**Setup:**
```bash
# Fork the repository, then clone your fork
git clone https://github.com/YOUR_USERNAME/interactsh-lite
cd interactsh-lite

# Install dependencies
go mod download

# Verify your setup
make test
```

## Development Workflow

**Available Commands:**
```bash
make test        # Run fast tests
make test-all    # Run tests with race detection and coverage including network service usage
make test-cover  # Generate HTML coverage report
make lint        # Run linting and static analysis
```

**Before submitting changes:**
1. Ensure all tests pass: `make test-all`
2. Ensure linting passes: `make lint`
3. Add tests for new features or bug fixes

## Pull Requests

1. Create a feature branch on your personal fork
2. Make your changes following existing code patterns
3. Run `make test && make lint` to verify everything passes
4. Commit with clear, descriptive messages
5. Push to your fork and open a pull request
6. Describe your changes and link any related issues

## Need Help?

If you have questions or need guidance, please [open an issue](https://github.com/go-appsec/interactsh-lite/issues/new?template=question.md) and we'll be happy to help!
