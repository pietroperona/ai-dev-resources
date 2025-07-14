# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a curated link repository for AI developers containing repositories, tools, resources, and reports. It serves as a centralized hub for AI development resources organized by category.

## Repository Structure

The repository is organized into 6 main categories, each containing dedicated README files in both English and Italian:

- **fundamentals/**: Core AI and LLM concepts, focusing on Hands-On Large Language Models
- **agents/**: AI agent development resources with 45+ implementations using LangChain, LangGraph, PydanticAI
- **prompt-engineering/**: Complete guides for prompt optimization and techniques
- **production/**: Production deployment strategies for AI agents and systems
- **tutorials/**: Learning resources including 90+ free courses and interview preparation
- **tools/**: Curated tools and utilities for AI development

## Multilingual Support

The repository maintains content in multiple languages:
- **Primary language**: English (README.md files)
- **Secondary language**: Italian (README_IT.md files)
- **Root README**: Available in both languages with language selector

Each category folder contains:
- `README.md` - English version
- `README_IT.md` - Italian version

## Content Management

### Adding New Resources
When adding new resources (repositories, tools, resources, reports):
1. Determine the appropriate category based on the resource type
2. **ALWAYS update BOTH language versions simultaneously**:
   - Create/update `README.md` (English) first
   - Create/update `README_IT.md` (Italian) with equivalent content
   - Add links under appropriate sections (Repositories, Tools, Resources, Reports)
   - Include brief descriptions for each link
   - Focus on practical utility for developers

### Documentation Style
- Primary documentation is in English, with Italian translations provided
- Each category README follows sections: Repositories, Tools, Resources, Reports & Research
- Keep descriptions concise and focused on practical utility
- Include direct links with brief explanations
- Maintain consistency between language versions

### CRITICAL MULTILINGUAL WORKFLOW
**MANDATORY**: When making ANY changes to documentation in this repository:

1. **Always work on both languages**: Never update only one language version
2. **Update sequence**: 
   - First: Update English version (README.md)
   - Second: Update Italian version (README_IT.md) with equivalent content
3. **Maintain parity**: Both versions must contain the same:
   - External repository links
   - Technical information
   - Section structure
   - Formatting and emoji usage
4. **Language selector**: Ensure all files have the language selector:
   ```markdown
   **🌐 Language Versions:** [English](README.md) | [Italiano](README_IT.md)
   ```
5. **Commit together**: Always include both language versions in the same commit

### Repository Maintenance
- This is a documentation-only repository with no build processes, tests, or deployments
- Primary maintenance involves updating links, adding new resources, and improving documentation
- No code compilation or testing required - content is purely informational

## Content Philosophy

This repository curates external links rather than hosting original content. The focus is on organizing and presenting valuable AI development resources (repositories, tools, resources, reports) in a structured, accessible way for the international developer community, with particular attention to English and Italian-speaking developers.