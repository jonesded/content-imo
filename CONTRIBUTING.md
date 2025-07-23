# Contributing to HNM Devs Docs

Welcome to HNM Devs Docs! We're excited that you want to contribute to our modern developer documentation platform. This guide will help you get started and make meaningful contributions to our community.

## 🚀 Quick Start for Contributors

### Prerequisites

- [Node.js](https://nodejs.org/) v22 or higher
- [Yarn](https://classic.yarnpkg.com/) package manager
- [Git](https://git-scm.com/) for version control
- A [GitHub account](https://github.com/join)

### Setting Up Your Development Environment

1. **Fork the Repository**
   ```bash
   # Click "Fork" on GitHub, then clone your fork
   git clone https://github.com/YOUR_USERNAME/docs.git
   cd docs
   ```

2. **Install Dependencies**
   ```bash
   yarn install
   ```

3. **Start the Development Server**
   ```bash
   yarn start
   ```
   
   The site will be available at `http://localhost:5042/`

4. **Create a Feature Branch**
   ```bash
   git checkout -b feature/your-awesome-feature
   ```

## 📝 Types of Contributions

We welcome various types of contributions:

### 🔧 Content Contributions
- **New Guides**: Modern development tutorials and best practices
- **API Documentation**: Comprehensive reference materials
- **Code Examples**: Real-world implementation samples
- **Updates**: Keeping existing content current and accurate

### 🐛 Bug Reports and Fixes
- Documentation errors and typos
- Broken links or outdated information
- Website functionality issues
- Performance improvements

### 💡 Feature Requests
- New documentation sections
- Interactive examples and demos
- Improved navigation and search
- Enhanced mobile experience

### 🎨 Design and UX
- Visual design improvements
- Accessibility enhancements
- User experience optimizations
- Brand consistency updates

## 📋 Content Guidelines

### Writing Style
- **Clear and Concise**: Use simple, direct language
- **Practical Focus**: Include real-world examples and use cases
- **Code-First**: Lead with practical implementation
- **Modern Standards**: Focus on current best practices
- **Inclusive Language**: Use welcoming, accessible terminology

### Technical Standards
- **Code Quality**: Follow industry best practices
- **Performance**: Optimize for speed and efficiency
- **Security**: Include security considerations
- **Accessibility**: Ensure content is accessible to all users
- **Mobile-First**: Design for mobile devices first

### Content Structure
```markdown
# Page Title

Brief introduction explaining what this page covers.

## Prerequisites
- List any required knowledge
- Link to foundational concepts

## Quick Start
Minimal working example to get users started quickly.

## Detailed Guide
Step-by-step instructions with explanations.

## Best Practices
Performance, security, and maintainability tips.

## Common Pitfalls
Known issues and how to avoid them.

## Related Resources
Links to related documentation and external resources.
```

## 🔄 Contribution Workflow

### 1. Planning Your Contribution
- Check existing [issues](https://github.com/hnmdevs/docs/issues) and [discussions](https://github.com/hnmdevs/docs/discussions)
- Create an issue for substantial changes
- Join our [Discord](https://discord.gg/hnmdevs) to discuss ideas

### 2. Making Changes
- Follow our [style guide](#writing-style)
- Test your changes locally
- Ensure all lints pass: `yarn lint`
- Add or update tests if needed

### 3. Submitting Your Contribution
- Create a descriptive pull request
- Reference any related issues
- Include screenshots for visual changes
- Be responsive to feedback

### 4. Review Process
- All contributions are reviewed by maintainers
- We may request changes or improvements
- Once approved, changes are merged and deployed

## 🛠 Development Commands

```bash
# Start development server
yarn start

# Run all lints and checks
yarn lint

# Fix common formatting issues
yarn fix:md
yarn fix:js
yarn fix:json

# Run tests
yarn test

# Build for production
yarn build:prod
```

## 📁 File Organization

```
files/
├── en-us/                    # English content
│   ├── web/                  # Web development guides
│   │   ├── api/             # API references
│   │   ├── guides/          # Step-by-step tutorials
│   │   └── examples/        # Code examples
│   ├── cloud/               # Cloud and DevOps
│   ├── security/            # Security best practices
│   └── emerging-tech/       # AI/ML, Web3, etc.
├── jsondata/                # Structured data
└── sidebars/                # Navigation configuration
```

## 🎯 Priority Areas

We're especially looking for contributions in:

- **Modern JavaScript Frameworks**: React, Vue, Svelte, Next.js
- **Cloud-Native Development**: Docker, Kubernetes, serverless
- **DevOps and CI/CD**: GitHub Actions, automated testing, deployment
- **Performance Optimization**: Core Web Vitals, bundling, caching
- **Security Best Practices**: Authentication, authorization, data protection
- **Accessibility**: WCAG compliance, inclusive design patterns

## 📐 Design System

### Brand Colors
- **Primary**: `#00ff88` (HNM Green)
- **Secondary**: `#1a1a1a` (Dark Gray)
- **Accent**: `#ff6b00` (Orange)
- **Background**: `#ffffff` (White)
- **Text**: `#333333` (Dark Gray)

### Typography
- **Headings**: Inter, system fonts
- **Body**: Inter, system fonts
- **Code**: 'SF Mono', 'Monaco', 'Inconsolata', monospace

### Component Guidelines
- Use semantic HTML
- Implement proper ARIA labels
- Ensure keyboard navigation
- Test with screen readers
- Support dark mode preferences

## 🤝 Community Guidelines

### Code of Conduct
We are committed to providing a welcoming and inclusive experience for everyone. Please read and follow our [Code of Conduct](CODE_OF_CONDUCT.md).

### Communication Channels
- **GitHub Issues**: Bug reports and feature requests
- **GitHub Discussions**: General questions and community chat
- **Discord**: Real-time collaboration and support
- **Twitter**: Updates and announcements

### Recognition
Contributors are recognized in:
- Release notes and changelogs
- Contributor credits on the website
- Special contributor badges
- Annual contributor appreciation posts

## 📚 Resources for Contributors

### Learning Resources
- [MDN Web Docs](https://developer.mozilla.org/) - Web standards reference
- [React Documentation](https://react.dev/) - React framework guide
- [Next.js Documentation](https://nextjs.org/docs) - Full-stack React framework
- [Kubernetes Documentation](https://kubernetes.io/docs/) - Container orchestration

### Tools and Extensions
- [Prettier](https://prettier.io/) - Code formatting
- [ESLint](https://eslint.org/) - JavaScript linting
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) - VS Code extension
- [GitHub CLI](https://cli.github.com/) - Command-line GitHub interface

## 🔍 Getting Help

### Common Issues
1. **Build Errors**: Clear `node_modules` and reinstall dependencies
2. **Port Conflicts**: Change the port in development server settings
3. **Lint Failures**: Run `yarn fix:md` to auto-fix common issues
4. **Content Not Updating**: Hard refresh your browser (Ctrl+F5)

### Support Channels
- Create an [issue](https://github.com/hnmdevs/docs/issues/new) for bugs
- Start a [discussion](https://github.com/hnmdevs/docs/discussions) for questions
- Join our [Discord](https://discord.gg/hnmdevs) for real-time help
- Email us at [support@hnmdevs.com](mailto:support@hnmdevs.com)

---

Thank you for contributing to HNM Devs Docs! Together, we're building the next generation of developer documentation. 🚀

**Happy coding!** ❤️
