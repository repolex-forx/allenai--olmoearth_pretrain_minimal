# Repolex Knowledge Graph of allenai/olmoearth_pretrain_minimal

RDF knowledge graph data for [allenai/olmoearth_pretrain_minimal](https://github.com/allenai/olmoearth_pretrain_minimal), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/olmoearth_pretrain_minimal
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8d5aa7c8c32f854ae8d7afa1b807614b8a1a4ab0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8d5aa7c8c32f854ae8d7afa1b807614b8a1a4ab0
│           └── chunk-001.nq.gz
├── blob
│   ├── 0afbe9aec87a8e70c689745c37df3b8bcf58fa37.nq.gz
│   ├── 0d12a435fceba10138eb072c3d5a4b967d953006.nq.gz
│   ├── 10060f36cdc572abbcd5f32129eb9a43ca168789.nq.gz
│   ├── 13d36af4b36cf75ccb1301b07e774b4b114a0441.nq.gz
│   ├── 15d138c62ef290f7b2a4b7bce94e7d3d5a76ec07.nq.gz
│   ├── 2a3115f7cea22737d948745223db3e934c49470d.nq.gz
│   ├── 2a8bf1a599c223d568451a52c5966ffd31fe6495.nq.gz
│   ├── 37ddcc5e0f3bad3d057df3774d3c4b51c85fe832.nq.gz
│   ├── 38f4065580622f766ea710291ea90a9a58589d08.nq.gz
│   ├── 392ef540cdefe6dbe3d2d9087ffa71b6c773014e.nq.gz
│   ├── 425b4efeaa98ae97d378e0e0a2a7181b3ccc3c6f.nq.gz
│   ├── 43d67919026c53196e736155e01ae36b58af4e11.nq.gz
│   ├── 47d30d14aadf63d7d033ba014945a37a6456fd03.nq.gz
│   ├── 4c58b62502363e48d95979ebef2214dec2693df2.nq.gz
│   ├── 4ccacb341077674d97aa1415f9686ec1a9b7ad2e.nq.gz
│   ├── 4d540d1de9bb09e0f4da04b3742f4e0a30ae2889.nq.gz
│   ├── 50f30c3a6f5566be6d9b9b9fec43612167eb4f30.nq.gz
│   ├── 65e4b6c8ad99e2c43c4138422f13189a413136cb.nq.gz
│   ├── 74ecea5436c2a38c373c6f43b5c1207cb1131ac5.nq.gz
│   ├── 85026459515c42348eb7af8ef3933c94ffcb8f7d.nq.gz
│   ├── 91e3697ae7d73c1e117e5e852ab2df9c44261c40.nq.gz
│   ├── 93608154dc9c41da1bf174f7d0a4112e3c14b598.nq.gz
│   ├── 94340d533b20ebdb3e3f9f64ac624605e50ba2de.nq.gz
│   ├── 975c539eaadd4370746973ef7a95a0075147913a.nq.gz
│   ├── 98ba3e3a1a8e71f08522546f15e6970776aec539.nq.gz
│   ├── 9b274a9a11730b79a4e0f8b6f8c3208c86a865f6.nq.gz
│   ├── 9fb241c3e3499ae1989e9583b3407bc1ec9c7dc9.nq.gz
│   ├── a3c71a96f6b2286dd3c0d69ad10426974a0ebd91.nq.gz
│   ├── a61d7e9cca14646eb269560a21755ca83916125b.nq.gz
│   ├── a7babf92da3e6e480a2510254ce54a36bb7bf41f.nq.gz
│   ├── a9105773bb20ac6cb6abe4a1f62f332fe6d7709e.nq.gz
│   ├── a9a97f885757730fd2c923b8293b52cde3f42084.nq.gz
│   ├── bac7baa6abf39b92a017b1a4c4c1fe2b9445ce3d.nq.gz
│   ├── c35c0409fd64557fe63c22fb7412b2c6278fedd1.nq.gz
│   ├── c35f0c345db196168d57eab0a8a8dafda03b235a.nq.gz
│   ├── ca025eb53cadc349750bc03a7805d40aef66d235.nq.gz
│   ├── d45af1bfa84005330086b70439475c52bef10f1b.nq.gz
│   ├── d79a9e20330484c0348777c438eb86d46f31eb42.nq.gz
│   ├── e4fba2183587225f216eeada4c78dfab6b2e65f5.nq.gz
│   ├── eb4f5d4f44c588031cb201cc52a61f6c55e44dd1.nq.gz
│   ├── f1efbee9e8d4cbac5969195491f5a61973932a77.nq.gz
│   ├── f725ba2bc99ba45a342ce1a3b8ba4f0736f96f8b.nq.gz
│   └── fe81716e7cd5db6d9c14508bb2a5e26ddd1dab30.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8d5aa7c8c32f854ae8d7afa1b807614b8a1a4ab0.nq.gz
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

[allenai/olmoearth_pretrain_minimal](https://github.com/allenai/olmoearth_pretrain_minimal)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
