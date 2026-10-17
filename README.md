# Repolex Knowledge Graph of spacetelescope/costools

RDF knowledge graph data for [spacetelescope/costools](https://github.com/spacetelescope/costools), parsed by [repolex](https://repolex.ai).

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
rlex download spacetelescope/costools
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5bf5eb61778ffc121186e0633d52ced30a4da2e0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5bf5eb61778ffc121186e0633d52ced30a4da2e0
│           └── chunk-001.nq.gz
├── blob
│   ├── 02aaad122aea3a52eed7e8f8b46583690301aeb3.nq.gz
│   ├── 06a764db4f020b0d644ddd2c254b520f966b5c57.nq.gz
│   ├── 0bdfcca5d259ff5e825e9e0ea9e0745fce8e35a3.nq.gz
│   ├── 10aa246601903e71e6d634764b7476a35d2b7d5d.nq.gz
│   ├── 12d14d0a97d262786b131926f9b7c4d668a9d374.nq.gz
│   ├── 144294093d4c239a584a09d055cec4278fb0c848.nq.gz
│   ├── 16af96ff435ab8835c05a2350350ce3666bcbe7a.nq.gz
│   ├── 1cb851eb1464e027a9871d170a1230636fd80c7c.nq.gz
│   ├── 21ceb7085022163058c68e9872428d200f6459b7.nq.gz
│   ├── 271e4b9a423c7ebc975cdafb09913f77d52a52d2.nq.gz
│   ├── 277254e86b696a9142f5dd24591b22b46e773992.nq.gz
│   ├── 3d13032bb54e181d86b4b6110c62f8f6139b3441.nq.gz
│   ├── 3daf865824729a9d7dce805ab386ab967709b774.nq.gz
│   ├── 3f306d86b6cd55a3367fbac3fc713d329cc39bc3.nq.gz
│   ├── 6361ed232136c0d3b7a3590399ad4b87aaa839b9.nq.gz
│   ├── 6cb81b0c687686056c0f8fcb230c3fba62adefca.nq.gz
│   ├── 6e36497b8d2c79dcf5b5aafa83888f6d77cb4136.nq.gz
│   ├── 6edb9198007f6c466570cf7c6a01a5911b40c0aa.nq.gz
│   ├── 74b9c5ed33ed0f95b99df953942dd05d4f1c0628.nq.gz
│   ├── 77392f5b66896ef64d791b2fdbf8505b7887fa28.nq.gz
│   ├── 77a4de2c8e8abdb0a916da5d9eb8cb9f121e8646.nq.gz
│   ├── 77c7ce98cf3e27ba060e1a869a253865a34d6f72.nq.gz
│   ├── 7d3f8beadeadbb95877a0d3706b785a1c387659f.nq.gz
│   ├── 842ffc5061277c61f476c5d97634826aa84b125a.nq.gz
│   ├── 85ebd22ee47b8033393716dcf473b5fbfb20e764.nq.gz
│   ├── 87390c628eb75b4b99b24504b052f60829bcf9d0.nq.gz
│   ├── a3c972d6cb25a2c1b5e1b06e67d483bd9cdfcd07.nq.gz
│   ├── b447b8cd8986a8b99b5ecb29f58cab103fcb6807.nq.gz
│   ├── b701ed3aebdbd1b364a4df4cb135af1f28b61913.nq.gz
│   ├── b8753cd751c17f7100d48a17dd83df004341d4c2.nq.gz
│   ├── bcfccac836b50cedc17576b6aaf0a7d32b952fca.nq.gz
│   ├── c553771c9dbef4979d57bd0a3a9b23d134d16fe4.nq.gz
│   ├── c6ec824776f160e382936e6a2c967483bb46f700.nq.gz
│   ├── d0e4d9e5414ea2005c290ad8a90598c7376eedfa.nq.gz
│   ├── d5d7b33664ad1d14bf1d36384479e880093a29b9.nq.gz
│   ├── de68ef680ace4820d5a85598ba97e7096c4aec3a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ebfc6acccab0d10ba8aed9bbd07cb38b0305c113.nq.gz
│   ├── ecc3a93dc21fe4244c40a4718a59c660c1f9e80a.nq.gz
│   ├── ee76f381f17698902e4d2c803a632d77318aacc9.nq.gz
│   ├── eeb3f5f29dbd496f9bbdd4d1bbcdda8bed66e722.nq.gz
│   ├── fb04673fb595a0bd2b4edcfdc5943116587aa526.nq.gz
│   └── fe06eccffcc48c38f6acf625ec6aa52ccb550483.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5bf5eb61778ffc121186e0633d52ced30a4da2e0.nq.gz
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

[spacetelescope/costools](https://github.com/spacetelescope/costools)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
