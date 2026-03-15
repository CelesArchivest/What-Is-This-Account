# 🤝 Contributing to The Celes Archive

Thank you for helping us preserve open-source knowledge! To keep the archive clean and functional, please follow these guidelines when converting documentation to the `.celes` format.

## 🛠️ The Conversion Process

We focus on "Documentation-Only" forks. If you find a project worth archiving:

1.  **Fork the Project:** Fork the target repository to this organization.
2.  **Prune the Code:** Remove all source code, binaries, and build files. Keep only the documentation (Markdown, HTML, or Wiki files).
3.  **Translate to .celes:** Convert the core documentation into a `.celes` file.

## 📝 .celes File Standards

To ensure compatibility with our **Python App** and **Browser Extension**, follow these structural rules:

* **Metadata Header:** Every file should start with a clear header including the original project name, original URL, and the date archived.
* **Logical Nesting:** Use clear delimiters to separate sections. Since `.celes` is designed for both human and machine readability, keep your hierarchy consistent.
* **Media Handling:** If the original docs use images, ensure they are either embedded or linked to a permanent archive (like Wayback Machine) rather than a volatile live URL.
* **Licensing:** Always include a reference to the original project's license within the `.celes` file to respect the original authors.

## 📂 Submission Guidelines

1.  **File Naming:** Use lowercase with hyphens (e.g., `react-v18-docs.celes`).
2.  **Directory Structure:** Place files in the `/archive` folder, categorized by the project's primary purpose (e.g., `/archive/web-frameworks/`).
3.  **Pull Requests:** When submitting a PR, briefly explain why this project is a high priority for archiving (e.g., "The project is no longer maintained" or "The original website is down").

---
*By contributing, you agree that your work will be distributed under the **Server-Lab Open-Control License (SOCL) 1.0** and that you have the right to share the documentation you are archiving.*
