# Contributing to Vibing

Thank you for your interest in contributing to Vibing! This document provides guidelines and instructions for contributing.

## Code of Conduct

By participating in this project, you agree to maintain a respectful and inclusive environment for everyone.

## How to Contribute

### Reporting Bugs

- Use the bug report template when creating an issue
- Include detailed steps to reproduce the problem
- Specify your platform (macOS/Windows) and version
- Attach relevant logs or screenshots

### Suggesting Features

- Use the feature request template
- Clearly describe the problem you're trying to solve
- Explain your proposed solution
- Consider alternative approaches

### Pull Requests

1. **Fork the repository** and create your branch from `main`
2. **Make your changes** following the style guidelines
3. **Test your changes** thoroughly on the relevant platform(s)
4. **Update documentation** if needed
5. **Submit a pull request** using the PR template

## Development Setup

### Prerequisites

- Node.js 20.x or higher
- npm or yarn

### Installation

```bash
# Clone your fork
git clone https://github.com/YOUR_USERNAME/Vibing.git
cd Vibing

# Install dependencies
npm install

# Start development server
npm run dev
```

### Available Scripts

- `npm run dev` - Start local development server
- `npm run validate` - Validate HTML files
- `npm run format` - Format code with Prettier
- `npm run format:check` - Check code formatting
- `npm test` - Run validation tests

## Coding Guidelines

### HTML

- Use semantic HTML5 elements
- Ensure proper accessibility (ARIA labels, alt text, etc.)
- Keep inline styles minimal; prefer external stylesheets
- Validate HTML with `npm run validate`

### CSS

- Use modern CSS features (flexbox, grid)
- Follow mobile-first responsive design
- Use meaningful class names
- Maintain consistency with existing styles

### JavaScript

- Use modern ES6+ syntax
- Write clear, self-documenting code
- Add comments for complex logic
- Handle errors appropriately

### Code Formatting

- Run `npm run format` before committing
- Follow EditorConfig settings
- Use 2 spaces for indentation
- Use LF line endings

## Commit Messages

Write clear, descriptive commit messages:

```
Short summary (50 chars or less)

More detailed explanation if needed. Wrap at 72 characters.
Explain what changed and why, not how.

- Bullet points are okay
- Reference issues: Fixes #123
```

## Testing

Before submitting a PR:

1. Test on the target platform(s)
2. Validate HTML: `npm run validate`
3. Check formatting: `npm run format:check`
4. Verify all links work
5. Test responsive design at various screen sizes

## Documentation

- Update README.md if adding features
- Add comments for complex code
- Update installation guides if needed
- Include screenshots for UI changes

## Questions?

If you have questions, feel free to:
- Open a discussion on GitHub
- Ask in your pull request
- Check existing documentation

Thank you for contributing to Vibing! 🎤
