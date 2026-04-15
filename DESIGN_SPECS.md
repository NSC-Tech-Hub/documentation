# Technical Design Specifications

To ensure the "Vetting Loop" remains efficient, all assets must meet the following criteria before being merged into production repositories.

## 📁 File Naming Conventions
All files must follow the kebab-case format:
* **Format:** `[project]-[asset-type]-[description]-[version].[ext]`
* **Example:** `b2t-logo-header-v01.png`
* *Reasoning:* Prevents version confusion and ensures clean indexing for the RAG system.

## 🖼 Asset Requirements
* **Web Graphics:** Must be exported as **WebP** (for performance) or **SVG** (for logos/icons).
* **Resolution:** 72 DPI for web; 300 DPI for print-ready assets.
* **Color Space:** RGB for all digital-first assets.

## 📝 Code Standards (For AD Students)
* **Commit Messages:** Must be descriptive and link to a specific GitHub Issue ID.
* **Branching:** No direct pushes to `main`. All code must go through a Pull Request (PR) and be vetted by the TPM or a designated Peer Reviewer.