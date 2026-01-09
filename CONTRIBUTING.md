# Contribution Guide

We welcome contributions to extend the AI-Endorsed Smart Contract architecture.

## How to Contribute

1. **Fork the repository** and create a new branch.
2. **Propose endorsement modules** using the issue template in `.github/ISSUE_TEMPLATE/endorsement-module.md`.
3. **Implement modules** in Python or Solidity, following the existing structure:
   - `/copilot-endorsement/` for Python verifiers
   - `/contracts/` for Solidity smart contracts
4. **Document your module** in `/docs` with clear usage instructions.
5. **Submit a Pull Request** with:
   - Code implementation
   - Documentation updates
   - Example data files (if applicable)

## Coding Standards

- Python: PEP8 style guide
- Solidity: Latest stable compiler version (`pragma solidity ^0.8.x`)
- Documentation: Markdown with clear headings and examples

## Review Process

- All contributions will be reviewed for technical accuracy and alignment with the endorsement orchestration model.
- At least one endorsement module maintainer must approve before merging.

## Community Guidelines

- Be respectful and collaborative.
- Focus on building distributed algorithmic trust.
- Ensure modules are safe, transparent, and auditable.
