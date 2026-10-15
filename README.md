# Repolex Knowledge Graph of twisted/tubes

RDF knowledge graph data for [twisted/tubes](https://github.com/twisted/tubes), parsed by [repolex](https://repolex.ai).

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
rlex download twisted/tubes
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a28e91a08e5bf3303772369e1909c7e118869044
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a28e91a08e5bf3303772369e1909c7e118869044
│           └── chunk-001.nq.gz
├── blob
│   ├── 07d50d97558b66f74a99d45f7557558921e2d233.nq.gz
│   ├── 09417430caacd1465755fa1ca49325ef1761d701.nq.gz
│   ├── 1287f0f7ee02e0458edfd93e4fec2b8bb036fb39.nq.gz
│   ├── 17267129ed9b08942904fdba6126980ae7a360bb.nq.gz
│   ├── 1d5f783b4a7aea13367a475ef5456797901c2126.nq.gz
│   ├── 2d6316a1f6620ce00f9129a1bc1bba8bc07281a5.nq.gz
│   ├── 2de2cfb4a5b6b985a3e24360d25b89cf1dc96530.nq.gz
│   ├── 365e3bc04ecec2f150e3753b2f12ed64d4a3d104.nq.gz
│   ├── 3a47e7bf31991d508ee623e36b73bfddd017837f.nq.gz
│   ├── 3c9e5a6b789a096469b90dd106deea95c865843d.nq.gz
│   ├── 4051a074fa80d25bb2a89c7f3725039371ea7523.nq.gz
│   ├── 48c308d56ef9d267b05a756fd423e2a7b91495ff.nq.gz
│   ├── 4a158f8e335f12ad0f14a9c3fbafc42030a5e222.nq.gz
│   ├── 4e9096b41c5904ae0188fa5cee35aa4e468cfabe.nq.gz
│   ├── 52f17b2f4c9a00f1b69122a9cfe83d72edac7a52.nq.gz
│   ├── 54502785e01efff8580b21b0f3df03aa6b9525c7.nq.gz
│   ├── 5a6288384cb67e211272d0235a000fbd7d10f8d4.nq.gz
│   ├── 5b0b3e3f186f0f82d5c25650a1e9b4b1ec5609ca.nq.gz
│   ├── 5b2657a63475bbb3bea8029a5b43e5dc3786771d.nq.gz
│   ├── 5d92829f24fd90b735026c98702cbba2282aaa0c.nq.gz
│   ├── 64e5226a479a1fb6d2f34b340980dbe4d9a258c9.nq.gz
│   ├── 6a8505adf65f638ee814467e4ad8310d80ebf6c8.nq.gz
│   ├── 7a2a26774c8ce74d19c4928e8b127bea5e836c9e.nq.gz
│   ├── 81c95416009189ca4261d446423a4c0668be534b.nq.gz
│   ├── 88d56e359826d7bfdc2f64e8fa0dbaa4cc8e7802.nq.gz
│   ├── 8bf1ba938af9b4993f625db4fc6e708be9f3f3b7.nq.gz
│   ├── 8bfd04aefd855d1d1c6d0ebcf1245cc1918c83e7.nq.gz
│   ├── 91641dbdbe584695e27f9e82e7736ccd8d53ba91.nq.gz
│   ├── 9b105f6f21852136801c25d131f30a5f516c5fe7.nq.gz
│   ├── 9be75bc5f2bd5561e489fe9def94ae33cfe1bf6f.nq.gz
│   ├── 9f8e9cd03858f4c3b01ade2c32672174cd62c144.nq.gz
│   ├── a081c6b50bc009eecd7451ab25c3779b3ccea73b.nq.gz
│   ├── a5c1a5d1e459921ff62bd14eec694807cd16bc39.nq.gz
│   ├── a7d7ac464773e321cb4bdb31b364f36c718ebac0.nq.gz
│   ├── a927f08f469eccf692c07188f12504728ae4ea85.nq.gz
│   ├── b5ede17194b9757d52ba5b100350059459bee7b4.nq.gz
│   ├── b9c37c072c8300b2314989e06013ef896a5ee699.nq.gz
│   ├── c2e3e90c33f1b3fe49cadd948cb0f8149800d404.nq.gz
│   ├── c573e108c2e74d8e8810b775bfcc02033eb3e49e.nq.gz
│   ├── c7508c367a5cf8f37294e3cd903f64f895f56429.nq.gz
│   ├── c8ed61215f61ffc1b4f75597ff67f91a717a4cbc.nq.gz
│   ├── cbdaeb3dbc37f78e2a201d325469f22cbeb13eb3.nq.gz
│   ├── cfbce52c88767d94a9640644414cd401a778442f.nq.gz
│   ├── dd68fba6325bb40d40b0a3d408b57e71ca331602.nq.gz
│   ├── df1595d76b94e452b8d6480bed1baf954aa1ec73.nq.gz
│   ├── e0d4a2365b8da84f004091c2bd5baba977f1e6fa.nq.gz
│   ├── e2417369c3f72c72462ec81a2ac9ef6ae18adbd3.nq.gz
│   ├── ec236efa90bff924702dfbdcfba4ce1f1e0ca914.nq.gz
│   ├── ec722968c409590eaccb025e296ee3b52fea49c7.nq.gz
│   ├── f1bb477982d707c6997f1fb792cec6e624391d13.nq.gz
│   ├── f4555f5df5a43c7fcd648979ed3a8491a7a37764.nq.gz
│   └── fda2032074552024d1c00854091164b026eda5ca.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a28e91a08e5bf3303772369e1909c7e118869044.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 60 files
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

[twisted/tubes](https://github.com/twisted/tubes)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
