# Signal

**AB180 Knowledge Base** — Transcripts from AB180's YouTube channel, including Modern Growth Stack (MGS) conference talks, webinars, and product presentations.

## What's Inside

- **88 videos** from [@ab180](https://www.youtube.com/@ab180)
- **68 transcripts** (201,000+ words) in Korean
- Topics: growth marketing, mobile attribution, CRM, product analytics, AI/ML, game marketing, app monetization

## Structure

```
videos/           # One markdown file per video
index.json        # Machine-readable metadata index
```

### Video Markdown Format

Each file contains:

```markdown
# Video Title

**Date:** 2025-01-15
**Duration:** 24:01
**Language:** ko
**YouTube:** https://www.youtube.com/watch?v=...

> First 200 characters of description...

---

Full transcript text...
```

### index.json Schema

```json
{
  "schema_version": 1,
  "generated_at": "2026-03-20T...",
  "total_videos": 88,
  "videos": [
    {
      "youtube_id": "abc123",
      "title": "...",
      "upload_date": "2025-01-15",
      "duration_seconds": 1441,
      "language": "ko",
      "word_count": 2415,
      "filename": "videos/video-title.md"
    }
  ]
}
```

## Use Cases

- **RAG / LLM Context** — Feed transcripts into retrieval-augmented generation pipelines
- **MCP Server** — Connect to the AB180 MCP endpoint for structured access (coming soon)
- **Search & Discovery** — Full-text search across all AB180 presentations
- **Content Repurposing** — Transform talks into blog posts, summaries, or training materials

## Data Source

Transcripts are auto-generated captions from YouTube, cleaned and deduplicated. Some videos (primarily English-only) may not have transcripts available.

## Updates

This repository is updated periodically as new videos are published on the AB180 YouTube channel.

## License

Content is provided for informational and educational purposes. All presentation content remains the intellectual property of AB180 and respective speakers.

---

Built by [AB180](https://ab180.co) — Makers of [Airbridge](https://airbridge.io)
