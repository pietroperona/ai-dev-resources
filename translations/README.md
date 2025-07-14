# Translations 🌍

This directory contains resources for managing translations and supporting multiple languages in the AI Development Resources repository.

## Current Language Support

- **English** - Primary language (README.md files)
- **Italian** - Secondary language (README_IT.md files)

## Future Language Support

The repository is designed to easily accommodate additional languages. For each new language:

1. Create `README_[LANG].md` files in each category directory
2. Update the language selector in the main README files
3. Follow the same structure and content organization

## Translation Guidelines

### File Naming Convention
- English: `README.md` (primary)
- Italian: `README_IT.md`
- Future languages: `README_[ISO_LANG_CODE].md`

### Content Structure
All language versions should maintain:
- Same section structure
- Same external repository links
- Consistent formatting and emoji usage
- Equivalent technical information

### Language Selector Format
```markdown
**🌐 Language Versions:** [English](README.md) | [Italiano](README_IT.md) | [New Language](README_XX.md)
```

## Adding New Languages

To add a new language:

1. **Create translation files** for each category:
   - `fundamentals/README_XX.md`
   - `agents/README_XX.md`
   - `prompt-engineering/README_XX.md`
   - `production/README_XX.md`
   - `tutorials/README_XX.md`
   - `tools/README_XX.md`

2. **Create main README** translation:
   - `README_XX.md` in root directory

3. **Update language selectors** in all existing files

4. **Update CLAUDE.md** to reflect new language support

## Translation Status

- ✅ English (complete)
- ✅ Italian (complete)
- ⏳ Other languages (awaiting contribution)

## Contributing Translations

Translations are welcome! Please ensure:
- Technical accuracy is maintained
- Links and repository references remain unchanged
- Formatting and structure match existing versions
- Language selector is updated in all relevant files