# Repolex Knowledge Graph of darvid/python-hyperscan

RDF knowledge graph data for [darvid/python-hyperscan](https://github.com/darvid/python-hyperscan), parsed by [repolex](https://repolex.ai).

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
rlex download darvid/python-hyperscan
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 64201bb15021a2c6bcaffeed921c84e306d7e0fc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 64201bb15021a2c6bcaffeed921c84e306d7e0fc
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a6268d991f1418506078f7d0fbda104698378c.nq.gz
│   ├── 036e1fbe1b75b9e8049e7c6b3e5814929c31b04a.nq.gz
│   ├── 06643bf930b51cbf858e7abc7b73794120ec2731.nq.gz
│   ├── 0b409d992206126a363228b67a1860a944553f01.nq.gz
│   ├── 0fbfdb644cdae02d02d722986609b91d91a36811.nq.gz
│   ├── 166ff088165d51eb87ee615234b62fd20b4ebb58.nq.gz
│   ├── 173cb9b4d56447b4bea41a7a5d3613dc11ef90ac.nq.gz
│   ├── 177f26e2d7005bbdcef84290eae377851f1d5ce9.nq.gz
│   ├── 1b617a48c4bf83e581cb67280908894bc3279577.nq.gz
│   ├── 1c17d21bcb324752f205b1988c2eb5f10283d209.nq.gz
│   ├── 26114d32947243d0778607f2400d0b75b858c3e9.nq.gz
│   ├── 2904e44856c7aba6a63da1c45a01ea0dcea31174.nq.gz
│   ├── 330bcda4b675e23beeef0ac821220cf6e150b6ea.nq.gz
│   ├── 35b8a7b90b203d0d6c54e0488a9b17d096db5181.nq.gz
│   ├── 3e75c76309c0bfcad41140379ec7412981c493c1.nq.gz
│   ├── 436ab9694cab226dfecd47b4ced35fe0706e33bb.nq.gz
│   ├── 46114eb3458ce63a724b3aca4eb92a31a508d3df.nq.gz
│   ├── 4b4ddeda880bd3de182afb3f19fc2ba499dd0112.nq.gz
│   ├── 4b8206d55db3067d463ea325fe56dccdda1041e1.nq.gz
│   ├── 5398b7f05936ddad62077a8ef9780f207a4eb3e9.nq.gz
│   ├── 57ff131a844dd33e5ae5accdb6dff2c9cbb50887.nq.gz
│   ├── 5e93213876ad643537f7eebf1d615118d0e43fda.nq.gz
│   ├── 5ee407751795b698edda12214cd34729e4a9bdf7.nq.gz
│   ├── 61b3a7d5b4830eabb5973787efa57c75c9ff377b.nq.gz
│   ├── 6e4c7410b186d29ef99e2f434a081d9762d1c6c1.nq.gz
│   ├── 6e844998ac1a918cbf36c1e56bc79dedbd289cb9.nq.gz
│   ├── 7026d9dfa6b6768ec37046e671b7b0fdce458ac8.nq.gz
│   ├── 725c0ffbd50d206db8a4e3ad9ebeff26b88c35f6.nq.gz
│   ├── 766030ad5e2cba6b237b3766467c0b4364b8cb0e.nq.gz
│   ├── 7c62331ecf6b7ac78b64b0d83460898657840b51.nq.gz
│   ├── 7e7330a3af78a3d8653cc293d65015475354e32a.nq.gz
│   ├── 7fab16d58bb72bf7266abc438100f46d12d05bf7.nq.gz
│   ├── 8c654bac59332479be10eebe31213103aa6a5873.nq.gz
│   ├── 983f75fc0a317111b381df9fc3649fd513a060cf.nq.gz
│   ├── 994132e9481e7e92942529f650034a1a720f84ec.nq.gz
│   ├── 9e2320aa0c1866facc56cbf3c8448d268fbdf08c.nq.gz
│   ├── a4ec38d144d0fb0d11691708b8878105a03c5e81.nq.gz
│   ├── a755f7486cb87157d20206a9c2aa640a86e0f119.nq.gz
│   ├── b8d2a808dd622ccefa9cb4e5f701899dc3492a60.nq.gz
│   ├── bdba0ddb45e097c9968ebd2e369474bd36fc8079.nq.gz
│   ├── c2086edecf8ece37b94ee05909ddf1cff289a858.nq.gz
│   ├── c9aaf138411c6ae724e585af3d0f26db4a6941f5.nq.gz
│   ├── d69d16e980b8d6f94e93d6d6fb3fc785171c2fd7.nq.gz
│   ├── d8df3d0fa82c32930dac30e9031139eeb6c4f93e.nq.gz
│   ├── d8f69df140d383b8c292de7affed9dffcfffd1ff.nq.gz
│   ├── df1e5644f6890b464a4e7d4c0fc5839aba9c7ec6.nq.gz
│   ├── e0e41c1953ccee8be97b1431a631662b76a70998.nq.gz
│   ├── e2fc265e9717eed93bb0c72f73d33dfc6a6e4b72.nq.gz
│   ├── e614f1bb8512b53cac3787205bb3d3f79fb7fd7f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8c6dcc3f69ebdb1ab54e57289ede8c5cb029aeb.nq.gz
│   ├── eb43a8ed4b0f8947e7b30e7dad767c39fe4ae025.nq.gz
│   ├── ee420c108781baeac012210e2c8e2c37b4981f26.nq.gz
│   └── fdddce4f84eb97379ddd344045b30740909791cb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 64201bb15021a2c6bcaffeed921c84e306d7e0fc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 62 files
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

[darvid/python-hyperscan](https://github.com/darvid/python-hyperscan)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
