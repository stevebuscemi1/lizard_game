# Contributing to Lizard Game 🦎

Thank you for your interest in contributing to Lizard Game! This guide will help you get started with contributing to the project.

## 🤝 How to Contribute

### Reporting Bugs
1. **Search existing issues** before creating a new one
2. **Use the bug report template** when creating new issues
3. **Provide detailed information**:
   - Browser and version
   - Device type (desktop/mobile)
   - Steps to reproduce the issue
   - Expected vs actual behavior
   - Screenshots if applicable

### Suggesting Features
1. **Check for existing feature requests**
2. **Use the feature request template**
3. **Provide clear descriptions** of the proposed feature
4. **Explain the benefit** to players/developers

### Code Contributions
1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/your-feature-name`
3. **Make your changes**
4. **Test thoroughly** on multiple browsers and devices
5. **Commit your changes** with clear messages
6. **Push to your branch**: `git push origin feature/your-feature-name`
7. **Open a Pull Request**

## 🛠️ Development Setup

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor or IDE
- Basic knowledge of HTML, CSS, and JavaScript
- (Optional) Local web server for testing

### Getting Started
1. **Clone your fork**:
   ```bash
   git clone https://github.com/stevebuscemi1/lizard_game.git
   cd lizard-game
   ```

2. **Open the game**:
   - Simply open `lizard_game.html` in your browser
   - Or use a local server:
     ```bash
     # Python 3
     python -m http.server 8000
     # Python 2
     python -m SimpleHTTPServer 8000
     # Node.js (if you have http-server installed)
     npx http-server
     ```
   - Then visit `http://localhost:8000`

### Testing
- **Test on multiple browsers**: Chrome, Firefox, Safari, Edge
- **Test on mobile devices**: Use browser dev tools or actual devices
- **Test different screen sizes**: Ensure responsive design works
- **Test game functionality**: All features should work correctly

## 📝 Code Guidelines

### JavaScript
- Use **ES6+** features when appropriate
- Follow **camelCase** naming convention
- Use **descriptive variable and function names**
- Add **comments** for complex logic
- Handle errors gracefully with try-catch blocks

### HTML/CSS
- Use **semantic HTML5** elements
- Follow **BEM** methodology for CSS classes when possible
- Ensure **responsive design** works on all screen sizes
- Use **CSS Grid and Flexbox** for layouts

### File Structure
```
lizard-game/
├── lizard_game.html          # Main game file
├── README.md                 # Project documentation
├── LICENSE                   # License
├── CONTRIBUTING.md           # Contribution guidelines
├── .gitignore               # Git ignore file
└── assets/                  # (Optional) Additional assets
```

## 🎯 Contribution Areas

### 🎮 Game Features
- **New levels** with different challenges
- **Additional leaf types** with unique properties
- **New power-ups** and abilities
- **Boss battles** with different mechanics
- **Achievement system** expansions

### 🎨 Visual & Audio
- **New lizard customization** options
- **Improved animations** and visual effects
- **Additional sound effects** and music
- **Better visual feedback** for actions

### 📱 Mobile & Performance
- **Touch gesture** improvements
- **Performance optimizations**
- **Battery usage** optimizations
- **Better responsive design**

### 🔧 Technical Improvements
- **Code refactoring** and optimization
- **Better error handling**
- **Improved accessibility**
- **PWA features** (offline support, installable)

### 📚 Documentation
- **Improved README** and guides
- **API documentation** (if applicable)
- **Translation** for different languages
- **Video tutorials** or walkthroughs

## 🐛 Bug Fix Process

### Before Fixing
1. **Reproduce the bug** consistently
2. **Understand the root cause**
3. **Check for similar issues** in other parts of the code
4. **Consider edge cases** that might be affected

### While Fixing
1. **Make minimal changes** that fix the issue
2. **Don't break existing functionality**
3. **Add comments** explaining the fix
4. **Test thoroughly** after changes

### After Fixing
1. **Verify the fix works** on multiple browsers
2. **Test related functionality** isn't broken
3. **Document the change** if needed
4. **Update tests** (if applicable)

## 📝 Pull Request Process

### Before Submitting
1. **Test your changes** thoroughly
2. **Ensure code follows** project guidelines
3. **Update documentation** if needed
4. **Check for typos** and errors

### Pull Request Template
Use the following structure for your PR:

```markdown
## Description
Brief description of changes made.

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Breaking change
- [ ] Documentation update

## Testing
- [ ] Tested on Chrome
- [ ] Tested on Firefox
- [ ] Tested on Safari
- [ ] Tested on mobile
- [ ] All existing tests pass

## Checklist
- [ ] Code follows project guidelines
- [ ] Self-review completed
- [ ] Documentation updated
- [ ] No breaking changes
```

### After Submitting
1. **Respond to feedback** promptly
2. **Make requested changes**
3. **Keep the PR updated**
4. **Be patient** with the review process

## 🏆 Recognition

Contributors will be recognized in:
- **README.md** contributors section
- **Game credits** (for significant contributions)
- **Release notes** for included features

## 📞 Getting Help

### Questions?
- **GitHub Discussions**: Ask general questions
- **GitHub Issues**: Report bugs or request features
- **Email**: minequest.subsystem972@passinbox.com

### Resources
- **HTML5 Game Development**: MDN Web Docs
- **JavaScript Best Practices**: Modern JS tutorials
- **CSS Techniques**: CSS-Tricks and MDN
- **Mobile Development**: Web.dev mobile guides

## 🎉 Thank You!

Your contributions help make Lizard Game better for everyone. Whether you're fixing bugs, adding features, or improving documentation, your help is greatly appreciated!

---

**Happy Coding! 🦎🎮**
