# TryHackMe Notes

This repository contains my personal notes and learning journey through the TryHackMe platform.

The goal is not to document walkthroughs, but to build a structured knowledge base focused on:
- Understanding core cybersecurity concepts
- Extracting reusable patterns and methodologies
- Connecting tools with the problems they solve

These notes evolve as I progress and revisit concepts.

---

## Repository Structure

This repo is organized into folders based on the type of content:
- **01_paths/**: Notes structured by the learning paths I’m following on TryHackMe (e.g., Pre Security).
- **02_methodology/**: Generalized concepts, procedures, patterns and analysis techniques that can be reused across machines and modules.
- **03_tools/**: A catalogue of tools with brief explanations of what they do and when to use them.
- **04_checklists/**: Short practical checklists for common enumeration and assessment tasks.

---

## How I Use This Repository

1. I use the folders in `01_paths/` to mirror the paths I follow on TryHackMe.
2. After completing a lesson or topic, I extract the key ideas into `02_methodology/` so I can reuse them later.
3. When a tool or command is mentioned repeatedly, I document it succinctly in `03_tools/`.
4. I build checklists in `04_checklists/` for quick reference during practice.

The focus is always on *why* something matters and *when* to use it, not just *what* the command is.

---

## 📌 Notes and Best Practices

- Avoid copying walkthroughs directly — focus on understanding.
- Organize content based on **idea + pattern + when to apply**, not just notes by date.
- Tags can be used within files for easier searching (e.g., `#web`, `#enumeration`, `#linux`).

Example of a short note entry:

```md
## Web Enumeration – Hidden Routes

**Purpose**  
To discover hidden or unlinked paths in a web application.

**Problem it solves**  
Identifies additional attack surfaces not visible through normal browsing.

**Tools / commands**  
- dirb <url>
```

## Disclaimer

All content in this repository is for educational purposes only and based on legal, controlled environments such as the TryHackMe platform. Do not use this knowledge for unauthorized testing.

## License

This project is licensed under the MIT License.
