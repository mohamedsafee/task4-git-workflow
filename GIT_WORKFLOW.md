# Git Workflow Documentation

## Repository Setup
The repository is managed using Git and hosted on GitHub.

## Branches
- main: Stable release branch.
- dev: Integration branch.
- feature/documentation: Feature implementation branch.

## Pull Request Process
1. Push changes to a feature branch.
2. Open a pull request targeting dev.
3. Review and merge the changes.
4. Open a pull request targeting main.
5. Review and merge the release changes.

## Commit Convention
Use descriptive messages such as:
- docs: add project README
- chore: update gitignore
- docs: document branching workflow

## Release Tags
Use version tags such as v1.0.0 to identify stable releases.

## Merge Conflict Resolution
Review conflicting files, edit the conflict markers, test the result, and commit the resolved changes.
