# Security Policy

## Supported Versions

The following table outlines which versions of EOSIO software receive security updates:

| Version | Supported          | Notes                              |
| ------- | ------------------ | ---------------------------------- |
| 5.1.x   | :white_check_mark: | Latest stable release              |
| 5.0.x   | :x:                | End of life - upgrade recommended  |
| 4.0.x   | :white_check_mark: | Legacy support available           |
| < 4.0   | :x:                | No longer supported                |

Users are strongly encouraged to upgrade to the latest supported version to receive security patches and bug fixes.

## Reporting a Vulnerability

**Do not disclose security vulnerabilities publicly on GitHub issues or discussions.**

### How to Report

If you discover a security vulnerability in EOSIO Documentation or related EOSIO software:

1. **Email Security Team**: Contact the appropriate security contacts listed below
2. **Subject Line**: Include `[SECURITY]` prefix and brief description
3. **Include Details**:
   - Description of the vulnerability
   - Affected version(s)
   - Steps to reproduce (if applicable)
   - Potential impact assessment
   - Suggested remediation (if available)

### Security Contacts

- **EOSIO Core Security**: security@eosio.io
- **EOS Network Foundation**: security@eosnetwork.org
- **GitHub Security Advisory**: Report via GitHub's [Security Advisory feature](https://github.com/EOSIO/Documentation/security/advisories)

### Response Timeline

We aim to provide security updates within the following timeframes:

- **Critical Vulnerabilities** (CVSS 9.0-10.0): Response within 24-48 hours
- **High Severity** (CVSS 7.0-8.9): Response within 72 hours
- **Medium Severity** (CVSS 4.0-6.9): Response within 2 weeks
- **Low Severity** (CVSS 0.1-3.9): Response within 30 days

### What to Expect

1. **Acknowledgment**: You will receive confirmation of receipt within 1 business day
2. **Investigation**: Our security team will investigate the report thoroughly
3. **Communication**: We will keep you updated on progress
4. **Resolution**: Upon confirmation and patching, we will coordinate a public disclosure timeline
5. **Credit**: Security researchers may be credited (with permission) in security advisories

### Disclosure Policy

- Researchers are asked to provide at least **30 days** for patch development before public disclosure
- EOSIO will work with researchers to establish a reasonable disclosure timeline
- Public disclosure will include researcher credit and details of the vulnerability

## Security Best Practices

Users and developers implementing EOSIO should follow these practices:

- Keep EOSIO software updated to the latest supported version
- Follow the principle of least privilege for account permissions
- Use role-based permission management as documented in the Technical Whitepaper
- Regularly audit smart contract code before deployment
- Monitor official EOSIO channels for security announcements
- Report suspicious activity to local authorities if criminal activity is suspected

## Security Advisories

Security advisories and patches are published in:
- GitHub [Security Advisories](https://github.com/EOSIO/Documentation/security/advisories)
- [EOSIO Announcements](https://eosio.io/announcements)
- EOS Network Foundation official channels

## Third-Party Dependencies

EOSIO Documentation acknowledges that security vulnerabilities may exist in third-party dependencies. Please refer to individual project security policies for those components.

## Questions?

If you have questions about this security policy or need clarification, please contact security@eosio.io

---

**Last Updated**: August 2026  
**Policy Version**: 1.0
