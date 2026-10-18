# Repolex Knowledge Graph of deepmind/trfl

RDF knowledge graph data for [deepmind/trfl](https://github.com/deepmind/trfl), parsed by [repolex](https://repolex.ai).

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
rlex download deepmind/trfl
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ed6eff5b79ed56923bcb102e152c01ea52451d4c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ed6eff5b79ed56923bcb102e152c01ea52451d4c
│           └── chunk-001.nq.gz
├── blob
│   ├── 0313434ed413365c5694835a3fca4c19e6c00549.nq.gz
│   ├── 0c5e0f29f6040de166a13cafaa539d6ab68fae3e.nq.gz
│   ├── 1189f2132edf36e8822c17c74f7ad72cacc7f212.nq.gz
│   ├── 11b027724e41f6ce762de13937c17a0c7413a119.nq.gz
│   ├── 184fbee15e27bb08bb0d6682964a9f30ef57ab17.nq.gz
│   ├── 18dbcf813b52d03d791d0c769520688a10f99d5d.nq.gz
│   ├── 1cff3dd2a63862303479a4e6a23a126c1d1a3847.nq.gz
│   ├── 1eb22fe01bcebdaea0ff42779c7b4e74e8658fdf.nq.gz
│   ├── 1f0eb8158950b767a62c1a5e7163c1ac4c767f03.nq.gz
│   ├── 225be1cea0d1df25ff24ed077f9f1546af47291b.nq.gz
│   ├── 28ee52a7eb78e1a1ebbfa10c26fc5e295ba47948.nq.gz
│   ├── 2a1751896579c7997a13f0188e9658e3d3e90640.nq.gz
│   ├── 2cfcba649323be08e1f29a5ea7e791b529ce5dfa.nq.gz
│   ├── 390e284b9c041724bb106cd6ca9e4531fa0626b0.nq.gz
│   ├── 3e45fd5158e081e26b9c985cf8c5ec6c16c99d99.nq.gz
│   ├── 41727552ecce37afc9ee360000189609bb064937.nq.gz
│   ├── 4ae49c76eb6c8ffda12fb11072dda0992928371c.nq.gz
│   ├── 4e2138faf2589f1bc52865a5eadf1533f147619c.nq.gz
│   ├── 5754090e31a52631f655a77edb43a927ec167141.nq.gz
│   ├── 589e350301374c42a956f59a80f8da6fffb90e02.nq.gz
│   ├── 6179a31e4ba22fd98c6b4cc56ae5f25205f2ab84.nq.gz
│   ├── 68d98a76f061f6640e737409a2b2e1b8bf4da598.nq.gz
│   ├── 6b5199819b12938e9a50577693cffd9f7ffdb5ea.nq.gz
│   ├── 6c7490d075d2fe30674b1214c18cb76e411aa478.nq.gz
│   ├── 7c3791efdcb987b9ed333cba68f71160b1f9564a.nq.gz
│   ├── 9040891b98d28f9630f76767bb22ed570ad3f11c.nq.gz
│   ├── 90d8412aaa560021a7f8a5307c4a23ce0c2fed43.nq.gz
│   ├── 939e5341e74dc2371c8b47f0e27b50581bed5f63.nq.gz
│   ├── a1610e4356f75bdc46886b8b9d3d1a9beefe726d.nq.gz
│   ├── a16d2100f71ad2a50281aa6e171b6fb7355aed4f.nq.gz
│   ├── a6e0343d2db839d71255194f1a7131ad887b7a71.nq.gz
│   ├── ada3773f424fb9486f87e9d2bfe452f4cc36d5f3.nq.gz
│   ├── b062dc2dbecec3a0562fe211b6e4c134d7d1618e.nq.gz
│   ├── b3444563a783eb61ab2dbb86459e401909e226b1.nq.gz
│   ├── cb803ae4b5a310a3280c78fee2b712ad696adaa9.nq.gz
│   ├── ce0f6045ce72a22096fb84e9b9b94092b09581cf.nq.gz
│   ├── cf91102f2d4befd4d66c9d3ce8ace3a0f6838a64.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d9dddfaad53079b5b7abb155f5ee0c2187ba045f.nq.gz
│   ├── e01bca8b0d723db8e22f8ebd85acd971cc73f131.nq.gz
│   ├── f03da9197bea7d0b3f7433b9c18700ba81997d2b.nq.gz
│   ├── f8d6b9c261ae6aad3414d71d59037c8d8e5c6366.nq.gz
│   └── fd5404253dda3de617f6a2a0c24b4fcb0582b9cc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ed6eff5b79ed56923bcb102e152c01ea52451d4c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
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

[deepmind/trfl](https://github.com/deepmind/trfl)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
