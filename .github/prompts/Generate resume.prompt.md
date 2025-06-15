---
mode: agent
description: Generate a professional resume from various data sources.
tools: ['codebase', 'fetch', 'get_me', 'githubRepo', 'search', 'server-time']
---

## Objective

Generate a concise, professional resume for **lasuillard** using the latest data from the data sources described below.

## Data Sources

- Use only files in `/my` for profile, skills, experience, and education.
- Enrich user information at beginning with `get_me` tool (GitHub profile).

## Resume Sections

Include the following sections in the resume:
- Contact: Email, GitHub, LinkedIn, Blog; these information may be found in the user's GitHub profile.
  - Present all contact information as badges with appropriate labels (e.g., "LinkedIn" for LinkedIn badge).
- Self Introduction
- Skills
  - Only include skills/technologies used in professional roles, not from personal projects.
  - Organize skills into appropriate categories:
    - Programming Languages
    - Frameworks & Libraries
    - Cloud & Infrastructure
    - Databases
    - Development Tools
  - Use badges instead of plain text for all skills.
- Experience
  - List professional experience with responsibilities and technologies used.
  - Include technology badges under each experience entry.
  - Ensure these technology badges match what appears in the Skills section.
- Education
- Use the following emojis for section titles:
  - Contact: 📞
  - Self Introduction: 👋
  - Skills: 🛠️
  - Experience: 💼
  - Education: 🎓

Omit Projects section for now.

## Guidelines

- Keep the resume clear, brief, and well-structured.
- Exclude sensitive/private data unless explicitly requested.
- Omit any section with no data.
- Format in Markdown for easy sharing.
- Reflect accurate experience level; do not exaggerate.
- Only include technologies that appear in professional experience; do not include technologies used only in personal projects.
- Ensure consistency between the Skills section and the technologies mentioned in the Experience section.
- Use badges for all technologies, including those in experience descriptions.

## Output

- Output only the complete resume in Markdown.
- Save as:
  - `/RESUME.ko.md` (Korean)
    - Be mindful of the Korean language and cultural nuances.
    - Choose humble and respectful language.
    - Avoid exaggeration or boasting.
    - Elaborate on overall description of each section.
  - `/RESUME.en.md` (English)
- NEVER change other files.
- Do not modify the structure of existing resumes unless asked.
- If any changes are made, at the end, add a horizontal line and center:

  > _Updated with assist of AI at {CURRENT_TIME}_

  Replace `{CURRENT_TIME}` with the UTC time from `server-time`.
