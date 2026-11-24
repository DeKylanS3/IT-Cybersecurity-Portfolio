# Lab 05 - Git and GitHub Portfolio Deployment

## Objective
Establish a version-controlled professional IT and
cybersecurity portfolio using Git and GitHub.

## Environment
- macOS
- Git 2.50.1
- Zsh
- GitHub
- Markdown

## Implementation
1. Verified Git installation.
2. Configured Git author identity.
3. Configured a private GitHub commit email.
4. Organized technical documentation.
5. Initialized a local Git repository.
6. Configured a .gitignore file.
7. Staged documentation and created an initial commit.
8. Configured a remote GitHub repository.
9. Configured fine-grained token authentication.
10. Successfully published the portfolio.

## Commands Used
- git --version
- git config
- git init
- git status
- git add
- git commit
- git log
- git remote add
- git remote rename
- git remote -v
- git push

## Troubleshooting

### Incorrect Remote Name
Problem: The remote was named original instead of origin.

Resolution:
git remote rename original origin

### Authentication Failure
Problem: GitHub rejected password-based authentication.

Resolution: Configured a fine-grained personal access
token restricted to the portfolio repository.

## Security Concepts
- Principle of least privilege
- Credential management
- Token-based authentication
- Email privacy
- Sensitive file exclusion

## Results
Successfully deployed a professional GitHub portfolio
containing four documented technical labs.

## Skills Demonstrated
- Version control
- Repository management
- Authentication troubleshooting
- Technical documentation
- Secure credential management

## Status
Completed
