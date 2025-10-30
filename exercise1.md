# Tools
For a python web project, here are some relevant tooling:
## Linting
- Pylint - more comprehesive analysis, but can be slower than Flake8
- Flake8 - combines Pyflakes' error linter with PEP 8 style checks, but less in-depth than Pylint
## Testing
- Pytest - most popular, open source. Supports unit, functional, and API tests
- PyUnit (Unittest) - built into Python, default unit testing framework
## Building
- build - manages `pyproject.toml` based builds, super simple way to package a project into a distribution package that can be shared through tools like `pip`
- Hatch - Standardized build system with reproducible builds by default

# CI Alternatives
- GitLab CI/CD - built into GitLab
- Azure DevOps Server - created by Microsoft and integrates well with their other products like VSCode
- Bitbucket Pipelines - built into Bitbucket

# Self-Hosted vs Cloud-Based
- It depends on the nature of the project - if it's an open source project, hosting it in the cloud would make more sense so that more people across the world can access and contribute to it. If it's highly sensitive and requires strict access controls and background checks, it's better to be self-hosted. You also need enough people on site to manage the hardware for on-prem - which could be difficult, but you can control costs and hardware much more easily.