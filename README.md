# Repolex Knowledge Graph of jazzband/django-embed-video

RDF knowledge graph data for [jazzband/django-embed-video](https://github.com/jazzband/django-embed-video), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-embed-video
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2b644987acb178d9113854b0c370b178a3a67a5e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2b644987acb178d9113854b0c370b178a3a67a5e
│           └── chunk-001.nq.gz
├── blob
│   ├── 00de8e9a20175e920b0ede1d03f99864d57dadce.nq.gz
│   ├── 0634409c3870063f47e43b6bf244a2cdabb96a3e.nq.gz
│   ├── 0892f67d50c701a486e88ca8e34998c7f268cc28.nq.gz
│   ├── 08ac87be39edaf3bcb9c727a39fea042ade63c90.nq.gz
│   ├── 13f35b10021c7ff2488c350a3b324619418ec737.nq.gz
│   ├── 17da1d508f2ffc63c9b433540e330dee8c7495c0.nq.gz
│   ├── 1aa86b62b78c125012c3977777d8f7b8a3475489.nq.gz
│   ├── 1b964165b74b00bb0c63fd830a241b19068a28af.nq.gz
│   ├── 1be064176be50aa458d2fd5edc26095cedf87fa9.nq.gz
│   ├── 1d54e82e3f62bc804a7b13923f01d70ac74c3375.nq.gz
│   ├── 21cb3e5212ceebb515a0bdfe48c2dd5ffc9aa819.nq.gz
│   ├── 276e6f33f91c9f7c969f52c2c933c4dd3e5b59e2.nq.gz
│   ├── 2ba1e2cd610047a862218aaf1f18fc4a4e39cf19.nq.gz
│   ├── 3284d6debed4df49e6103496c051381e4c88cd8c.nq.gz
│   ├── 34bfbeaa50bdb9624727f1f0421b6b9d38409afc.nq.gz
│   ├── 3c7e14b922b0602783d667c5420d86e244fd6813.nq.gz
│   ├── 3d8f8a6e8acfd38d4c66a9b4934d5ef19c6da1a1.nq.gz
│   ├── 446345b315fbe37dabbc661a4a0a7cc28ca1e599.nq.gz
│   ├── 4dc0168bc39966d56dbb6ffc6bcc52f64f0d67a1.nq.gz
│   ├── 4f755197741e9e18bfe05c736d2b124977504245.nq.gz
│   ├── 4fad3f96bf965f9df0605dac9cb263afa60bf7e2.nq.gz
│   ├── 501deb776c16733b19f3509d86e125df78958261.nq.gz
│   ├── 52ab193e5fedac563693e51727a02ac3a84b333c.nq.gz
│   ├── 56bd843acb5fede3e8e813e33aa95426eeea8f99.nq.gz
│   ├── 5acdff0fa3cc64ab4d79c18152acecee088cf5c0.nq.gz
│   ├── 606158399eba552344b9346ce41c8dee95a77f6b.nq.gz
│   ├── 64a20bee51bfb9b2b4084a81701b321683c6404a.nq.gz
│   ├── 64c79a6d1a1160a18547007dbb9dd08a30a593b1.nq.gz
│   ├── 69468c90269c997cd77dc4ef00a0bfd98218e042.nq.gz
│   ├── 6a0a9b45edc3a34a295a9ed04dff07b314b8536c.nq.gz
│   ├── 72f2347242883c546d3780f906327da70bad0492.nq.gz
│   ├── 752afecee0beadf867dbe1b7a6b9a29da8d00a70.nq.gz
│   ├── 776dc1d00497d4d47aad5579e20dbf5762e16dcb.nq.gz
│   ├── 78745c274bbf1b1374bc75bc17beb5ca5418a77f.nq.gz
│   ├── 7960e4ba57ceb2638332c5f90c2f6b63e94fe60c.nq.gz
│   ├── 81b52dfa115764b849affc4dbbb88a2ba3d16275.nq.gz
│   ├── 85d6efef228561ba51d863a6bc8ee10ab5d08652.nq.gz
│   ├── 9763e12ded802c1d7bea09a446ab0938f54dbedc.nq.gz
│   ├── 9eb904bd8bdf3bb7e8b2e2dfd5dcf3b5d16d4a50.nq.gz
│   ├── a490f051c6cc77b1cdfcdea49c8a08e66de36fe9.nq.gz
│   ├── a4c625a20b6a54a4d7183650018a87dc6d81fc1c.nq.gz
│   ├── a7e6321152c7629640d7d9a77e2e234080c18eb0.nq.gz
│   ├── ae039426edea64dbf546113b90b9a2f109296c1b.nq.gz
│   ├── b28eb54d197934832cb4dad81ea9e99d35ccc775.nq.gz
│   ├── b5fbce98b6caa852a0ab8c55c3cd23007664415f.nq.gz
│   ├── b6327a0d3131ea794767dac91fbfb28ea3c49fe8.nq.gz
│   ├── b78e3c3ccec8173b5743dc9bd45462f12585c83d.nq.gz
│   ├── bd3ff91cf65a254f4f9c62e704569974a8ac7af3.nq.gz
│   ├── bdd1844853662a185c7477882ea9609ff8246f83.nq.gz
│   ├── bffcc19901ceb00338e51330c4108aa8421ae7e9.nq.gz
│   ├── c3035d280c4764ca25f56f2321b1cfece6daf997.nq.gz
│   ├── c78d08dd9bc126d358a8acd97dc8cd2ed87fc3bb.nq.gz
│   ├── c7eafb3ec31aba64ad15352c48852a0f0abd4b91.nq.gz
│   ├── c835aa43be9892315b413eab3ded20e4bbba2601.nq.gz
│   ├── ccbcdf9bfa928c87ad1bfbec0c5becbeae2a4e72.nq.gz
│   ├── d1a7de70a1bba98489ee1b9aab02563fa98472aa.nq.gz
│   ├── d37523fcaaad97477245eaf2b8698b6a928cc7dd.nq.gz
│   ├── d875990a530c44777f820a393766036c412248c4.nq.gz
│   ├── d963ec0e59c51169902238eb63bc733d1c870b97.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── dbb049168ed71706d12695ea2427399cac55bf3e.nq.gz
│   ├── dff4d364328b9bff7158dd3da257fdfd1fd65e11.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e212bcdd1a99f331723126cb38055f1dccfc0161.nq.gz
│   ├── e397ac62a0d15c1d51fc9da420066b9e8943d8eb.nq.gz
│   ├── e5192218bd20c7f0501d7d8463842cceac2437b2.nq.gz
│   ├── e57a5a5ff64ce466a9057fce8f570dd6d32d593d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eea743d395454e132e089544fd560f707d72f58a.nq.gz
│   ├── f4c3ddf2c7d53fce5b27562848c7ec7e7338fdbf.nq.gz
│   └── f7e1bd7147e04b8f7df4cfecbcac5189b8c6e63f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2b644987acb178d9113854b0c370b178a3a67a5e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 79 files
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

[jazzband/django-embed-video](https://github.com/jazzband/django-embed-video)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
