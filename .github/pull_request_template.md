# [INT-#]

# Pull Request Type

- [ ] Feature
- [ ] Bugfix
- [ ] Refactor
- [ ] Documentation
- [ ] Release
- [ ] Other

# Purpose

The linked Jira ticket should capture most of the context. Here you should address the following:
- What and why were the code changes made?
- What changes should the reviewer focus on?
- Point out any code changes that require extra feedback.

# Notes

## Pull Requests

Before submitting a pull request, verify the working branch has backmerged all the latest changes. For example:
-  For a pull request that will merge a `working` branch into the `master`, the `working` branch __must__ have the latest `master` branch changes merged into its own branch before submitting a PR.

## Commit Messages

Commit messages, especially for **Squash and Merges**, should have the following format:
- For the commit message title/summary, `INT-#: Feature in Title Case (#PR)`
  - For example - `INT-1: Add Support for New Endpoints (#1)`
- For the commit message description/body, describe the commit in one or more sentences. This is optional and can often be omitted for trivial or small PRs. 
  - For example - `Added X support for Y and Z endpoints.`

## Merges

- For merges into `master` PRs, always **Squash and Merge**