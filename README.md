# Repolex Knowledge Graph of block/kotlin-formatter

RDF knowledge graph data for [block/kotlin-formatter](https://github.com/block/kotlin-formatter), parsed by [repolex](https://repolex.ai).

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
rlex download block/kotlin-formatter
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cda53bc0b575fec0d85728d94b44b668d041ad99
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── cda53bc0b575fec0d85728d94b44b668d041ad99.nq.gz
│   └── repolex
│       └── cda53bc0b575fec0d85728d94b44b668d041ad99
│           └── chunk-001.nq.gz
├── blob
│   ├── 0b3433d6784ac0b6d4e9e5e7c43f72cccd092916.nq.gz
│   ├── 11d81a5a7d6dc067ed2a3d3c88d4eb7cd4a04772.nq.gz
│   ├── 12e60ac3c88a91a02e6cb4ff5a7ca8d5a3fcd15a.nq.gz
│   ├── 138b3f52d31289ead1032053f8dd4ec0b0579e00.nq.gz
│   ├── 14a348a838f08ea712a617b59c083e1f809437e7.nq.gz
│   ├── 175924d02d23d1cb7d942b8ff4b24fce6b4e327d.nq.gz
│   ├── 1d48461e4bcbc48020b89fc2f68c69e577765a5b.nq.gz
│   ├── 219b8234a9400020b2a8bf605172957d0941b1ba.nq.gz
│   ├── 22969d78f397f49e9c0f9288ae8e9e41171bb178.nq.gz
│   ├── 234c7f4c17e1ad05c583887c57bf777230083e52.nq.gz
│   ├── 258cc81cf74bfc5611a63f4c728d24b4db97e3c7.nq.gz
│   ├── 2afe721e2cd73d628b585550f29211036a5751d0.nq.gz
│   ├── 2c8ae1ed636fbf183355c0ae1b843252b9470865.nq.gz
│   ├── 37060db50db8192a1454e0e0bdd809cc7df2861d.nq.gz
│   ├── 3ae6a25543da304daf4c73adf1fce52f824030ac.nq.gz
│   ├── 3be6dcdce9abe6b1d8ed6df50bb401bdcc11e815.nq.gz
│   ├── 3d45d854b0fc09dcfa68944f9aefcaf7469cd411.nq.gz
│   ├── 4330499019afd7790ce289c17c043224caeb57ed.nq.gz
│   ├── 485114a5856bbabed9d23f7b560f57d9ed417352.nq.gz
│   ├── 485e7d59a8924f9a3a8fc7d9cf2465e492f2ac80.nq.gz
│   ├── 4a5b24330b9b34ba9ad18a757f8bcf41d0e9644c.nq.gz
│   ├── 4e1e4a0731b503fa5aed541360d82e1916658857.nq.gz
│   ├── 4e3386100e053f821430e9595ca517e7afc21da1.nq.gz
│   ├── 55ece8d2146fbcf769108f1db2340564fe6ee159.nq.gz
│   ├── 56e5a7af3f16872d88a6238f06416055d6f0b4a6.nq.gz
│   ├── 573a5cb3b7b0f92f79c78b305ad9c158aab3de91.nq.gz
│   ├── 5b4645f408736df17d0cb17ff08b948b81c967a9.nq.gz
│   ├── 67136d17499ddddbd90a1f9000687b8bc9f1bd65.nq.gz
│   ├── 739907dfd15937f032b5a46390e9d63709e87f7a.nq.gz
│   ├── 7761a7f6097375e3b802154933819eb5c4f9ecd5.nq.gz
│   ├── 7c0d568c8a6a7b7ef231bd9ab1a0bf2e93ee006a.nq.gz
│   ├── 7db603639e4ddbb615c0c0a92baeeb42d3a9e22e.nq.gz
│   ├── 7df6a62ed06d1aee3096b7fbed5bc97b9572f527.nq.gz
│   ├── 81f693259cc5d34ab293770d78cfb50d7be03b17.nq.gz
│   ├── 82aed8b9a2d6bbe16ef932272d45563ce713cedb.nq.gz
│   ├── 8abbcdca886abbe2e4ec70ecb0f34bde69e17c25.nq.gz
│   ├── 903572ba36e8d9a0eb5d3619fb0a8c203f1b4f97.nq.gz
│   ├── 927b22fd0aba40aadb15c188a97fed09b0dc1d44.nq.gz
│   ├── a79576a8d6827a9b9dfae46baacf87b316b8c479.nq.gz
│   ├── a93cab967f6f44a8204255d3ed086291d70e0132.nq.gz
│   ├── ac394ef7958d076c54eda596b604946fae9d7eae.nq.gz
│   ├── ae2ed60de7649f7d90da4a7d9ef2a12c5fefdc86.nq.gz
│   ├── c4d7d66ce840c8997708a0ccfec4a3198648df1b.nq.gz
│   ├── c61a118f7ddb21223f1a2fdd05f6aec1b9863aec.nq.gz
│   ├── cbdbdd45e2015128276883c0a7bf63287ebab9d7.nq.gz
│   ├── cc581e199c0a71f8d7d78a7dcc5173bea2917ca4.nq.gz
│   ├── ce3b71ec9ad3bca07b2c6e938e062e2abf106b86.nq.gz
│   ├── cfb1bb63f70a67c719e2c8148aa7b606b99948c2.nq.gz
│   ├── cfd69be6522c8b1c719d69478617a4a49eb588ab.nq.gz
│   ├── d12810fae8128f6c2ec178e8458658c7cca23bbb.nq.gz
│   ├── d39c897df8b170ad951c605b016698114a716270.nq.gz
│   ├── d93d90b18b707be31d5085b6845346e02beabab7.nq.gz
│   ├── d997cfc60f4cff0e7451d19d49a82fa986695d07.nq.gz
│   ├── da0b3fe67c9f12ad1c0162c41b38f1679163c4e5.nq.gz
│   ├── e42b0e93f36d8265e99089ef43927f3217cd4e82.nq.gz
│   ├── e509b2dd8fe5579a5954a2c28633ad914cd1c225.nq.gz
│   ├── e8b5076f947375fb72aa173471be2f3a49042a34.nq.gz
│   ├── ec6bf34eecbb430b80ac7caec22afb3cb60990b0.nq.gz
│   ├── ecfd7e44180e79ba0cf983795215bb604741576b.nq.gz
│   ├── edc4c67287815a7ebdd35462fbfd21956786fd70.nq.gz
│   ├── f199c9750cf81cede875ea0ab4e3937be0f33363.nq.gz
│   ├── f3f12dd5a6b498b499635f1f79c5bbb7307cc64a.nq.gz
│   ├── fb1bae23a1f996713750a8755edb007f0a9cacfa.nq.gz
│   ├── fc82c157eae63b2f6eb619e69baae322488fa861.nq.gz
│   └── fd98f159425b16470cccc00e93f679c86e62edcd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── cda53bc0b575fec0d85728d94b44b668d041ad99.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 74 files
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

[block/kotlin-formatter](https://github.com/block/kotlin-formatter)

---
*Parsed on 2026-10-02 by [repolex](https://repolex.ai)*
