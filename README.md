# Repolex Knowledge Graph of ionelmc/python-aspectlib

RDF knowledge graph data for [ionelmc/python-aspectlib](https://github.com/ionelmc/python-aspectlib), parsed by [repolex](https://repolex.ai).

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
rlex download ionelmc/python-aspectlib
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 52092d5e8ee86705c0cad9f9b510dcedabbdc46f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 52092d5e8ee86705c0cad9f9b510dcedabbdc46f
│           └── chunk-001.nq.gz
├── blob
│   ├── 0039108770880ebf7f2abf558afd698d65ff3b51.nq.gz
│   ├── 009a913cde5985359d40200f00c0efcc2baf5582.nq.gz
│   ├── 02514ceda055963ef5c07023b4d69b3987cc6eae.nq.gz
│   ├── 052284324226764c04205a19699c705905cef67f.nq.gz
│   ├── 0e3a2cde2930ddbddf17d70a19f476b21425ca5f.nq.gz
│   ├── 118418c2bf0b2e763410acb228f6d821791777fc.nq.gz
│   ├── 15482c45205095db60891600e267a6db013f4eeb.nq.gz
│   ├── 1900e6f4d0319d9bd9cd498c321e4b0fcac7775e.nq.gz
│   ├── 1c924f43553e4b09c9d8378adb2cb1045a7b05e8.nq.gz
│   ├── 28df5654c0caecab5c654cf11ca055238ff76c72.nq.gz
│   ├── 298bf0dd83f9121d9d3962c0ba724c30a4a35a44.nq.gz
│   ├── 29caa5038d1fb5063b1374afc5adbace0f16b016.nq.gz
│   ├── 2b5fc57d1979a7d5a3df84877f9adca70dc71aec.nq.gz
│   ├── 2cb466bbf26c2257be860be9c8202eceba85cdc5.nq.gz
│   ├── 33236843d84f6438b6396c8474adc509e65f085d.nq.gz
│   ├── 34b73cbf707b884a951e9bd049184ec89b0bfed3.nq.gz
│   ├── 3cc799bd11e5f36ee708836ac09a5bf51c271f21.nq.gz
│   ├── 415ea7b2c89bb707466add328de378aafbb3a428.nq.gz
│   ├── 4586d9238e5f40aedf3b972be4a9b4c2ed81e42d.nq.gz
│   ├── 5274834a1ffd8cb9de34940798cc301416367339.nq.gz
│   ├── 5544935a40866365de8255860563e7cc714d58e3.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 586c7367de1cff5d362be309c0a4014b0905edb1.nq.gz
│   ├── 61b141c28f033ab52ec35ab9684f843297f4ae98.nq.gz
│   ├── 6ac03825c724f1f039852e00bcb2bb66355d2780.nq.gz
│   ├── 72a33558153fb57def85612b021ec596ef2a51b9.nq.gz
│   ├── 770e36ed77519bd8b5250531a3cd986f5cf185fa.nq.gz
│   ├── 77973dd9ff9648541ba9872375bba8ed6e340038.nq.gz
│   ├── 7a7e143a4e87f6ff40101cd9fb97813b0f9eaa2f.nq.gz
│   ├── 7a8ebeaba7c682d7858163a4d1878ed5b2614755.nq.gz
│   ├── 7eaddf9442678e5cb791e4c99cb27e43928b3e4a.nq.gz
│   ├── 7fa9bced62e00aecae9eaa348f85700dbc5350a6.nq.gz
│   ├── 81a06f8facf9bc55d0724463d317be8603284bc1.nq.gz
│   ├── 862c3733156344dfeda7662ac000a2c2a598277a.nq.gz
│   ├── 9267902b69911408f90c3f77dc25a3064048c3ee.nq.gz
│   ├── 976719c165f142e6ab8a456dedcf66ff35bceded.nq.gz
│   ├── 97a257e8e68d64b77a64abd1fc60dd34e4eefd8c.nq.gz
│   ├── 988950a580e6d03694e5d5ea767553b59f76b6cc.nq.gz
│   ├── a1708f401aa3b38d34cfb9a7b6d084fce2014e32.nq.gz
│   ├── af589bc986cd7f8efcae13646a2b24ed7617d493.nq.gz
│   ├── b290b6979273759a275735806d33730c5a9f151a.nq.gz
│   ├── b650280a530ba59e5de5f5c2da1c80866e8dbece.nq.gz
│   ├── bd70924c99ae5153b23edebbde7e72dfb82e83a7.nq.gz
│   ├── c03e307ab39cd6807b9bc0d8f404e716707c2533.nq.gz
│   ├── c243d2ebb772b70a001102616f232e921fa1632a.nq.gz
│   ├── cce57beb19e8003c25ab8bf3a9d7d1e043a4b2bb.nq.gz
│   ├── d0dac9c381161c95e487044411c1f9838f4ffe3a.nq.gz
│   ├── d3b0b2fdc46b50679d02527a4aa26d3abd585010.nq.gz
│   ├── d8724c54ad8b077f1931ab7385c1c465946d3c1c.nq.gz
│   ├── da9c516dd744b6c88dd8c91f58f7bcf8f7e8341b.nq.gz
│   ├── daf10e4ba364e3799122ca821a839e413318e4e5.nq.gz
│   ├── dc0a507f771c51fd2f8eac6d25a2860937267188.nq.gz
│   ├── dc0ed3b72c3fde9410c36617a37010e57c28c127.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e1db807e7fb5656b169fc2ee741cb1c4418103b5.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eaff88e0aab5b1c094eeb9760b08e435cbf7ed85.nq.gz
│   ├── eb019b86fdbaa9f38912cbfa967d97586c1d0309.nq.gz
│   ├── ed3344cccd0b6cc7c2532c88bd65339482f94fda.nq.gz
│   ├── f3c9a7ea683e2a0b79a04e03b91fa117b49a08b0.nq.gz
│   ├── f66975c46c239ae1ca34b90457f0faebbf08d09a.nq.gz
│   └── fea87e6ef8679426282c8db83dd076546f3aa607.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 52092d5e8ee86705c0cad9f9b510dcedabbdc46f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 71 files
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

[ionelmc/python-aspectlib](https://github.com/ionelmc/python-aspectlib)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
