# Bibliography Skills Marketplace

A curated marketplace for bibliography extraction and management tools for Claude Code.

## Installation

### Add Marketplace

```bash
/plugin marketplace add fangrh/bibliography-skills-marketplace
```

### Install Plugin

```bash
/plugin install bibliography-skills@fangrh-bibliography-skills-marketplace
```

## Available Plugins

### Bibliography Skills

Zotero-like bibliography extraction and management for Claude Code.

**Features:**
- Extract BibTeX from DOIs, URLs, PMIDs, arXiv IDs
- Generate LaTeX previews with numbered references, hyperlinks, notes, abstracts
- Search and extract bibliography from web
- Auto-generated citation keys
- AI-powered citation suggestions
- Support for Science magazine e-locators

**Commands:**
- `/bib-extractor` - Extract BibTeX from identifiers
- `/bib-preview` - Generate LaTeX preview
- `/bib-search` - Search and extract from web

**Repository:** https://github.com/fangrh/bibliography-skills

## Usage Examples

### Extract from DOI

```bash
/bib-extractor 10.1038/s41586-021-03926-0
```

### Extract from URL

```bash
/bib-extractor https://www.nature.com/articles/s41586-021-03926-0
```

### Batch extraction

```bash
/bib-extractor --input dois.txt --output references.bib
```

### Generate LaTeX preview

```bash
/bib-preview references.bib
```

### Search for papers

```bash
/bib-search "quantum computing" --limit 5
```

## License

MIT License

## Author

fangrh (https://github.com/fangrh)
