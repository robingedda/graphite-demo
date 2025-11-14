# graphite-demo

A demo project showcasing Graphite workflow and Git collaboration patterns.

## Overview

This repository serves as a demonstration of modern Git workflows using Graphite for stack-based development.

## Getting Started

### Prerequisites

- Git
- [Graphite CLI](https://graphite.dev/) (optional, for enhanced workflow features)

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd graphite-demo
```

## Development Workflow

This project uses stacked branches to manage feature development. Each branch builds on top of the previous one, allowing for:

- Incremental code review
- Logical separation of changes
- Easier conflict resolution
- Better collaboration

### Basic Commands

```bash
# Create a new branch
git checkout -b feat/your-feature

# Make changes and commit
git add .
git commit -m "Your commit message"

# Push changes
git push origin feat/your-feature
```

### Using Graphite (Optional)

If you have Graphite CLI installed:

```bash
# Create a stacked branch
gt branch create feat/your-feature

# Navigate between branches in stack
gt up    # Move to parent branch
gt down  # Move to child branch

# Submit stack for review
gt submit
```

## Project Structure

```
.
├── .claude/          # Claude AI configuration
├── .git/            # Git repository data
├── .gitignore       # Git ignore patterns
└── README.md        # This file
```

## Contributing

1. Create a feature branch
2. Make your changes
3. Commit with clear, descriptive messages
4. Push your branch and create a pull request

## License

[Add your license here]

## Contact

[Add contact information or links]
