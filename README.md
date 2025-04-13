# sample-dotnet-pipeline
## Branching Strategy

This repository follows a simple branching strategy:

- `main`: Production-ready code
- `develop`: Integration branch for feature development
- `feature/feature-name`: Individual feature branches

Workflow:
1. Create a feature branch from `develop`
2. Work on your changes in the feature branch
3. Create a Pull Request to merge back to `develop`
4. After testing, `develop` is merged to `main` for production
