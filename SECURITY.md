# Security Policy

## Reporting a Vulnerability

**Do NOT open a public GitHub issue for security vulnerabilities.**

If you discover a security vulnerability in any 0x3 Team project, please report it responsibly:

1. **Email**: [security@0x3.dev](mailto:security@0x3.dev)
2. **Subject line**: `[VULN] <project-name> - <brief description>`
3. **Include**:
   - Affected repository and version/commit
   - Description of the vulnerability
   - Steps to reproduce
   - Potential impact
   - Suggested fix (if any)

## Response Timeline

| Step | Target SLA |
|---|---|
| Acknowledge receipt | 48 hours |
| Initial assessment | 5 business days |
| Fix or mitigation delivered | 30 days (severity dependent) |
| Public disclosure | After fix is released, coordinated with reporter |

## Disclosure Policy

- We follow **coordinated disclosure**
- We will credit reporters (publicly or anonymously, your choice)
- We will not pursue legal action against good-faith security research
- We ask that you do not publicly disclose the vulnerability until a fix is available

## Scope

This policy covers security vulnerabilities in:
- All repositories under the [0x3-team](https://github.com/0x3-team) organization
- Our infrastructure at 0x3.dev

Out of scope:
- Social engineering attacks
- DoS / DDoS attacks
- Automated scanner reports without proof of exploitability
- Issues in third-party dependencies (report upstream)

## Security Features Enabled

All repositories created in this organization have the following enabled by default:
- Dependabot security alerts
- Dependabot security updates
- Secret scanning with push protection
- Dependency graph

## Contact

- **General security**: [security@0x3.dev](mailto:security@0x3.dev)
- **Security team**: [@0x3-team/security](https://github.com/orgs/0x3-team/teams/security)
