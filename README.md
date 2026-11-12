# Watchtower

AI news intelligence in the spirit of ScoutAsia, designed and shipped by an AI product manager orchestrating a team of Claude Code agents.

**Live demo:** TODO

## Screenshots

| | | |
|---|---|---|
| Screenshot 1: TODO | Screenshot 2: TODO | Screenshot 3: RAG chat (TODO) |

## What it does

Watchtower pulls news from GNews, turns it into structured intelligence, and lets users question it through a RAG chat grounded in the underlying articles.

- **Who it is for:** TODO
- **Core features:** TODO (3 to 5 bullets)
- **Coverage:** TODO (regions, languages, volume)

## Architecture

1. **Ingestion:** GNews API, TODO (schedule, dedupe).
2. **Processing:** TODO (enrichment, entity extraction, summarisation).
3. **Storage:** TODO (database, vector store).
4. **Retrieval and chat:** RAG over the article store, TODO (models, retrieval method).
5. **Frontend and hosting:** TODO.

## How it was built: multi-agent orchestration

Watchtower was built by directing Claude Code agents, not by writing most of the code by hand. My job was to define the work, split it across agents, set the checkpoints, and decide what shipped.

| Agent or role | Responsibility | Where I stepped in |
|---|---|---|
| TODO | TODO | TODO |
| TODO | TODO | TODO |
| TODO | TODO | TODO |

The full account, including where my judgment changed the output, is in [how-this-was-built.md](how-this-was-built.md).

## How quality is measured

> Placeholder. Results will be published once the eval runs are final.

| Eval | What it checks | Test set | Result | Target |
|---|---|---|---|---|
| Faithfulness | Chat answers are supported by retrieved articles | TODO | TODO | TODO |
| Citation accuracy | Cited sources contain the claim they are cited for | TODO | TODO | TODO |
| Retrieval recall | The right articles reach the model | TODO | TODO | TODO |
| TODO | TODO | TODO | TODO | TODO |

## Case studies

Short write-ups of product decisions: the problem, options, decision, trade-offs, and what I would revisit.

1. [Switching from RSS to GNews](case-studies/rss-to-gnews.md)
2. [Designing the RAG chat and checking answer quality](case-studies/rag-chat-quality.md)
3. TODO: third decision reversal

## License

Writing is all rights reserved. Code samples are MIT. See [LICENSE](LICENSE).
