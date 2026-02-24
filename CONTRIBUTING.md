# Contributing to Awesome AI Devtools (Multilingual)

Thank you for your interest in contributing! This document provides guidelines and instructions for contributing to this project.

## Table of Contents

- [Adding a New Tool](#adding-a-new-tool)
- [Improving Translations](#improving-translations)
- [Adding a New Language](#adding-a-new-language)
- [Reporting Issues](#reporting-issues)
- [Pull Request Process](#pull-request-process)

## Adding a New Tool

1. **Fork** this repository and create a new branch
2. Add the tool to the appropriate category in `i18n/README.en.md` (English version)
3. Follow this format:
   ```markdown
   - [Tool Name](https://tool-url.com/) — Brief description of the tool and its key features.
   ```
4. Make sure the tool:
   - Is AI-powered or AI-enhanced
   - Is relevant to software development
   - Has a working website or repository
   - Is not already listed
5. Submit a Pull Request

## Improving Translations

1. Navigate to the `i18n/` directory
2. Open the file for the language you want to improve (e.g., `README.zh.md` for Chinese)
3. Make your corrections while following these rules:
   - Keep tool names, URLs, and technical terms in English
   - Maintain all Markdown formatting
   - Ensure the language navigation header remains intact
4. Submit a Pull Request with a clear description of what was improved

## Adding a New Language

1. Copy `i18n/README.en.md` as your template
2. Name the file `README.{language-code}.md` (e.g., `README.ar.md` for Arabic)
3. Add the language navigation header at the top
4. Translate all section headers and descriptions
5. Keep tool names, URLs, and technical terms in English
6. Update the main `README.md` to include the new language
7. Update the language navigation header in all existing files
8. Submit a Pull Request

## Reporting Issues

- Use GitHub Issues to report bugs or suggest improvements
- Include as much detail as possible
- For translation issues, specify the language and the specific text that needs correction

## Pull Request Process

1. Ensure your changes follow the existing formatting conventions
2. Update the main `README.md` if necessary
3. Your PR will be reviewed by maintainers
4. Once approved, it will be merged into the main branch

## Code of Conduct

- Be respectful and constructive in all interactions
- Welcome newcomers and help them get started
- Focus on what is best for the community

Thank you for helping make AI developer tools accessible to developers worldwide!
