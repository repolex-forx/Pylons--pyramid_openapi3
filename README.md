# Repolex Knowledge Graph of Pylons/pyramid_openapi3

RDF knowledge graph data for [Pylons/pyramid_openapi3](https://github.com/Pylons/pyramid_openapi3), parsed by [repolex](https://repolex.ai).

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
rlex download Pylons/pyramid_openapi3
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 39a3e77b7599a77ba107e5a772bb36f2f71a3ee5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 39a3e77b7599a77ba107e5a772bb36f2f71a3ee5
│           └── chunk-001.nq.gz
├── blob
│   ├── 08a0549d9543f19c279d031a02ce873c6fddb50d.nq.gz
│   ├── 0fe36b26dc3df3a91b55cd48c13d4dc4996db562.nq.gz
│   ├── 1503133439091cb752ef6757fa5cff26158e661a.nq.gz
│   ├── 168212955e3df697749df01af17690b8760145fe.nq.gz
│   ├── 1d86ce3f0cc29927ca27d4dc5d605e1b3bf0bf64.nq.gz
│   ├── 2372d5622e060da0fd9accb8f7573cb75ff249ad.nq.gz
│   ├── 29e41e84d32ce0095ac0a9ccf42469e388899336.nq.gz
│   ├── 2c4b13ad58cabfb0e0fe4788cf6de4f8c234ceed.nq.gz
│   ├── 2e7ca22ad9fed460acb7da2cc806bab5c923ca0d.nq.gz
│   ├── 31468f8e055ac6ca8ca04d4a572c14ae5c27bcbf.nq.gz
│   ├── 3408e765c586ecb35fee360abba49813d4f1a10c.nq.gz
│   ├── 36c3a5881e7dadac1143fe2466cd836acb4a322a.nq.gz
│   ├── 3c806ae941e43fb20ba915f6c6c0dc46c81eec94.nq.gz
│   ├── 416dbbf2213179dbfc82be23fb0d90fe3f6719e6.nq.gz
│   ├── 4771c236b2cc5e31c0af292ef6f3cb45e103ac3d.nq.gz
│   ├── 4a3e31e78c34cf3d45f438f6018c2b6e3e65bb06.nq.gz
│   ├── 6247e0917f42180006b2daad94fc1c76aa698102.nq.gz
│   ├── 635671847b288f048fb0545966f7c79fdddfeb4d.nq.gz
│   ├── 69fb915e4433d7a2d36f3e9377aa994607d520d4.nq.gz
│   ├── 6d5e74a701daa3adb30652c6fb3077d29b9d2920.nq.gz
│   ├── 723d2b98cebdf62e2e4576b24e9ba8e9aaef054b.nq.gz
│   ├── 7295e45dd41593e5ba525b8f95ee375635bbb5ba.nq.gz
│   ├── 78c6e6ee7eabf19b2c4e8366dc9189a390239afb.nq.gz
│   ├── 7d0a102a2c59660bb7b346308ed846efa8624206.nq.gz
│   ├── 7d454f4d15dbe818c16f8c6571b1c79a5ee8b3a1.nq.gz
│   ├── 8437d0274f1e8c2d64970dafbb6f0d064117fe4e.nq.gz
│   ├── 84876b0318336490a40842b6dbc4ca513ba18d66.nq.gz
│   ├── 849f14bbf5b5a3a273e914bc6d8518013906d11e.nq.gz
│   ├── 86d4023bde69a6abf61c5ffad9c12b37b6931120.nq.gz
│   ├── 8822357aeff53d4ac1bb17f45f55ab21b96921e1.nq.gz
│   ├── 88d9ed20a24e14b80054666e56d1f2054cdc5db9.nq.gz
│   ├── 8f67899626f9e35daa9dfb04acbaedd6a2587ffd.nq.gz
│   ├── 93aaa9f53da44d6067119c895b7cb54c89a6267d.nq.gz
│   ├── 94f9b63f09514b457751f50fa91861dfaa999436.nq.gz
│   ├── 98213c70ec443177002dd4ff70090764ee586235.nq.gz
│   ├── 9d047bdab3e89bb835b423be97c6f107f96a8d6f.nq.gz
│   ├── 9d7cb59fa51f7ad4ec7e2f832374ec3e875767ee.nq.gz
│   ├── a1f5c83de177b9983e2e4c857113792f671ea5c6.nq.gz
│   ├── a2f234184485d6ab0115168ee00e2bf4f9a80449.nq.gz
│   ├── a4bcefb23d463417922571cc48618795be0390b6.nq.gz
│   ├── a98dfa11700957269c7eaa987dab8e82ef2db9a4.nq.gz
│   ├── b172cddad0a99fe6527aecac575613a0c20d81b6.nq.gz
│   ├── b3240549f100020c35eacc3427a5661c8490e866.nq.gz
│   ├── bbce5d9e3d8cb1a8db105d13c62c2716a04cc07b.nq.gz
│   ├── c5984edb1af4cc9812aedef1a9c31380b52e6b8d.nq.gz
│   ├── ca091e511aaf18bb1f6e781eb7f602b9e667a44d.nq.gz
│   ├── cfca483ddbfe41e63c098bd156618b78faa4a63b.nq.gz
│   ├── e5022ab52ced5ab8290df2e13cd03c0979d6cf45.nq.gz
│   ├── e626987289b546b1b12d704efd815931e09bafe0.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7f9727250bc91d86fc8225b57b78e71d77729b8.nq.gz
│   ├── f16f7b81d56bc0ae3b8bca6b9a92b5a5deeb6b36.nq.gz
│   └── f98a708da62e52d1e4988715c4d484cd5bfe7fef.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 39a3e77b7599a77ba107e5a772bb36f2f71a3ee5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 61 files
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

[Pylons/pyramid_openapi3](https://github.com/Pylons/pyramid_openapi3)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
