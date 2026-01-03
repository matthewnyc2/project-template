# .claude - Claude Code Configuration

## Custom Commands

Add custom slash commands here:

```json
{
  "commands": {
    "setup": {
      "description": "Set up the development environment",
      "prompt": "# Setup Instructions\n\nHelp me set up this project's development environment.\n\n## Steps\n1. Check for required tools\n2. Install dependencies\n3. Configure environment\n4. Run initial setup"
    },
    "test": {
      "description": "Run tests with coverage",
      "prompt": "# Test Runner\n\nRun the test suite and provide coverage report.\n\n## Command\n```bash\nnpm test --coverage\n```"
    },
    "docs": {
      "description": "Generate documentation",
      "prompt": "# Documentation Generator\n\nGenerate up-to-date documentation for this project.\n\n## Areas\n- API documentation\n- Architecture docs\n- Usage guides"
    }
  }
}
```

## Settings

```json
{
  "permissions": {
    "allow": [
      "Bash(npm:*)",
      "Bash(pip:*)",
      "Bash(python:*)",
      "Read",
      "Write",
      "Edit"
    ]
  }
}
```

## Skills

Custom skills for Claude Code:

- **setup-skill**: Project setup automation
- **test-skill**: Test generation and execution
- **docs-skill**: Documentation generation
