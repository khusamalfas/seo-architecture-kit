# Crawling & Indexing

## Goals
- Make important pages easy to discover.
- Prevent index bloat.
- Provide clear signals on what should and should not be indexed.

## Core Elements
- robots.txt configured per environment (prod/stage/dev).
- XML sitemaps split by type (services, blog, geo, etc.).
- Self-referencing canonicals on all indexable pages.
- Noindex for:
  - Internal search results
  - Filter combinations (unless strategic)
  - Technical / system pages
