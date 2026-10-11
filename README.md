# Repolex Knowledge Graph of pytest-dev/pytest-html

RDF knowledge graph data for [pytest-dev/pytest-html](https://github.com/pytest-dev/pytest-html), parsed by [repolex](https://repolex.ai).

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
rlex download pytest-dev/pytest-html
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dd163c5408bc76933379aa4b96949a82fdda79c8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dd163c5408bc76933379aa4b96949a82fdda79c8
│           └── chunk-001.nq.gz
├── blob
│   ├── 0376ea4d70753435086706ebc8f8e7602bb2a427.nq.gz
│   ├── 069cf845d90868dd36ca5c66ed3b6479fd5c6ceb.nq.gz
│   ├── 08ad208dc66b9a3a459c7064803add2ea05d4c42.nq.gz
│   ├── 1830711f6d3c184a96610d7742189d54891aeb70.nq.gz
│   ├── 1da4eaa1445f4f892f160cfe0bc74e99b9d371b2.nq.gz
│   ├── 1ea945ea924041a3c9bdb1f37863dee12b2c3e94.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 223cb04a84b5d8b093c4b85c471ba16acc680866.nq.gz
│   ├── 22ef7e146e3b1c9e80dd7ad4c0073a7f846cc9fa.nq.gz
│   ├── 2a29cb42f5defbd81046684b411c73d69b323c06.nq.gz
│   ├── 2e7f542eb34d7fc03d497ad441eb139039ea2682.nq.gz
│   ├── 38ddb5604bdaf73a0176e16af5feba2da44ac1bb.nq.gz
│   ├── 3dc0ea21ee835ec6237c1673ac4026fb80c4d699.nq.gz
│   ├── 41dc2327f1698b99dd397a84f47b9596d0a516b5.nq.gz
│   ├── 4351b2afbf68217a5846b9cf415e52b1fa6ffb69.nq.gz
│   ├── 46007bead0dfbee524bd8e1a3456a5c27128f65e.nq.gz
│   ├── 47288a4b329367fd2ffcde7b6752a89c134b94e1.nq.gz
│   ├── 4c8d21289d1509d4ea2f1aa65b549f9a4a003ac2.nq.gz
│   ├── 561524c69106e8feda279c7c65e5dc8ec20e5cb7.nq.gz
│   ├── 57060e7944c187f6ad57f9947dfc64e727a4aaa7.nq.gz
│   ├── 5bf3ad69a702939cd1f063ea2e10793116e9b080.nq.gz
│   ├── 6808743e26595f8a6cbd1a8639b76afdaa2ea73d.nq.gz
│   ├── 77a2b72322ae6fdf939e1655ea620e3dfc2ece38.nq.gz
│   ├── 79525f7e6921dadeac13ada4a789bd9d5731545b.nq.gz
│   ├── 7aed9f7544c2a036b085cae2a303d700a72891f4.nq.gz
│   ├── 7e7057d73e0cc087d87c6f9b2381e842cc487573.nq.gz
│   ├── 85508fa8080ecaf76bde55edff2b5c8e9f347a7f.nq.gz
│   ├── 8706cdf986f3f5827a646310ea56bd7e9a0a427a.nq.gz
│   ├── 876f70c7b5da9f44f00e8d7b4d3f174427e16fdd.nq.gz
│   ├── 88ce828d95f14817f16b1bfeccc35904502bb27b.nq.gz
│   ├── 891c8877f72b8f2f8489201ffd2e28e4c9c57321.nq.gz
│   ├── 8d6c81136bee41794cce1cfb74693ecfd69b9861.nq.gz
│   ├── 8f3703cdf11afb47c65c967a572a4ddcff7383f1.nq.gz
│   ├── 949a6ffaa9e5fb611da1c65ab5cd1f63bcfde768.nq.gz
│   ├── 9a59a76d460f1cfcb9c81835d24fe04dd21c513d.nq.gz
│   ├── a654791654cdf1d47584db891345ae679587fe03.nq.gz
│   ├── abc028f6e62dd98a74d9e5dbb0421d33ad5e5e16.nq.gz
│   ├── ac39c12b19741e90d863fe40b18f8531b59134bb.nq.gz
│   ├── acfac88e5f8490ea9a83d4464c4bf96647c910f1.nq.gz
│   ├── b4bf0eee0bce8c56f88d494080678c63d29dd8db.nq.gz
│   ├── b95e95d950948c592363fa5f8d0fc3507377749c.nq.gz
│   ├── b96a003900a6912f590419d418840429855ec946.nq.gz
│   ├── bc94147aa5b13dbaa5b13d2cc508276faec53620.nq.gz
│   ├── c3a7267810fc2bcf044ce44c58a6f4bd95d58ee2.nq.gz
│   ├── c4b554434f59d31b6ac0770a533ac7e6a1babbc2.nq.gz
│   ├── cfcc74b2e24f7eef7f49425dc0d1322c67db0518.nq.gz
│   ├── d2968422ef8b0172718d16663461e81dc6570135.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d5c91da32c87c66a1a3e6dc481f67b3ab2b32251.nq.gz
│   ├── d899375e8fb24ce655223ce6b58ffd1e71ceaa96.nq.gz
│   ├── da094b82439c29037577b21d6916ee7927fcd598.nq.gz
│   ├── dbca2074616a5b9cc087a41e9049977203985065.nq.gz
│   ├── dc17ecc0377277db7238dd3b835c01bc12963673.nq.gz
│   ├── e1822dc23c90964683720ec10d1e6e4b7ffc86f5.nq.gz
│   ├── e6f80ef531eaf0eebecb25a7684757135ee3a839.nq.gz
│   ├── e97ea1bfabbafa202fe43049d7c686c3973f164e.nq.gz
│   ├── ecc44600b6becfeed787b95e91175cebe415f5a6.nq.gz
│   ├── edc0f78867796f03fb440c6ad3592b8f9575fc8e.nq.gz
│   ├── efc3d167078871b2ee58ab33f93d2f0c7763b1b8.nq.gz
│   ├── f01f2eac07441407192aa0bdd782b66995ffe968.nq.gz
│   ├── f3d7fe96a296640f1fb4fa8f73d2a5c9fd1cc7f7.nq.gz
│   ├── f736a01738b9dac0b01e3f31e2933b00004dc600.nq.gz
│   └── fb3bb541bf3c1d777839f2b5f71f1f344826f169.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── dd163c5408bc76933379aa4b96949a82fdda79c8.nq.gz
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

[pytest-dev/pytest-html](https://github.com/pytest-dev/pytest-html)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
