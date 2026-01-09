# Contribution Guidelines

## Repository Context

This is Xe's GitHub profile README repository. It displays on the GitHub profile at https://github.com/Xe and contains:

- Profile bio and contact information
- Star history chart
- Social media links
- Recent blog posts (auto-updated)
- Sponsor list (auto-updated)
- Contact methods

## Code Quality & Security

### Commit Guidelines

Commit messages follow **Conventional Commits** format:

```text
[optional scope]: <description>
[optional body]
[optional footer(s)]
```

**Types**: `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `test`, `build`, `ci`, `chore`, `revert`

- Add `!` after type/scope for breaking changes or include `BREAKING CHANGE:` in the footer
- Keep descriptions concise, imperative, lowercase, and without a trailing period
- Reference issues/PRs in the footer when applicable

### Attribution Requirements

AI agents must disclose what tool and model they are using in the "Assisted-by" commit footer:

```text
Assisted-by: [Model Name] via [Tool Name]
```

Example:

```text
Assisted-by: GLM 4.6 via Claude Code
```

## Common Tasks

### Updating Profile Information

To update your profile bio, pronouns, or contact links, edit the appropriate sections in `README.md`.

### Adding Social Links

Add new social media links under the "Other Places on the Internet" section following the existing format.

### Blog Posts

Blog posts are automatically updated by a workflow. Do not manually edit the content between `<!-- BLOG-POST-LIST:START -->` and `<!-- BLOG-POST-LIST:END -->`.

### Sponsors

Sponsors are automatically updated by a workflow. Do not manually edit the content between `<!-- sponsors -->` markers.

## Security Best Practices

- Secrets never belong in the repo; use GitHub Secrets for any workflow credentials
- Be cautious when adding images or external links
- Review and understand any workflows before enabling them

## File Maintenance

- This file should remain clear of test messages, temporary comments, or non-essential content
- Keep documentation concise and production-ready

## Pull Request Requirements

- Include a clear description of changes
- For profile updates, consider if changes should be made directly to the main branch
- Verify that the README renders correctly on GitHub profile preview
