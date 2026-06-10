---
description: "Instructions to use whenever creating or editing assignment README.md assignment files to ensure consistency and clarity for students."
applyTo: "assignments/**/README.md"
template: "../../../../templates/assignment-template.md"
---

# Assignment Markdown Structure Guidelines

All assignment README.md files must follow the exact structure and icon usage found in the repository template: [templates/assignment-template.md](../../../../templates/assignment-template.md).

Required file and location:
- The assignment must be created as a `README.md` file inside an `assignments/<assignment-name>/` folder (for example: `assignments/python-basics/README.md`).

Required headings (use exact text and emoji from the template):
- `# 📘 Assignment: [Assignment Title]`
- `## 🎯 Objective`
- `## 📝 Tasks`
- `### 🛠️  [Task Title]`
- `#### Description`
- `#### Requirements`

Section guidance:
- **Objective**: 1–2 concise sentences describing what the student will build or learn.
- **Tasks**: Provide one or more task blocks. For each task include a short title, a `Description` that explains the work, and a `Requirements` list with specific, testable outcomes.
- Include example input/output or code blocks when they clarify expected behavior.

Template usage rules:
- Use the file at [templates/assignment-template.md](../../../../templates/assignment-template.md) as the canonical structure and copy its icons and headings exactly.
- Do not remove required sections or change icon text.
- Keep language simple and active to be accessible to beginners.

Pre-publish checklist:
- Ensure the file is named `README.md` and located under `assignments/<name>/`.
- Verify all headings and emoji match the template exactly.
- Confirm `Requirements` are specific and measurable.
- Add starter code or assets in the same assignment folder when needed (e.g., `starter-code.py`, `data.csv`).

Do not add extra sections unless there is a clear reason and it is documented in the assignment header.