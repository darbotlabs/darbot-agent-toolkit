# Copilot Instructions for Darbot Agent Toolkit

## Repository Overview

Darbot Agent Toolkit is a comprehensive framework for building intelligent agents and conversational AI applications. This is a monorepo containing multiple packages that work together to provide a complete development experience.

## Repository Structure

This repository uses a monorepo structure managed by pnpm workspaces with the following key packages:

- **packages/vscode-extension**: Visual Studio Code extension for agent development
- **packages/cli**: Command-line interface tool 
- **packages/sdk**: Core SDK with authentication and utilities for agent developers
- **packages/api**: API contracts and interfaces
- **packages/fx-core**: Core implementation shared by IDE extensions and CLI
- **packages/function-extension**: Azure Functions integration
- **packages/spec-parser**: OpenAPI spec parser for API-based extensions
- **packages/adaptivecards-tools-sdk**: Adaptive Cards development tools
- **templates/**: Project templates for different platforms (VS Code, Visual Studio)

## Development Guidelines

### Package Manager
- This project uses **pnpm** (version 8.6.12) as the package manager
- Run `pnpm install` to install dependencies
- Use `pnpm build` to build all packages
- Use `pnpm --parallel -r run watch` for development mode

### Node.js Version
- Requires Node.js >= 22 (though currently running on 20.x)
- Use the version specified in package.json engines field

### Coding Standards
- TypeScript is the primary language for most packages
- ESLint is configured with custom rules (see eslint-local-rules.js)
- Husky is set up for git hooks with pre-commit linting
- Commitlint enforces conventional commit messages

### Testing
- Tests are located in packages/tests/
- Use existing test patterns when adding new tests
- Run tests with the appropriate pnpm scripts

### Architecture Principles
- The toolkit supports multiple platforms: Visual Studio Code, Visual Studio, and CLI
- Authentication is handled centrally through the SDK
- Core functionality is shared via the fx-core package
- Extensions and integrations are modular (function-extension, spec-parser)

### AI/Agent Development Focus
- This toolkit is specifically designed for building conversational AI agents
- Supports Microsoft 365 integration, Teams apps, Office add-ins
- Templates include various copilot and agent scenarios
- Focus on developer experience with debugging, hot reload, and deployment tools

## When Contributing
- Follow the existing code patterns in each package
- Maintain backward compatibility when possible  
- Update documentation for any API changes
- Consider cross-platform compatibility (Windows, macOS, Linux)
- Test changes across different agent scenarios when applicable

## Package-Specific Context
- **SDK**: Focus on authentication, security, and developer utilities
- **CLI**: Command-line operations, CI/CD integration
- **VSCode Extension**: IDE integration, debugging, project management
- **Templates**: Scaffolding for different agent types and platforms
- **Spec Parser**: OpenAPI processing for API integration scenarios

## Build and Deployment
- Uses Azure Pipelines for CI/CD (.azure-pipelines/)
- Supports GitHub Actions workflows
- Lerna is used for version management and publishing
- Code coverage reporting via codecov

## Common Development Tasks
- **Setup**: `pnpm install` (installs all dependencies across workspaces)
- **Build**: `pnpm build` (builds all packages)
- **Development**: `pnpm watch` (parallel watch mode for all packages)
- **Clean**: `pnpm clean` (removes all node_modules)
- **Pre-commit**: Automated via husky with lint-staged

## Key Configuration Files
- `pnpm-workspace.yaml`: Workspace configuration
- `lerna.json`: Lerna configuration for version management
- `commitlint.config.js`: Commit message linting
- `eslint-local-rules.js`: Custom ESLint rules
- `.gitignore`: Includes build artifacts, dependencies
- `codecov.yml`: Code coverage configuration