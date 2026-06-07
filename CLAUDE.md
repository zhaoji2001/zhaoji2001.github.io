# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A Jekyll-based academic personal homepage. Designed for researchers who want an attractive, responsive website without managing their own hosting.

## Development Commands

### Local Development
```bash
# Start live reloading server (requires Ruby/Jekyll installed)
bash run_server.sh
# Open http://127.0.0.1:4000
```

### Building
```bash
bundle install
bundle exec jekyll build
# Output goes to _site/
```

## Architecture

### Jekyll Site Structure
- **[_config.yml](_config.yml)** - Main configuration (title, author info, analytics ID)
- **[_pages/about.md](_pages/about.md)** - Main page content (Markdown + HTML)
- **[_layouts/default.html](_layouts/default.html)** - Base layout with includes
- **[_includes/*](_includes/)** - Reusable components (head, masthead, sidebar, etc.)
- **[_sass/*](_sass/)** - Sass stylesheets (compiled to CSS)
- **[_data/navigation.yml](_data/navigation.yml)** - Site navigation structure

### Page Content
Pages use frontmatter for metadata:
- `permalink` - URL path
- `title` - Page title
- `author_profile` - Set to true for profile pages
- `redirect_from` - Alternative URLs

Content uses Markdown with optional HTML. For paper citations, use:
```html
<span class='show_paper_citations' data='PAPER_ID'></span>
```

### Configuration Options
In [_config.yml](_config.yml):
- `google_analytics_id` - Analytics tracking ID (optional)
- Author links (GitHub, LinkedIn, ORCID, etc.) - under the `author` section

## Dependencies
- Ruby + Jekyll (for building)
