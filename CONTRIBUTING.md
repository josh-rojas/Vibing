# Contributing to Vibing Website

Thank you for your interest in contributing to the Vibing website! This repository contains the **documentation and landing page website** for Vibing, a voice input desktop application for macOS and Windows.

> **Note:** This repository contains the marketing website and documentation. For issues with the Vibing desktop application itself, please report them through the app or contact support.

## About This Repository

This is the source code for the website hosted at [vibingjustspeakit.github.io/Vibing](https://vibingjustspeakit.github.io/Vibing/). It includes:
- Landing page (index.html)
- Installation guides
- Feature demonstrations
- Documentation

## Code of Conduct

By participating in this project, you agree to maintain a respectful and inclusive environment for everyone.

## How to Contribute

### Reporting Website Issues

- Use the bug report template when creating an issue
- Specify which page has the issue
- Include browser and OS information
- Attach screenshots if applicable

### Suggesting Website Improvements

- Use the feature request template
- Clearly describe the improvement
- Explain how it benefits users
- Consider alternative approaches

### Pull Requests

1. **Fork the repository** and create your branch from `main`
2. **Make your changes** following the style guidelines
3. **Test your changes** on multiple browsers
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

1. Test on multiple browsers (Chrome, Firefox, Safari)
2. Test on mobile devices
3. Validate HTML: `npm run validate`
4. Check formatting: `npm run format:check`
5. Verify all links work
6. Test responsive design at various screen sizes

## Documentation

- Update README.md if adding features or changing content
- Ensure installation guides are accurate
- Include screenshots for UI changes
- Keep documentation in sync with website content

## Questions?

If you have questions, feel free to:
- Open a discussion on GitHub
- Ask in your pull request
- Check existing documentation

Thank you for contributing to the Vibing website! 🎤
