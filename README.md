# Bibliography Skills Marketplace

Curated bibliography extraction and management tools for Claude Code.

## Installation

Add this marketplace to Claude Code:

```bash
/plugin marketplace add fangrh/bibliography-skills-marketplace
```

## Available Plugins

### Bibliography Skills (Core)

**Description:** Zotero-like bibliography extraction and management suite with DOI/URL extraction, LaTeX preview generation, and AI-powered citation suggestions.

**Categories:** Bibliography, LaTeX, Academic Writing

**Install:**
```bash
/plugin install bibliography-skills@fangrh-bibliography-skills-marketplace
```

**What you get:**
- `/bib-extractor` - Extract BibTeX from DOIs, URLs, PMIDs, arXiv IDs
- `/bib-preview` - Generate LaTeX previews with numbered references, notes, abstracts, and AI suggestions
- `/bib-search` - Search and extract bibliography from web
- `bib_extractor.py` - Python script for batch processing
- Full LaTeX formatting with hyperlinks for DOI/URL
- AI-powered citation sentence suggestions (optional)

**Repository:** https://github.com/fangrh/bibliography-skills

---

## Marketplace Structure

The marketplace contains a README.md that lists all available packages. Each package is hosted in its own GitHub repository.

## Adding a Package

To add a new package to this marketplace:

1. Create a GitHub repository for your package (e.g., `yourusername/package-name`)
2. Add `.claude-plugin` file to identify it as a Claude Code plugin
3. Add `package.json` with package metadata
4. Add your commands to `commands/` directory
5. Add your skills to `skills/` directory
6. Update this README.md with package description
7. Reference your package repository

## Plugin Development

See [Claude Code Documentation](https://docs.anthropic.com) for more information on plugin development.
