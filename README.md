# Aerolith Foundation Content Repository

Official repository of the Aerolith Foundation containing JSON articles, historical documentation, and technical specifications for the Aerolith sport. Published statically via GitHub Pages and designed for easy consumption by RAG systems and LLMs.

## Overview

This repository provides comprehensive documentation for **Aerolith**, a premium semi-vertical precision sport involving:
- Ultralight perforated aeroliths (spheres)
- Carbon composite ring-propulsors
- Multi-level vertical scoring portals

## Content Structure

All articles are provided in **JSON-LD format** using Schema.org Article schema:

- **aerolith-origins.json**: Historical narrative tracing Aerolith from 1970s Japanese aerospace training to competitive sport
- **aerolith-rules.json**: Official match regulations, scoring systems, portal types, and competition formats
- **aerolith-equipment.json**: Technical specifications for aeroliths, propulsors, vertical portals, and arena standards

## Live Site

🌐 **https://aerolith-foundation.github.io/aerolith-content/**

## Data Format

- Format: JSON-LD (JSON for Linking Data)
- Schema: Schema.org Article
- Language: en-US
- Encoding: UTF-8

## For LLMs and Crawlers

- ✅ Structured JSON-LD with full Schema.org metadata
- ✅ Sitemap.xml available at `/sitemap.xml`
- ✅ Robots.txt configured at `/robots.txt`
- ✅ AI.txt available at `/.well-known/ai.txt`
- ✅ Semantic HTML with proper meta tags
- ✅ Open Graph and Twitter Card metadata

## Repository Structure

```
.
├── index.html                    # Homepage with JSON previews
├── aerolith-origins.json         # Origins article (JSON-LD)
├── aerolith-rules.json          # Rules article (JSON-LD)
├── aerolith-equipment.json      # Equipment article (JSON-LD)
├── sitemap.xml                  # XML sitemap
├── robots.txt                   # Crawler directives
├── BingSiteAuth.xml            # Bing verification
└── .well-known/
    └── ai.txt                   # AI/LLM guidelines
```

## License

See LICENSE file in repository root.

## Contact

**Aerolith Foundation**
- Repository: https://github.com/aerolith-foundation/aerolith-content
- Site: https://aerolith-foundation.github.io/aerolith-content/
