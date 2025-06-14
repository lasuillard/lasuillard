---
mode: agent
description: Generate a professional resume from files in this repository.
tools: ['codebase', 'fetch', 'filesystem', 'get_me', 'githubRepo', 'search', 'server-time']
---

## Objective

Generate a concise, professional resume for **lasuillard** using the latest data from the `/my` directory.

## Data Sources

- Use only files in `/my` for profile, skills, experience, and education.
- For missing contact info, supplement with `get_me` tool (GitHub profile).

## Resume Sections

Include the following sections in the resume:
- Contact: Email, GitHub, LinkedIn, Blog
- Self Introduction
- Skills
- Experience
- Education

Omit Projects section; instead, suggest readers visit the GitHub profile for project details.

## Guidelines

- Keep the resume clear, brief, and well-structured.
- Exclude sensitive/private data unless explicitly requested.
- Omit any section with no data.
- Format in Markdown for easy sharing.
- Reflect accurate experience level; do not exaggerate.
- Use the following emojis for section titles:
  - Contact: 📞
  - Self Introduction: 👋
  - Skills: 🛠️
    - Use badges instead of plain text for skills.
  - Experience: 💼
  - Education: 🎓

## Output

- Output only the complete resume in Markdown.
- Save as:
  - `/RESUME.ko.md` (Korean)
    - Be mindful of the Korean language and cultural nuances.
    - Choose humble and respectful language.
    - Avoid exaggeration or boasting.
  - `/RESUME.en.md` (English)
- Do not change other files or the structure of existing resumes unless asked.
- At the end, add a horizontal line and center:

  > _Updated with assist of AI at {CURRENT_TIME}_

  Replace `{CURRENT_TIME}` with the UTC time from `server-time`.
