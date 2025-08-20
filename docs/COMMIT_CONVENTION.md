# Commit Convention

This project follows the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification to ensure a consistent and readable commit history.

## Format

Each commit message consists of a **header**, a **body**, and a **footer**.

```
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

### Type

Must be one of the following:

*   **feat**: A new feature or DApp submission.
*   **fix**: A bug fix.
*   **docs**: Documentation only changes.
*   **style**: Changes that do not affect the meaning of the code (white-space, formatting, etc).
*   **refactor**: A code change that neither fixes a bug nor adds a feature.
*   **perf**: A code change that improves performance.
*   **test**: Adding missing tests or correcting existing tests.
*   **build**: Changes that affect the build system or external dependencies.
*   **ci**: Changes to our CI configuration files and scripts.
*   **chore**: Other changes that don't modify src or test files.

### Scope

The scope provides contextual information. It must be one of the following:

*   **dapp**: Changes related to a DApp submission (e.g., adding or updating a `dapp.json` file).
*   **workflow**: Changes to a GitHub Actions workflow.
*   **docs**: Changes to documentation files.
*   **repo**: General repository maintenance or configuration.
*   **ci**: CI/CD related changes.

### Subject

The subject contains a succinct description of the change:

*   Use the imperative, present tense: "change" not "changed" nor "changes".
*   Don't capitalize the first letter.
*   No dot (.) at the end.
