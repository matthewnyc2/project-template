# Project Template

A comprehensive template repository for new software projects with AI coding agent integration.

## 🎯 Quick Start

1. Click **"Use this template"** above
2. Name your new repository
3. Clone it locally
4. Start building!

## 📁 Directory Structure

```
project-template/
├── frontend/          # Frontend application (React, Vue, etc.)
├── backend/           # Backend API (FastAPI, Express, etc.)
├── docs/              # Documentation
├── scripts/           # Utility scripts
├── screencaps/        # Screen recordings and demos
├── tasks/             # Task tracking and management
├── tests/             # Test suites
├── database/          # Database schemas and migrations
├── .amazonq/          # Amazon Q configuration
├── .clinerules/       # Cline/Cursor AI rules
├── .code/             # .code AI configuration
├── .codex/            # OpenAI Codex configuration
├── .cursor/           # Cursor AI configuration
├── .gemini/           # Gemini AI configuration
├── .github/           # GitHub workflows and templates
├── .opencode/         # OpenCode AI configuration
├── .qwen/             # Qwen AI configuration
├── .claude/           # Claude Code configuration
├── .kilocode/         # Kilocode AI configuration
└── tools/             # Additional tools and utilities
```

## 🤖 AI Coding Agent Integration

This template is pre-configured for multiple AI coding assistants:

### Supported Agents
- **Claude Code** (`.claude/`)
- **Cursor** (`.cursor/`)
- **Cline** (`.clinerules/`)
- **GitHub Copilot** (`.github/`)
- **Gemini** (`.gemini/`)
- **Amazon Q** (`.amazonq/`)
- **Qwen** (`.qwen/`)
- **OpenAI Codex** (`.codex/`)
- **Kilocode** (`.kilocode/`)
- **OpenCode** (`.opencode/`)
- **.code** (`.code/`)

## 📋 Getting Started Checklist

- [ ] Configure AI agent(s) of choice
- [ ] Set up frontend framework
- [ ] Set up backend framework
- [ ] Configure database
- [ ] Set up testing framework
- [ ] Configure GitHub Actions CI/CD
- [ ] Set up documentation
- [ ] Configure development environment

## 🔧 Configuration

### Environment Variables

Copy `.env.example` to `.env` and configure:

```bash
cp .env.example .env
```

### AI Agent Setup

Each AI agent directory contains configuration files:

```bash
# Example for Claude Code
.claude/
├── commands.json       # Custom commands
├── settings.json       # Agent settings
└── skills/             # Custom skills
```

## 📚 Documentation

See `docs/` for:
- [Setup Guide](docs/SETUP.md)
- [AI Agent Configuration](docs/AI_AGENTS.md)
- [Development Workflow](docs/WORKFLOW.md)

## 🧪 Testing

```bash
# Run all tests
npm test                # JavaScript
pytest                  # Python

# Run specific test suite
npm test -- unit
pytest tests/unit/
```

## 🚀 Deployment

```bash
# Deploy frontend
cd frontend && npm run deploy

# Deploy backend
cd backend && npm run deploy
```

## 🤝 Contributing

This is a template repository. Fork and customize for your needs!

## 📄 License

MIT License - feel free to use this template for any project.
