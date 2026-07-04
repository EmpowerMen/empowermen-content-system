# Courses

This folder contains foundational course materials organized by course.

## Purpose

The `/courses/` directory serves as:

1. **Content Repository** - Complete course materials (workbooks, transcripts, exercises)
2. **AI Agent Knowledge Base** - Structured data that AI agents can query and cite
3. **Email & Marketing Reference** - Source material for content creation workflows
4. **Citation Library** - Authoritative sources for course-based content

## Current Courses

### Sovereign Man: A Shadow Work Online Course

- **Location:** `sovereign-man-shadow-work/`
- **Primary Module:** King Within
- **Purpose:** Comprehensive shadow work and archetypal psychology course
- **See:** [sovereign-man-shadow-work/README.md](sovereign-man-shadow-work/README.md)

## File Structure Overview

Each course follows this pattern:

```
{course-name}/
├── README.md                    # Course overview and index
├── INDEX.json                   # Searchable index of modules
├── course-metadata.json         # Course metadata, URLs, CTAs
└── modules/
    ├── {module-name}/
    │   ├── README.md
    │   ├── workbook.md
    │   ├── aims-and-practices.md
    │   ├── movie-assignments.md
    │   └── video-transcripts/
    │       ├── chapter-1.md
    │       ├── chapter-2.md
    │       └── ...
    └── {other-modules}/
```

## How to Use This Folder

### For Content Creators

1. Find the course module you need
2. Reference workbook, transcripts, or aims-and-practices files
3. Use content as source material for marketing emails, blogs, etc.
4. Always cite the course module

### For AI Agents

1. Check `INDEX.json` for available modules and topics
2. Reference `course-metadata.json` for course-level CTAs and URLs
3. Pull content from specific files (workbook, transcripts, etc.)
4. Maintain proper citation format

## Citation Standards

### Citing Course Materials

**Format:**
```
> "[Quote or concept from course]"
> — The Sovereign Man: A Shadow Work Online Course, [Module Name]
```

**Example:**
```
> "The King archetype ensures other archetypal energies are channeled in constructive and ethical ways."
> — The Sovereign Man: A Shadow Work Online Course, King Within Module
```

### When to Cite

**Always cite when:**
- Using direct quotes from course materials
- Referencing specific exercises or workbook content
- Discussing course frameworks or concepts
- Creating marketing content based on course material

## Adding New Courses

1. Create a new folder: `/courses/{course-name}/`
2. Follow the structure pattern above
3. Include a README.md with course overview
4. Create INDEX.json for searchability
5. Add course-metadata.json with URLs and CTAs
6. Update this README.md with the new course
7. Update `/governance/glossary.json` under `courses` section

## Relationship to Other Folders

### `/foundations/courses/` vs `/foundations/robert-moore-lectures/`

- **Lectures** = Foundational psychological theory and teaching
- **Courses** = Applied learning programs based on theory

Courses reference and build upon the lectures.

### `/foundations/courses/` vs `/skills/marketing/writing-course-promotion-emails/`

- **Courses** = Knowledge base and source material
- **Skills** = Workflow for creating marketing content from course material

---

**Last Updated:** [Current Date]
**Maintained By:** EmpowerMen Content Team
