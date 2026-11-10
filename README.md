# Repolex Knowledge Graph of holdenk/spark-testing-base

RDF knowledge graph data for [holdenk/spark-testing-base](https://github.com/holdenk/spark-testing-base), parsed by [repolex](https://repolex.ai).

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
rlex download holdenk/spark-testing-base
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 649d3c501facc2704027c52bede940a932fcaff7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 649d3c501facc2704027c52bede940a932fcaff7
│           └── chunk-001.nq.gz
├── blob
│   ├── 05bd3a45ee8ccb6bceaba3787967bc4f99cd79ca.nq.gz
│   ├── 0ef017a3524ad2a27cb12b77d5fe846cf957f81f.nq.gz
│   ├── 0fdeb384ebcd0aafd72d3d787243b7f60e622c80.nq.gz
│   ├── 184709775d39bdc2bcf45763508bd799bbd0466a.nq.gz
│   ├── 18614f920d52ce63ddfae58e79b0b30d3afc82d5.nq.gz
│   ├── 199066f08901d7d8de5bd1e90c3ecb9f8bef59ce.nq.gz
│   ├── 1a536c6e94b0ace7ea684582eb196b03a9b5227a.nq.gz
│   ├── 1ae22a2f8b5b56c291437d6a8db8ed6357ba73aa.nq.gz
│   ├── 206bf9a231dcc3d24d6d1256821adc26792f77a5.nq.gz
│   ├── 234bb9efdb80493384cb0fe85413833083efe72d.nq.gz
│   ├── 2b6176457f99bc78c1cb27cdf686d269b9a09475.nq.gz
│   ├── 2cc56129bd06ba83a00a098f650a7ed3d8b7213c.nq.gz
│   ├── 2d372e220019cf5d0719003c5471934431196cea.nq.gz
│   ├── 2f48e951703e4e86c23c50b4dfb5df620033ef2b.nq.gz
│   ├── 318fde5ca4b3bd5496f16f52280f138a9c4351a2.nq.gz
│   ├── 332f4bee4bcf055b5cf34227d883601dc34b83b5.nq.gz
│   ├── 36158466bc811231aee7be576159d726c0925bdb.nq.gz
│   ├── 365cfe2921d247033ba6c3fe5f9d759d68d4f6ee.nq.gz
│   ├── 36860735c73ad9a7b836e78924397fd4f492809e.nq.gz
│   ├── 38fe538d27cded9b035e924316363517106771d9.nq.gz
│   ├── 3accbf0fbc24cf425fc1f60d23821903be98370b.nq.gz
│   ├── 3c966a3c8068264ec89aa0724cbf3aa9b15a2dbb.nq.gz
│   ├── 3f559a3fe9ed408db162476b820c2e233486644e.nq.gz
│   ├── 41485e1602b437d50b3dbc48ea0d6a7509305fa3.nq.gz
│   ├── 4313245862de8c1d9064febb38556d72800d6e9b.nq.gz
│   ├── 4620b18e8b56b2ad00d660a3c62a7c3596424630.nq.gz
│   ├── 46a3d5fafe8f902f6f592c37066ea955f62995ae.nq.gz
│   ├── 50c65442252fa9208455bc8554c9a4d255c02acd.nq.gz
│   ├── 529db2f1f5c4959c479112b13a69af650361466d.nq.gz
│   ├── 5458947f37b093b1c93138811bd1d4f8aabf13cd.nq.gz
│   ├── 5767546623822cee3b34ebdda419f2432998c6da.nq.gz
│   ├── 59418643d9a56de49d469514d9f9cd6026a91ea3.nq.gz
│   ├── 59ed2cc34c0e67a2f15568e17327a414cac71b7b.nq.gz
│   ├── 5c22379907430b9186e02933ab0d947b918a71de.nq.gz
│   ├── 5c26eaad0522a4b7fa903d41b6d166aad3f6d4f9.nq.gz
│   ├── 5ed285709c5c0ed5b5bd8bbd8c2a3c4d9fa5f73f.nq.gz
│   ├── 619d517ec84f84e3ee34dc0615ab06c7c9a420e5.nq.gz
│   ├── 62159052bd61580a769e01c1ff95eb4189de188a.nq.gz
│   ├── 6352d67ca7b24f2913e9d3b67090640f0e073180.nq.gz
│   ├── 65a2a5f5363ffa36183d8e20859edfe3351da5d5.nq.gz
│   ├── 6640ffd64ec81076813b1cd558b05223607174ed.nq.gz
│   ├── 6774d496d69afb1bae1211bbb27220787e23542b.nq.gz
│   ├── 67d5f605ffb9f33f708878be187edc3d74b22921.nq.gz
│   ├── 681038b9dfca2d9498e0e29166b7c2e88004290e.nq.gz
│   ├── 69f9f07adaa20debbdd04628842606d6f8531a8a.nq.gz
│   ├── 6c5845115cf71b12121b554f7d0ecb919677971a.nq.gz
│   ├── 6c73a50498c37236f7a95f68e232e1c63d9b0b26.nq.gz
│   ├── 6cc5bcd8850f1378cea2a21552e2457800c8af05.nq.gz
│   ├── 6ff1c4fd8e5e6ec7ebe264d698718f7611313402.nq.gz
│   ├── 704fdf05747a0a2589d6eb07a540a967cf725fdc.nq.gz
│   ├── 72877aaada5fdef5372c5b35d2860d0d425672a2.nq.gz
│   ├── 728cae7d84375c7e88c8f8c72963058b36cbabb1.nq.gz
│   ├── 7388b3899d52514544a29f78e10f737f615a4dac.nq.gz
│   ├── 73ada56502f8c8b537ecf733fb6367ef4107a103.nq.gz
│   ├── 75e867c9e206397f6d65b154a7da8563adf72f96.nq.gz
│   ├── 76542e3375a40c1087bc2a0d11c922e8a0ab65b3.nq.gz
│   ├── 767a64b24ce5adadc1fea41c642ad403b5c37451.nq.gz
│   ├── 7a6934750fab6da6dd95f588326a5e2db8abadc1.nq.gz
│   ├── 7af8069002b290d9169ad2276d9d3330ff024288.nq.gz
│   ├── 7da4b7ccfefa937ceb8ff1c057deff301d5d27f1.nq.gz
│   ├── 8229a08968bf398ead62a7c62fb9833cdbfacc09.nq.gz
│   ├── 84c68965904d40a1863ef5ea643bea33487641ef.nq.gz
│   ├── 85b2fe00d0f06f68a7de2768c62ed15e256ea1ae.nq.gz
│   ├── 86933bf828269b36664507c2a1db83678ec713e2.nq.gz
│   ├── 87a4eb23417244bd1722be09c04e798e05590be3.nq.gz
│   ├── 883a38b2a03309200641307db3c246acf1e2691b.nq.gz
│   ├── 885160a21e3158ed9934f8b3b43321f53ddd4914.nq.gz
│   ├── 892116a7131a257ffa1def18af06fd311c634c86.nq.gz
│   ├── 8a6bac55864fce9a17ad22b9ed9e43c351868d9a.nq.gz
│   ├── 8ba1c85ac3ee88c9e0a1732d78babb159e0836f0.nq.gz
│   ├── 8bf4a947e792a6565ca6d9d35d7c53ca71f8fc82.nq.gz
│   ├── 8fb6672bddc4da559c0f7e6266327a7a6673d9f6.nq.gz
│   ├── 924ab4384754d598126a14a63c5d42de057ceab7.nq.gz
│   ├── 92f399d3d89d051a2519bfdc0408c38a1233fffa.nq.gz
│   ├── 94d8c003350e08b0b9c0c3d2eef6845c871d7cf5.nq.gz
│   ├── 983c3001091a12b924d1ff81fbe441868a042b31.nq.gz
│   ├── 99ad3cad69fa8325d3ee33aafcaed46b5c74e56c.nq.gz
│   ├── 9acf99709efacd1617ae14e4722adab3c8f239f7.nq.gz
│   ├── 9cb252ee0b8bb7cb32a39406bcba6425070251d3.nq.gz
│   ├── a08c58afd7687886686ee38b30fba2670ae7da85.nq.gz
│   ├── a509cbe26c2d3a6b60c29287cddd86f20f843ed1.nq.gz
│   ├── a8c72f3035201a7f1343171d52559cf7550c652a.nq.gz
│   ├── ab1636daebd378314acb78f4104dfad3a1f65843.nq.gz
│   ├── ad7405b92dee0997590516f12ca871e1c3f11eac.nq.gz
│   ├── ae9ca93fc9ca940aa4de322c5a9b6f2ad4193750.nq.gz
│   ├── afc11ccf54adb028141288f0842303d3e0532173.nq.gz
│   ├── b4594dd7caf1d84bbd0f1db7fcf20bf5c9cbe012.nq.gz
│   ├── b4d54b0fb92f31e6eb9e5372df8da0805632d445.nq.gz
│   ├── b66b2517eb8d0425580e92164373a6b179c03ec5.nq.gz
│   ├── b89c694ec8afc602b50c7fbf88ebfa52dda8d279.nq.gz
│   ├── bb8e0805922cfffba0570141a667d2094c698d07.nq.gz
│   ├── bc7f061b48a03d25b9e10bd3b3426e0c3786a6c1.nq.gz
│   ├── bc9680785319ac725a6000f29eea54632e6bcb8b.nq.gz
│   ├── be893d98434f3ecd19c642d1e2fa260836f746ca.nq.gz
│   ├── c9bf6bbb1599122c4698f0a7f0ffa2772d914e5b.nq.gz
│   ├── cb8f424627dcf8fd9ff50bb11f1fab582c15fb86.nq.gz
│   ├── cc69995a764eaa9906bba64703787c5692793c64.nq.gz
│   ├── d1dfa0fbc51045f5655d9f067a4aee205bd986ef.nq.gz
│   ├── e06d2081865a766a8668acc12878f98b27fc9ea0.nq.gz
│   ├── e1bd9e645b01c3482f4241706da5bb6dc75119af.nq.gz
│   ├── e3a5e893795ecddda026c521381112d656429c53.nq.gz
│   ├── e558457d0785f88c06b7a5444a2844daffc0df24.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7e07b19bebd8c2557537ed55e522e43dba25a94.nq.gz
│   ├── e7e5a90e959d88983919462e0f198b4b52fe2673.nq.gz
│   ├── ea368fe07e6f2603cb81fab952dd1d39e4f63d71.nq.gz
│   ├── eb4a5763b364df4f3fee2883d00f3991cc1a2db7.nq.gz
│   ├── f39273d9043b74b584fe21905ad3e99e28d8abba.nq.gz
│   ├── f5993c0adbbd93160e575295dcf1b638ae2fde4b.nq.gz
│   ├── fca101e1217c6679383302d8b0727c29f3c050ac.nq.gz
│   └── fdf22ff88cff629d02fe9c4cdcea2e25903960aa.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 649d3c501facc2704027c52bede940a932fcaff7.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 119 files
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

[holdenk/spark-testing-base](https://github.com/holdenk/spark-testing-base)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
