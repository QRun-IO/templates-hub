# QRun Templates Hub

Central registry of project templates for `qctl qqq init`.

## Usage

```bash
# List available templates
qctl qqq list

# Initialize a new project from a template
qctl qqq init new-qqq-application ./my-project
```

## Templates

| ID | Name | Description |
|----|------|-------------|
| new-qqq-application | QQQ Application Starter | Complete QQQ application with entities, database, and dashboard |

## Adding Templates

1. Create a template repository with a `template.yaml` manifest
2. Add the template entry to `templates.yaml` in this repo
3. Submit a pull request
