# Linked Data — A Hands-on Introduction

A 4-hour [Slidev](https://sli.dev/) workshop walking through the full Linked Data stack — from the first triple to querying real-world knowledge graphs, validating data with SHACL, and using knowledge graphs to ground LLMs (GraphRAG).

Live deck: <https://matdata-eu.github.io/slides-linked-data-introduction/>

## What's inside

- **Why Linked Data** — data silos, the 5-star model, graph vs tree
- **RDF** — triples, IRIs, literals, blank nodes
- **Turtle** — syntax, serializations, schema.org
- **Real-world knowledge graphs** — Wikidata, DBpedia, Google KG, ERA RINF, Infrabel & Bane NOR DIM, UniProt, Europeana, BBC, enterprise KGs
- **Ontologies** — RDFS, OWL, SKOS, reasoning
- **SPARQL** — `SELECT`, `CONSTRUCT`, `ASK`, federated queries with `SERVICE`
- **SHACL** — shapes, constraints, validation reports
- **Linked Data & LLMs** — hallucinations, RAG vs GraphRAG, how ontologies and SHACL ground and guardrail LLM output
- **Tooling & publishing** — triple stores, VS Code extensions, libraries, JSON-LD, LDES, Solid

### Hands-on exercises

1. **Describe yourself in Turtle** using schema.org, validate online
2. **Query a public knowledge graph** live (Wikidata / ERA RINF)
3. **Validate your TTL** against a SHACL shape and fix violations

## Run locally

```bash
npm install
npm run dev      # dev server at http://localhost:3030
npm run build    # static build into ./dist
npm run export   # export to PDF
```

Edit [slides.md](./slides.md) to modify the content. Custom styles live in [style.css](./style.css).

## Deploy

Pushing to `main` triggers [.github/workflows/deploy.yml](./.github/workflows/deploy.yml), which builds the deck and publishes it to GitHub Pages.

## Links

- [Slidev docs](https://sli.dev/)
- [matdata.eu](https://matdata.eu/)
- [yasgui.matdata.eu](https://yasgui.matdata.eu/) — SPARQL playground
