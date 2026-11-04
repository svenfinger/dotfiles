# Repository standards

- Treat every repository as public unless explicitly instructed otherwise.
- A repository represents the intentional state of a project, not the process of developing it. Every contribution should be suitable for publication, even during active development.
- Never commit internal planning, implementation phases, progress reports, temporary notes, agent memory, handoff instructions, or private context.
- Do not assume information provided during a conversation or task is intended for publication.
- Keep temporary working information outside tracked repository files.
- Documentation should provide meaningful, durable information for users, contributors, or maintainers.
- Document technical decisions, architecture, workflows, and implementation details when they provide lasting value.
- Keep the README focused on the project overview, essential setup, and navigation to further documentation. Do not turn it into an exhaustive manual.
- Organize documentation by purpose using established conventions such as `CONTRIBUTING.md`, `RELEASE.md`, or focused files in `docs/`. Avoid unnecessary fragmentation and duplication.
- Do not create documentation merely to record completed work. Update existing documentation when appropriate.
- Write changelogs for users. Include meaningful product changes and omit internal milestones, implementation details, testing administration, and development-process commentary unless relevant to users.
- If information would be valuable to preserve but does not belong in the public repository, suggest documenting it separately and ask where it should go. Do not assume a particular external tool or location.
- Before proposing a commit, review the changes for internal, temporary, sensitive, redundant, or irrelevant content. Ensure all tracked files serve a legitimate purpose.

# Git operations

- Never commit, push, create tags, or publish releases without explicit user authorization.
- Explicit requests such as "commit", "push", "tag", or "release" authorize the corresponding operation within the requested scope.
- Authorization for one operation does not imply authorization for another. For example, permission to commit does not authorize pushing.
- Do not interpret task completion, successful tests, or an approved implementation as authorization to perform Git operations.
- When an operation requires authorization that has not been given, leave the changes ready and ask before proceeding.

# Commit messages

- Use short, direct, imperative commit messages.
- Capitalize the first word unless its official spelling starts with a lowercase letter.
- Don't use a trailing period.
- Preserve the official capitalization and spelling of names, brands, technologies, and acronyms.
- Use plain English without prefixes like feat:, fix:, or chore:.
- Include only words necessary to describe the change.
- Prefer a single line. Never add a body unless explicitly requested.
- Describe the change rather than its benefits or incidental implementation details.
- Never sacrifice clarity just to make a message shorter.

# Package management

- Prefer pnpm for new JavaScript and TypeScript projects.
- Use the existing package manager in established projects.
- Never migrate package managers unless explicitly requested.
