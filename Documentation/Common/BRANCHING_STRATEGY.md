# Branching Strategy - TaskFlow Pro

## Branch Types

### Main Branches

- **main**: Production-ready code, protected branch
- **develop**: Integration branch for features

### Supporting Branches

- **feature/**: New features (`feature/task-creation`)
- **fix/**: Bug fixes (`fix/task-toggle-bug`)
- **chore/**: Maintenance tasks (`chore/update-dependencies`)

## Workflow

1. Create feature branch from `develop`
2. Work on feature with conventional commits
3. Test thoroughly before merge
4. Merge to `develop` via pull request
5. Deploy `main` from `develop` after testing

## Branch Protection (to implement later)

- `main` branch requires pull request reviews
- `main` branch requires status checks to pass
- Direct pushes to `main` are blocked
