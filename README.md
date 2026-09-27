# Slide Share Research Agent

A CrewAI declarative Flow for multi-source academic document research.

The agent accepts a natural-language research request, generates search queries, searches four public sources, scrapes discovered pages, extracts document metadata, validates relevance, removes duplicates, maintains checkpoints, and produces structured research outputs.

## What it does

The Flow follows this pipeline:

```text
Natural-language research request
        ↓
Research Command Interpreter
        ↓
Checkpoint Loader
        ↓
Multi-source Search & Scrape
        ↓
Metadata Extraction
        ↓
Relevance Validation
        ↓
Deduplication & Storage
        ↓
Summary Report
