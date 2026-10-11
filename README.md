# Repolex Knowledge Graph of agronholm/apscheduler

RDF knowledge graph data for [agronholm/apscheduler](https://github.com/agronholm/apscheduler), parsed by [repolex](https://repolex.ai).

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
rlex download agronholm/apscheduler
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a660860d841c5426ec3b7ed2d4ada8fe168710f1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a660860d841c5426ec3b7ed2d4ada8fe168710f1
│           └── chunk-001.nq.gz
├── blob
│   ├── 0654a41097f5b9f8ba7e4ce24812b257b452e887.nq.gz
│   ├── 070fbdbdaed55f64c005e30d5879db21af86efd7.nq.gz
│   ├── 081c1b3bbc968342f8f879a1293668697736a882.nq.gz
│   ├── 081f51b3fd3baf9656ce19c4bcd26c42f910d795.nq.gz
│   ├── 09a1469250bbc5fa37db9decd83a081668ea5707.nq.gz
│   ├── 0b84a24312679a97eeaf4a4754a9f9b01237cc7d.nq.gz
│   ├── 0edc0e502e9ca9de04e9e479651605c6accc94f4.nq.gz
│   ├── 124bab4020479d4519b9d6736e8531289559a32c.nq.gz
│   ├── 1596a0647176b1ad26d8e03fcc3a6244505bd397.nq.gz
│   ├── 191da82ecda07e3e26fffe367fad2cb6f4f7bda5.nq.gz
│   ├── 1fcf3a8a90c5d879ebbde19e07eb8144d6703b7a.nq.gz
│   ├── 238c0d34b273c9d5c32971dc5131fa0b329ead1c.nq.gz
│   ├── 24641591dbe6fa73c39e0e8d892b25bf4db91882.nq.gz
│   ├── 262690f07bf211ecd552fe9b9efaf6225103b282.nq.gz
│   ├── 28d23b0edd5cfd15ac87fbcc0918d787e2f8039b.nq.gz
│   ├── 2d618a24929867f8a06d9225697c4bee7fd060d3.nq.gz
│   ├── 3038ba2c9a4585c98f73b15b0a09373d450c61e3.nq.gz
│   ├── 316e17a846667cb097e200950c37c6e565211fdd.nq.gz
│   ├── 332a3a278026e79d06c578a6e1f425c654609d0c.nq.gz
│   ├── 357e6a0bca4e68ecc7d3054bae86af910c8473c5.nq.gz
│   ├── 3634901d1bca4e56f1b7c60c50040e4cf9db6533.nq.gz
│   ├── 37950c7c2e35654c0f9e2ec837c62b35f6635aa7.nq.gz
│   ├── 38cf499c5eb470e7a2481977b7b27a3f35e7eab4.nq.gz
│   ├── 38f557a0bba0a2f7406e2e65e558f8cd984e371d.nq.gz
│   ├── 3a2fa3699a147f6dc6397202266fd61d30139337.nq.gz
│   ├── 4101db451511fded5e7e167d083e244bd3323aa2.nq.gz
│   ├── 41116b0c0c26261e62b4ce53520882883038a5d4.nq.gz
│   ├── 4271081f8901b75d9b971cdc62a944c053ba3d79.nq.gz
│   ├── 45a2f73673edab66a13ab5de206142341e996f10.nq.gz
│   ├── 45ecd030872a53213085a5ec55adf5f6f24aa8e3.nq.gz
│   ├── 45ecf80af8d53928efbe222ce384c99ae0d38d85.nq.gz
│   ├── 4865f1a44356af54073c8d0f68fc0b2c81d1b4cd.nq.gz
│   ├── 48e094bb36ddb183831d07773a7b8afc2ff54b56.nq.gz
│   ├── 4e843eee0d15081fd36b936e798d7692fee42076.nq.gz
│   ├── 51d3dd11db8b87b1368130f8785e2fe749f1934b.nq.gz
│   ├── 52f7748301374a80f9f639af123f88a5bd18e595.nq.gz
│   ├── 568b77c24a3f42a88e16f1f228657a1469b172c1.nq.gz
│   ├── 5ab695bc3e5bf87840f7163f6f96410866587333.nq.gz
│   ├── 5dae75bbfa5877233988fbd145ee2c62f105caec.nq.gz
│   ├── 5e036cbab17ff48c5ff99ea6ff9f7be905f35a7c.nq.gz
│   ├── 607f3f894b548e51548063b48bfdb7edf77c40a2.nq.gz
│   ├── 615ff0b8a88fc0ee20191bda034c16989fd406f0.nq.gz
│   ├── 64c666501eec6d57faadb8411bea0db85ff587e9.nq.gz
│   ├── 6aa6bf3b0cedb76fcacde7dfc8d9254a481cf68d.nq.gz
│   ├── 6c0dae3a4009fa64cadf120d3c6e678775fc4c24.nq.gz
│   ├── 6c538a78461780f0f61f7ee024e212b9a4aaa3dd.nq.gz
│   ├── 6ec481ea6b044a6b26c822ebd3669f5eb942ec4f.nq.gz
│   ├── 71618fe82a85a23f0923210150d0f780bec62b8c.nq.gz
│   ├── 71966b47748f696a06a2242f95519313a623638b.nq.gz
│   ├── 79117e846f8a0f48688db75286b23303352d524f.nq.gz
│   ├── 7bb89fc21ff5fe1d27a379036fd1ef7d7bd2545b.nq.gz
│   ├── 7e820c6618664aebac7411a79f6a944e928200d6.nq.gz
│   ├── 812d3eb2babfa91c692f154a4bcac37f2a1d3f90.nq.gz
│   ├── 812e760717c42e6dbe7c5a80609b8bdd95fc0995.nq.gz
│   ├── 8e82bd7ce7bf58d82773ce04422b89c9c11fbe8e.nq.gz
│   ├── 8ed031b0c08dee9c6d12656471aaf505ef72dfbc.nq.gz
│   ├── 8fc7a0e6f8ff741addaed2e73b61330cbc7f8f4e.nq.gz
│   ├── 9141263d7bff1d93cb9d08de6b69c91c440b6548.nq.gz
│   ├── 91b67393fc5f4fd7bb50a4293e74c8cbc9e87ebb.nq.gz
│   ├── 94074b3ef4dfa4e43409e22f75857dfdc69fab07.nq.gz
│   ├── 9771ae7b1905ea5ddb37e77ba4c729d116415a6c.nq.gz
│   ├── 9774093f25bf8db7cd14d042f09570d1af6848f8.nq.gz
│   ├── 9bd5fc2a60ed7a7aee8d9ae03a062fb44852c284.nq.gz
│   ├── 9dd1f44f65e71fa0b8263ac59133df0d59011598.nq.gz
│   ├── 9ea030ca6810554e1d91115f1d410e34f83dee1a.nq.gz
│   ├── a2605ee00ca310efc35237cdc5efc48b6e8445ad.nq.gz
│   ├── a8205970b1546eb8a9aa333d9298a30d1654a236.nq.gz
│   ├── a90a70240304f8adbd999ea61754e43d3ca019e3.nq.gz
│   ├── a9fd49393f6f56c6d5b58bbaa7b356456d05ce92.nq.gz
│   ├── aa8df90dd42b2398885a12dfebdb8894ab38e689.nq.gz
│   ├── aff4e2634186f059108e1720c7db6fbfca5ae0f6.nq.gz
│   ├── b618477b3f2320adfc6c04b473cff03c5682c96f.nq.gz
│   ├── bde5e4065641106168c1626268efc1c49d03e9ea.nq.gz
│   ├── c0216fb310725663dcfe2f2eff887b9cbee9497d.nq.gz
│   ├── c1d971d5291345e983af450f4d4752262eb5584f.nq.gz
│   ├── c2311df6dd78c8dedeb98951636cf0860c27b05f.nq.gz
│   ├── c7924ad7ade4dd7fb1ce98890173ccec466c4fc2.nq.gz
│   ├── cad2b572214aa8e324a8ee49ae5a1bea1a246174.nq.gz
│   ├── cc770a8f1a20f79f0e91feffc3e61318bd72c311.nq.gz
│   ├── cfe089e0adc7d9d38b053621655f12eda30b1cd1.nq.gz
│   ├── d24a39d106992f101f3a35fc30c671e389a32389.nq.gz
│   ├── d66cd452fdeeceff02f0d397e6866141fc50f5e1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e766e71476e7a632dc72973840b9952290c395e6.nq.gz
│   ├── ec75afb9aac16761779656544aab60cd1a64b4b1.nq.gz
│   ├── f06a2cc2fe39708396c6e9759ceccfb2163aca9f.nq.gz
│   ├── f358f45ab369cc0895e0130fc221ef3433b37300.nq.gz
│   ├── f4714507174af0b1934c35154feaef433ee692f5.nq.gz
│   ├── f526ebe29fbfc2a33db861959aa72f1e4ad2580d.nq.gz
│   ├── f7ba30b5dbced455b7ba49926e2030b11c14d833.nq.gz
│   ├── f901cd877e3ee80dede3876696ae3b7380e68390.nq.gz
│   ├── f93e2ff816e680f2e52492f6c9f88e66cb67d498.nq.gz
│   ├── fbeaa9ba3039ab79e382388b54e3aa1fb14f3e5a.nq.gz
│   └── ff7af6db8385db7c43f9aeb0ae509dbeba5ce22d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a660860d841c5426ec3b7ed2d4ada8fe168710f1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 102 files
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

[agronholm/apscheduler](https://github.com/agronholm/apscheduler)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
