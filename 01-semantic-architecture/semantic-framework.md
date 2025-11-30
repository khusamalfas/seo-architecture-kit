# Semantic Framework

This module defines how we structure search demand into a scalable semantic architecture.

## Goals
- Convert raw keyword dumps into a clean, clustered, intent-based structure.
- Eliminate cannibalisation by assigning one primary URL per cluster.
- Align content, product and UX around clearly defined topics.

## Core Concepts
- **Entity** – real-world concept (service, symptom, category, brand).
- **Intent** – what the user wants to achieve (informational, commercial, transactional, navigational).
- **Cluster** – group of semantically related queries that should be served by one content asset / URL.
- **Topic Tree** – hierarchical map of categories → subcategories → topics → supporting topics.

## Process Overview
1. Collect queries (SEO, PPC, search terms, competitor gaps).
2. Clean & normalise (lowercase, trim, remove brands/noise).
3. Classify by:
   - Intent
   - Stage (awareness / consideration / decision / post-purchase)
   - GEO, language (if relevant)
4. Cluster by semantic similarity and SERP overlap.
5. Assign each cluster:
   - Target page type (service, category, article, FAQ, local page, etc.)
   - Priority
   - Target URL (existing or planned)
6. Build Topic Tree and sync with IA & URL architecture.
