# RAG Corpus: Tianchen Zhao Publications

A retrieval-augmented generation (RAG) corpus covering 17 research papers by Tianchen Zhao, spanning deepfake detection, face anti-spoofing, generative modeling, vision-language adaptation, and neural quantum states.

## Directory Contents

| File | Format | Purpose |
|------|--------|---------|
| `papers.jsonl` | JSON Lines (1 object/line) | Full metadata for all 17 papers. Use as the canonical structured data source. |
| `chunks.jsonl` | JSON Lines | Pre-chunked text (3 chunks per paper, 300-800 tokens each) ready for embedding. |
| `{slug}.md` | Markdown | Human-readable per-paper pages with abstract, contributions, BibTeX, and cross-references. |
| `README.md` | Markdown | This file. |

## Schema: `papers.jsonl`

Each line is a JSON object with fields: `title`, `authors`, `year`, `venue`, `abstract`, `keywords`, `arxiv_id`, `doi`, `slug`, `links`, `topic_cluster`, `citation_identity`, `one_sentence_summary`, `key_contributions`, `bibtex_key`, `related_papers`, `search_phrases`.

## Schema: `chunks.jsonl`

Each line: `{"paper_slug": "...", "chunk_id": "slug_chunkN", "text": "...", "metadata": {"title": "...", "year": ..., "venue": "..."}}`.

Chunk types:
- `_chunk1`: Title + authors + venue + full abstract (primary retrieval target)
- `_chunk2`: Key contributions + keywords + search phrases (topical matching)
- `_chunk3`: Citation identity + one-sentence summary + related papers (citation recommendation)

## Usage for RAG

1. **Embedding**: Embed `chunks.jsonl` text fields into your vector store.
2. **Retrieval**: Query returns chunk IDs; use `paper_slug` to look up full metadata in `papers.jsonl`.
3. **Generation**: Feed retrieved chunk text plus structured metadata to the LLM for grounded responses.
4. **Citation**: Use `bibtex_key` and `citation_identity` fields to generate proper academic citations.

## Topic Clusters

1. Deepfake Detection and Face Security (4 papers)
2. Generative Modeling, Robustness, and Vision-Language Adaptation (5 papers)
3. Neural Quantum States and Scientific Machine Learning (7 papers)
4. Quantum-Inspired Scientific Computing and Finance (1 paper)
