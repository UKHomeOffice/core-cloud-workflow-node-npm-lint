# Core Cloud Workflow Node npm lint

A GitHub Actions workflow for running npm lint on Node.js projects to identify and report code quality issues.

## Overview

This workflow automates code linting of Node.js projects within the core-cloud ecosystem, ensuring code quality standards are met.

## Features

- Automated npm lint scanning
- Code quality reporting

## Requirements

- Valid `package.json`, `package-lock.json` and valid `npm run lint` command

## Usage

Reference this workflow in your GitHub Actions pipeline:

```yaml
jobs:
    lint:
        uses: UKHomeOffice/core-cloud-workflow-node-npm-lint
```

## Inputs

| Input | Description | Required | Default |
|-------|-------------|----------|---------|
| `working_directory` | Directory to run npm lint in | No | `.` |
| `node_version` | Node version | No | `24` |


## Contributing

Follow core-cloud contribution guidelines when updating this workflow.
