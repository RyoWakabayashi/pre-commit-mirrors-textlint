# textlint mirror

Mirror of textlint package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For textlint: see https://github.com/textlint/textlint

## Using textlint with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/RyoWakabayashi/pre-commit-mirrors-textlint
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: textlint
