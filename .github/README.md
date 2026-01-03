# .github - GitHub Configuration

## GitHub Actions

Workflow templates in `.github/workflows/`:

- `ci.yml` - Continuous Integration
- `cd.yml` - Continuous Deployment
- `test.yml` - Test automation
- `security.yml` - Security scanning

## Issue Templates

Templates in `.github/ISSUE_TEMPLATE/`:

- `bug_report.md`
- `feature_request.md`
- `question.md`

## Pull Request Template

`.github/PULL_REQUEST_TEMPLATE.md`:

```markdown
## Description
<!-- Describe your changes -->

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Breaking change
- [ ] Documentation update

## Testing
- [ ] Tests added/updated
- [ ] All tests passing

## Checklist
- [ ] Code follows project patterns
- [ ] Self-review completed
- [ ] Documentation updated
```

## Dependabot

Auto-dependency updates in `.github/dependabot.yml`:

```yaml
version: 2
updates:
  - package-ecosystem: "npm"
    directory: "/"
    schedule:
      interval: "weekly"
```
