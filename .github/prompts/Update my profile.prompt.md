---
mode: agent
description: Update the root README.md for the GitHub profile.
tools: ['codebase', 'fetch', 'githubRepo', 'memory', 'server-time', 'search_repositories', 'search_users']
---

## Goal

Update the root `README.md` using information from files in `/my`.

## Data Sources

- **Use only information from files in `/my` within this repository.**
- **Do not include sensitive or private information** unless explicitly provided or requested by the user.
- Proactively use the provided tools to search for necessary information from various sources.
- Ignore repositories with insufficient content or those that do not contribute to the resume.

## Profile Section Instructions

- **This is not a resume.** Only include information suitable for a public GitHub profile:
  - Do **not** include work experience details, education, or certificates.
  - **Include a section titled "I'm working on"** to highlight current projects or interests. Use the `search_repositories` tool to find relevant repositories.
  - **Do not include** content already displayed by GitHub, such as:
    - User's name
    - Profile picture
    - Contact information
    - Contributions graph

## Content Guidelines

- **Summarize and present** the user's bio, skills, and self-description in clear, engaging Markdown.
- **Do not add or remove sections** unless explicitly requested by the user.
- Ensure the `README.md` is suitable for public display as a GitHub profile.

## Inspiration

- You may reference the following sources for inspiration and examples:
  - [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme)
- **Do not update the content with inspiration from these sources** unless explicitly requested by the user.
  - If inspiration is requested, first suggest the changes with examples and wait for user confirmation before making any changes.

## Output

- **Output only the complete, updated `README.md` content.**
- **Do not modify any other files in the repository.**
- At the end, add a horizontal line and the phrase (in Markdown format), center-aligned:

  > _Updated with assist of AI at {CURRENT_TIME}_

  Replace `{CURRENT_TIME}` with the current time in UTC format using the `server-time` tool.
