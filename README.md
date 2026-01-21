# Technical Writing Sample: Workflow Tracker Guide

This repository contains a professional documentation sample for a **Technical Writing Workflow Tracker**. It demonstrates high-level technical writing proficiency, including the ability to simplify complex processes and implement a **Docs-as-Code** workflow.

## Quick Links
* **[Live Rendered Documentation](https://github.com/alonzo-brown/TechWriting)**
* **[Source AsciiDoc File](Sample-AsciiDoc.adoc)**

## Project Objective
The goal of this sample is to provide clear, task-oriented instructions for a team-based workflow application. It transforms a tasks checklist into a navigable, user-centric guide that prioritizes clarity and actionability.

## Technical Decisions

### Why AsciiDoc?
While Markdown is common, I chose **AsciiDoc** for this project because it is purpose-built for technical documentation. Key features utilized include:
* **Custom Attributes:** Used for product naming (`:app-name:`) to ensure consistency and easy global updates.
* **Refined Admonitions:** Implementation of `[NOTE]`, `[TIP]`, and `[IMPORTANT]` blocks to provide visual cues without breaking the narrative flow.
* **Complex Tables:** Utilizing advanced column formatting that Markdown cannot natively handle.
* **Document Attributes:** Automatic generation of a Table of Contents (`:toc:`) and section numbering (`:sectnums:`) for better navigability.

### Docs-as-Code Automation
This project uses **GitHub Actions** to automate the publishing process. Every commit to the `main` branch triggers a build container that:
1. Validates the AsciiDoc syntax.
2. Renders the content into a clean, responsive HTML5 file.
3. Deploys the result to GitHub Pages.

---

## Accessibility & Standards
I have prioritized accessibility by following these standards:
* **Logical Hierarchy:** Strict use of sequential heading levels for screen reader compatibility.
* **Semantic Web:** Utilizing native AsciiDoc elements rather than visual hacks to ensure the underlying HTML is clean.
* **Clarity:** Adhering to the Microsoft Writing Style Guide for UI elements and active voice instructions.

## Repository Structure
* `Sample-AsciiDoc.adoc`: The primary documentation source.
* `images/`: Contains all visual assets and screenshots.
* `.github/workflows/`: The CI/CD pipeline configuration for automated rendering.
