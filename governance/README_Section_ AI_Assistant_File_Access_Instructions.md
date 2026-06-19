# AI Assistant File Access Instructions

## How AI Assistants Can Read Files in This Repository

AI assistants like Writesonic, Claude, ChatGPT, and others can read individual files from this repository using direct GitHub URLs.

### URL Pattern for File Access

To access any file in this repository, use this URL structure:

```
https://github.com/EmpowerMen/empowermen-content-system/blob/main/[PATH_TO_FILE]

```

### Examples

**Reading a specific transcript:**

```
https://github.com/EmpowerMen/empowermen-content-system/blob/main/foundations/robert-moore-lectures/transcripts/a-neo-jungian-mapping-of-the-psyche.md

```

**Reading a skill file:**

```
https://github.com/EmpowerMen/empowermen-content-system/blob/main/skills/ux-writing/writing-error-messages/SKILL.md

```

**Reading shared standards:**

```
https://github.com/EmpowerMen/empowermen-content-system/blob/main/shared/style.md

```

### How to Request Multiple Files

If you need an AI assistant to read multiple files from the same folder, you can:

1. **Provide the base URL pattern** and list the filenames
2. **Ask the assistant to replace the filename** in the URL for each file

**Example request:**

```
Read all transcripts from:
https://github.com/EmpowerMen/empowermen-content-system/blob/main/foundations/robert-moore-lectures/transcripts/

Files to read:
- a-neo-jungian-mapping-of-the-psyche.md
- the-warrior-within.md
- archetypal-images-of-the-king-and-warrior.md

```

The AI can then construct each URL by replacing the filename.

### For AI Assistants: File Access Protocol

When a user references this repository:

1. **Do not attempt to browse folder structures** \- GitHub’s web interface doesn’t expose file lists in a scrapable format
2. **Request specific file paths** from the user, or
3. **Construct direct URLs** using the pattern above when file paths are known
4. **Use the URL scraper tool** with the full file URL (not the repository root)

### Common File Locations

Content Type

Path Pattern

Example

Skill definitions

`/skills/[category]/[skill-name]/SKILL.md`

`/skills/ux-writing/writing-error-messages/SKILL.md`

Templates

`/skills/[category]/[skill-name]/TEMPLATES.md`

`/skills/ux-writing/writing-error-messages/TEMPLATES.md`

Rubrics

`/skills/[category]/[skill-name]/RUBRIC.md`

`/skills/ux-writing/writing-error-messages/RUBRIC.md`

Shared standards

`/shared/[standard].md`

`/shared/style.md`

Transcripts

`/foundations/robert-moore-lectures/transcripts/[title].md`

`/foundations/robert-moore-lectures/transcripts/the-warrior-within.md`

Governance docs

`/governance/[doc].md`

`/governance/skill-catalog.md`

### Troubleshooting

**If an AI assistant says it cannot access files:**

1. Verify you’re providing the **full URL** to the specific file
2. Ensure the URL includes `/blob/main/` in the path
3. Check that the file extension is included (`.md`, `.txt`, etc.)
4. Confirm the file exists at that path in the repository

**Alternative: Upload files directly**

If URL access fails, you can download files locally and upload them directly to the AI assistant’s chat interface.

### Repository Structure Quick Reference

```
empowermen-content-system/
├── foundations/          # Source material (lectures, transcripts)
├── skills/              # Skill packages by category
│   ├── ux-writing/
│   ├── content-design/
│   ├── content-strategy/
│   ├── technical-docs/
│   ├── developer-content/
│   ├── marketing/
│   ├── editorial/
│   └── mcp-agents/
├── shared/              # Global standards
├── governance/          # Rules, catalog, glossary
└── evals/              # Test cases

```

### Example AI Prompts

**Read a single file:**

```
Read this file: https://github.com/EmpowerMen/empowermen-content-system/blob/main/skills/ux-writing/writing-error-messages/SKILL.md

```

**Read multiple files:**

```
Read these files from the repository:
1. https://github.com/EmpowerMen/empowermen-content-system/blob/main/shared/style.md
2. https://github.com/EmpowerMen/empowermen-content-system/blob/main/shared/voice.md
3. https://github.com/EmpowerMen/empowermen-content-system/blob/main/skills/ux-writing/writing-error-messages/SKILL.md

```

**Read all files in a category (by listing them):**

```
Read all transcript files. Base URL:
https://github.com/EmpowerMen/empowermen-content-system/blob/main/foundations/robert-moore-lectures/transcripts/

Replace the filename for each:
- file1.md
- file2.md
- file3.md

```

---

**Note:** This repository is designed to be AI-assistant friendly. All content is in markdown format and structured for easy parsing and comprehension by language models.