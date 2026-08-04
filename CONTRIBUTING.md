# Contributing to EOSIO Documentation

Thank you for your interest in contributing to EOSIO Documentation! This document provides guidelines and procedures for contributing to this project.

## Code of Conduct

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

## How to Contribute

### Reporting Issues

If you find an error, inconsistency, or gap in the documentation:

1. **Check existing issues** - Search to see if the issue has already been reported
2. **Create a detailed issue** including:
   - Document/section affected
   - Current content (quote or link)
   - What's wrong or missing
   - Suggested improvement (if applicable)

### Submitting Changes

#### Small Changes (Typos, Grammar, Clarity)

1. **Fork the repository**
2. **Create a branch**: `git checkout -b fix/description-of-fix`
3. **Make your changes** in the relevant markdown file
4. **Test your changes** - Verify formatting renders correctly
5. **Commit with clear message**: `git commit -m "Fix: description of what was corrected"`
6. **Push to your fork**: `git push origin fix/description-of-fix`
7. **Open a Pull Request** with description of changes

#### Major Changes (New Sections, Significant Updates)

1. **Open an issue first** - Discuss proposed changes before implementing
2. **Follow the small changes process** above
3. **Include rationale** in your PR description explaining why changes are needed
4. **Reference** the issue in your PR: `Closes #issue-number`

### Pull Request Process

1. **Title Format**: Use clear, descriptive titles
   - Good: `docs: Add security reporting procedures to SECURITY.md`
   - Avoid: `fix stuff`, `update docs`

2. **Description Template**:
   ```
   ## Description
   Brief description of changes

   ## Changes
   - Change 1
   - Change 2
   
   ## Why
   Explanation of why these changes are needed

   ## Testing
   How to verify these changes are correct
   
   ## Closes
   Fixes #issue-number (if applicable)
   ```

3. **Keep PRs focused** - One topic per PR when possible
4. **Reference issues** - Link related issues and PRs
5. **Be patient** - The project is maintained by volunteers; responses may take time

## Documentation Standards

### Formatting

- Use standard Markdown formatting
- Keep line length reasonable (80-120 characters) for readability
- Use clear headings hierarchy (H1 for title, H2 for sections, etc.)
- Use code blocks with language specified:
  ```markdown
  ```javascript
  // code here
  ```
  ```

### Content Guidelines

- **Be accurate**: Ensure technical content is correct and up-to-date
- **Be clear**: Write for both beginners and advanced users
- **Be concise**: Avoid unnecessary verbosity
- **Link appropriately**: Reference related documentation
- **Include examples**: Provide practical examples where helpful
- **Note version differences**: Clearly indicate which EOSIO versions content applies to

### File Organization

```
EOSIO/Documentation/
├── README.md                 # Main overview
├── SECURITY.md              # Security policy
├── CONTRIBUTING.md          # This file
├── CODE_OF_CONDUCT.md       # Community standards
├── TechnicalWhitePaper.md   # Main technical document
├── Roadmap.md               # Project roadmap
└── translations/            # Translated versions
    ├── zh-CN/
    ├── ru-RU/
    └── ko-KR/
```

## Translations

If you'd like to contribute translations:

1. **Check existing translations** at Crowdin or in the `translations/` directory
2. **Create translation file** following the same structure as English version
3. **Use language code prefix** (e.g., `es-ES/`, `fr-FR/`)
4. **Submit PR** with translated content

## Review Process

1. **Automated checks** will run (formatting, links, etc.)
2. **Maintainer review** - Someone will review your PR
3. **Feedback** - Any requested changes will be clearly outlined
4. **Approval** - Once approved, your PR will be merged
5. **Credit** - You'll be recognized as a contributor

## Recognition

Contributors are recognized in:
- Pull Request comments
- Repository contributors list
- Release notes (for significant contributions)
- Author attributions in modified sections

## Questions?

- Check existing [Issues](https://github.com/EOSIO/Documentation/issues)
- Review [Pull Requests](https://github.com/EOSIO/Documentation/pulls)
- Email: documentation@eosio.io
- Community: [EOS Discord #documentation](https://discord.gg/eos)

## License

By contributing to EOSIO Documentation, you agree that your contributions will be licensed under the same terms as the project.

---

**Thank you for helping improve EOSIO Documentation!**

Last Updated: August 2026
