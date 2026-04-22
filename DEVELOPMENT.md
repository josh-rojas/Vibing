# Development Guide

## About This Repository

This repository contains the **documentation and marketing website** for Vibing, not the desktop application itself.

**What's in this repo:**
- Landing page and website (index.html)
- Installation guides
- Feature demonstrations
- Documentation pages

**What's NOT in this repo:**
- The Vibing macOS/Windows desktop application source code
- The backend server or API
- The voice processing engine

This is a static website hosted on GitHub Pages that provides information about the Vibing desktop app.

## Getting Started

### Prerequisites

- Node.js 20.x or higher
- npm 9.x or higher

### Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

The site will be available at `http://localhost:8080`

## Project Structure

```
Vibing/
├── index.html              # Main landing page
├── installation-guide.html # macOS installation guide
├── hotkeys-demo.html       # Hotkeys demonstration
├── src/                    # Assets (images, videos)
│   ├── logo.png
│   ├── logo_transparent.png
│   ├── usage.png
│   └── intro.mp4
├── images/                 # Additional images
├── .github/                # GitHub configuration
│   ├── workflows/          # CI/CD workflows
│   └── ISSUE_TEMPLATE/     # Issue templates
└── package.json            # Project configuration
```

## Development Workflow

### Making Changes

1. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. Make your changes to the HTML/CSS files

3. Test locally:
   ```bash
   npm run dev
   ```

4. Validate your changes:
   ```bash
   npm run validate
   npm run format:check
   ```

5. Format code:
   ```bash
   npm run format
   ```

### HTML Development

- All HTML files are standalone and self-contained
- Styles are embedded in `<style>` tags
- JavaScript is embedded in `<script>` tags
- Follow semantic HTML5 practices
- Ensure responsive design (mobile-first approach)

### Styling Guidelines

- Use CSS custom properties for theming
- Maintain consistent spacing and typography
- Support both light and dark color schemes
- Test at various viewport sizes
- Use flexbox/grid for layouts

### Adding New Pages

1. Create new HTML file in the root directory
2. Copy the structure from existing pages
3. Update navigation links in all pages
4. Add proper meta tags and title
5. Test responsiveness
6. Validate HTML

### Assets

- Images go in `/src` or `/images`
- Optimize images before committing (compress, appropriate format)
- Use descriptive filenames
- Include alt text for all images

## Testing

### Local Testing

```bash
# Start local server
npm run dev

# In another terminal, validate
npm run validate
```

### Manual Testing Checklist

- [ ] Test on Chrome, Firefox, Safari
- [ ] Test on mobile devices
- [ ] Verify all links work
- [ ] Check responsive design
- [ ] Validate HTML
- [ ] Test download links
- [ ] Verify images load correctly
- [ ] Check video playback

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch.

### Deployment Process

1. Push to `main` branch triggers CI/CD workflow
2. HTML validation runs
3. Format checking runs
4. If tests pass, site deploys to GitHub Pages
5. Site is available at: https://vibingjustspeakit.github.io/Vibing/

### Manual Deployment

GitHub Pages deployment is handled automatically by GitHub Actions. No manual deployment steps are needed.

## Scripts Reference

| Script | Description |
|--------|-------------|
| `npm run dev` | Start local development server on port 8080 |
| `npm run validate` | Validate HTML files |
| `npm run format` | Format all HTML, CSS, JS, JSON, and MD files |
| `npm run format:check` | Check if files are formatted correctly |
| `npm test` | Run validation tests |

## Troubleshooting

### Port 8080 Already in Use

```bash
# Use a different port
npx http-server -p 3000 -o
```

### HTML Validation Errors

```bash
# Check specific file
npx html-validate index.html

# Get detailed output
npx html-validate --formatter stylish index.html
```

### Formatting Issues

```bash
# See what files need formatting
npm run format:check

# Auto-fix formatting
npm run format
```

## Resources

- [HTML5 Specification](https://html.spec.whatwg.org/)
- [MDN Web Docs](https://developer.mozilla.org/)
- [GitHub Pages Documentation](https://docs.github.com/pages)
- [Prettier Documentation](https://prettier.io/docs/)

## Getting Help

- Check existing [Issues](https://github.com/VibingJustSpeakIt/Vibing/issues)
- Open a [Discussion](https://github.com/VibingJustSpeakIt/Vibing/discussions)
- Read [CONTRIBUTING.md](CONTRIBUTING.md)

## Best Practices

1. **Keep it simple**: Use vanilla HTML/CSS/JS when possible
2. **Mobile-first**: Design for mobile, enhance for desktop
3. **Accessibility**: Use semantic HTML and ARIA labels
4. **Performance**: Optimize images and minimize file sizes
5. **Cross-browser**: Test on multiple browsers
6. **Validation**: Always validate HTML before committing
7. **Formatting**: Run prettier before committing

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
