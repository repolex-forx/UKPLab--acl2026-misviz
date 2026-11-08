# Repolex Knowledge Graph of UKPLab/acl2026-misviz

RDF knowledge graph data for [UKPLab/acl2026-misviz](https://github.com/UKPLab/acl2026-misviz), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download UKPLab/acl2026-misviz
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6a6612b4a3216ea4eaef157043347c0405d70f0a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6a6612b4a3216ea4eaef157043347c0405d70f0a
│           └── chunk-001.nq.gz
├── blob
│   ├── 019d5e333047630dbc18c4b60849b1dc9fb3dd87.nq.gz
│   ├── 065c24f1abc100a928dbe6e5b016ac9ba2ca4b7f.nq.gz
│   ├── 08a5f7e8ee0753fb5e52e9c848cdbde19c263021.nq.gz
│   ├── 09a28c7bf5789cef85167bfb72c43d9e70314884.nq.gz
│   ├── 0ab61e7b3ebd387d6e5325f40c9e610dcb329345.nq.gz
│   ├── 132fd921e070d1f0f6361d193d790e61ca9eda4f.nq.gz
│   ├── 1828de269ba31e2c77a21ea65294daa1b9af2f22.nq.gz
│   ├── 229edba242bb190698662cdce6bdacde9f0769fe.nq.gz
│   ├── 2472c6c2e60df426e7c02bde0645d6e08c41e11e.nq.gz
│   ├── 3373cc1186385b2461f13a5e90a4e9ac1b0d023b.nq.gz
│   ├── 3462899b8bf7685b4ec6dd124ec12c75d1586854.nq.gz
│   ├── 38c4755d51c0e24342be7a6b2a8c0dab927c2451.nq.gz
│   ├── 44381b0ae5c2a49a0e81a79403d180d9a7bf5a7c.nq.gz
│   ├── 4494992e95a890d760734ccf84e8f96ba53b132e.nq.gz
│   ├── 45b4fff0e55198655f9ecd635e1c8e94d17e15d6.nq.gz
│   ├── 4853a84943437998a4be207f0825563965e5f678.nq.gz
│   ├── 4b02b04013c794dabe7cad751c90fc6716448f7b.nq.gz
│   ├── 5af488e9d5c75bffe13489863040c6bb46fa87ef.nq.gz
│   ├── 5e83e44eca2393fe64c747394b54a46c42b4e5c1.nq.gz
│   ├── 69734bcfa6b66780692b93c53dcefc01af6d2263.nq.gz
│   ├── 6a8269405f5737865a95e33f825beffaefd4b961.nq.gz
│   ├── 6fdc19974fe696ca337eea0b63746ac7c351bed1.nq.gz
│   ├── 779bb4a2fa8656f65b6a661523e8ed9d946a505e.nq.gz
│   ├── 7c3a3ae2a98fa823948446bb0b7c669ab3d2de7a.nq.gz
│   ├── 7d4f96c54aa155a17387e64501c50b6a0469932c.nq.gz
│   ├── 82ddb4d6b76e6c6c633f0f623ff1ba9c2264b4a3.nq.gz
│   ├── 846c17545055001bd25c674835ddd23c1f863edd.nq.gz
│   ├── 8b0c91d1c0c6a7abd38e8816a0d7276492fb5185.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8fe903406bffad8fa201f825860133c1725d7940.nq.gz
│   ├── 90e565c114ada08f2f9b6af8ddc78505fa4fd4fa.nq.gz
│   ├── 9b3703a912d40f58fb0fb57d20742e53d9fe7671.nq.gz
│   ├── 9c092a716fbf4520753b54ad8309ce22316e2b1a.nq.gz
│   ├── 9ebf38e55bd863e89e842bc09b088d6d6bc9ded6.nq.gz
│   ├── b159b455e95b6a1efd79e56b8ffb7f2690f92a07.nq.gz
│   ├── bf649b397891fd92f849424037ba6f043552b94c.nq.gz
│   ├── c06dd3de8d8af92758a3efe83c18669e94c6815b.nq.gz
│   ├── c08a79032592be8f5e7318991b0242323389469d.nq.gz
│   ├── c5f16677d8711f24332669f590efd7de74293621.nq.gz
│   ├── c6718de5c5ae59d2c22141a147f5afba41af9cbb.nq.gz
│   ├── c728e3f5aa1828ddb9e06e5314321d493b9330ad.nq.gz
│   ├── c9402e0193197af0a59ee70ddb647d97ce1e1f9c.nq.gz
│   ├── cc70d88618f2db414b567dc6a4f0e509ba8b6b00.nq.gz
│   ├── ce84d10af1444ed721f510c380cc3c8f0351112a.nq.gz
│   ├── d601ebb1f04e4015c1874962e841fd731af2d996.nq.gz
│   ├── d62fc66df4b9acdd5381753fde4173a5775b1ddf.nq.gz
│   ├── de11f31d089ed227e1dded874ce2bb707368fc64.nq.gz
│   ├── dfed206574ad40e645a9d7b62089af8347562d8c.nq.gz
│   ├── e0d1daf803ef7147e47f49ac7126d8d6b48b6197.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea6d05ea8f9d193059c6b06318dbcc5229e7b33a.nq.gz
│   ├── ed22d30bde6e2a5a08a3e4a342c1e6b40e4b054c.nq.gz
│   ├── ed3a9d377ba3c30e6eb8b2a35e08e8dc814a0725.nq.gz
│   ├── f92f40132f45839bbc7cb63684615653fbb0bf9f.nq.gz
│   └── f9b36a2e386cb3d8d888a1a7a06628e6595f0143.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6a6612b4a3216ea4eaef157043347c0405d70f0a.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 61 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[UKPLab/acl2026-misviz](https://github.com/UKPLab/acl2026-misviz)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
