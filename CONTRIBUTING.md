# Contributing to open-forge

Thanks for your interest in contributing to open-forge. This project aims to make self-hosting open-source applications easier through reusable, verified deployment recipes and agent-friendly documentation.

## Ways to contribute

You can help by:

- Improving existing deployment recipes.
- Adding notes about provider-specific setup steps, gotchas, or recovery paths.
- Improving documentation for supported agent platforms.
- Reporting bugs with clear reproduction steps.
- Suggesting new recipes or recipe metadata improvements.

## Before opening a pull request

Please try to keep changes focused and easy to review.

1. Check the existing documentation and recipes for similar work.
2. Prefer small pull requests over large mixed changes.
3. Include enough context for reviewers to understand why the change is useful.
4. Avoid committing secrets, tokens, credentials, or environment-specific private values.

## Recipe contribution checklist

When adding or updating a deployment recipe, consider including:

- Supported platform or provider.
- Required tools or CLIs.
- Required environment variables or secret references.
- DNS, TLS, storage, backup, and email notes when relevant.
- Known limitations or provider-specific caveats.
- A short validation step to confirm the deployment works.

## Documentation style

- Use clear headings and short steps.
- Prefer copyable commands when possible.
- Explain assumptions, especially around infrastructure, credentials, and domains.
- Keep safety-sensitive instructions explicit, especially around credential handling.

## Pull request description

A helpful pull request usually includes:

- What changed.
- Why the change is needed.
- How it was tested or reviewed.
- Any follow-up work that remains.

Thank you for helping improve open-forge.
