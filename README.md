# GAISE 2026-03-9

A Node.js web application with a GitHub Actions CI workflow.

## GitHub Actions

This repository includes the [GitHub Actions quickstart workflow](https://docs.github.com/en/actions/get-started/quickstart) at `.github/workflows/github-actions-demo.yml`.

The workflow runs on every `push` and:

1. Prints the event type, OS, branch name, and repository name.
2. Checks out the repository code.
3. Lists all files in the workspace.
4. Reports the final job status.

## Project Structure

```
.github/
  workflows/
    github-actions-demo.yml   # GitHub Actions demo workflow
public/
  index.html                  # Static front-end
server.js                     # Node.js server entry point
package.json                  # Project metadata and dependencies
```

## Getting Started

```bash
npm install
node server.js
```
