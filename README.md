# Repolex Knowledge Graph of akubera/bigdecimal-rs

RDF knowledge graph data for [akubera/bigdecimal-rs](https://github.com/akubera/bigdecimal-rs), parsed by [repolex](https://repolex.ai).

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
rlex download akubera/bigdecimal-rs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f0a1f920f222d9776584b26659a3c9326dd1aca1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f0a1f920f222d9776584b26659a3c9326dd1aca1
│           └── chunk-001.nq.gz
├── blob
│   ├── 06424f77794a3f458fab35fcdb13501fe58118aa.nq.gz
│   ├── 097cde063033621ce052a09d34b4e08bb21cc274.nq.gz
│   ├── 09a9e32f37fcc999b7dcaa2d69a1a8d2a743a14e.nq.gz
│   ├── 0a165af05a4dbe81e88e12b040859fe06f00fc5b.nq.gz
│   ├── 0f71390c331efd440209eaabcb2a24ba2c4f6732.nq.gz
│   ├── 0fe1d82ab0589098018ffbe06ed705fd0533819c.nq.gz
│   ├── 103bad0dd7db54a24b5758727c374f488a6862f8.nq.gz
│   ├── 1269e78436c4937d18291fe00a92c27d0e1d5183.nq.gz
│   ├── 13497ce8db133524e1681c7fb0086f5efb7907d6.nq.gz
│   ├── 14f4e8fe5af752e3119d47a0e7ce96f8ddf06919.nq.gz
│   ├── 1a349ffec9e0a92d4713f67c0874400fb2cdbcf8.nq.gz
│   ├── 1cf0faebe6b2a371d800f29f464d538e2a50f93e.nq.gz
│   ├── 2161eb558f002f4a89b0ef56d981d5db3575d189.nq.gz
│   ├── 24a633eeabff71cc052a9a6622067f94133984fa.nq.gz
│   ├── 26d8d7386c2bfa366f21bbb94bb3f4cfb5648964.nq.gz
│   ├── 2ab308fd23dacea9a23362ed190a579c49d9f160.nq.gz
│   ├── 2ec0e039ff09b349a376235eee7109351f34628f.nq.gz
│   ├── 2fa647b007b31b0a8a19e3c4519d1df0d2826f1c.nq.gz
│   ├── 301f099443e46171493f5b986f23d412f246b941.nq.gz
│   ├── 356ce268e3ea751fc979b07df8901a3e0163f94d.nq.gz
│   ├── 394378c21a13d44999f03a2bd46453f454699afd.nq.gz
│   ├── 3b738761c9f045cc0b3295b2627df726fe84de4c.nq.gz
│   ├── 4037aa3f385fc58aa0326f80f10990833f042246.nq.gz
│   ├── 4322302b48110526c03a3acb3aafebddb70eca6e.nq.gz
│   ├── 445713f62fda39d438989cd36292d04e7031bdc8.nq.gz
│   ├── 447dc51f782af27b541b6d1c862516a258483cfe.nq.gz
│   ├── 4497c0fe231ef8db9125019f43622b420ab1e510.nq.gz
│   ├── 4c3065cf1ffc38da6d36cef71e82f94145cbc4fe.nq.gz
│   ├── 4e4b1d4cf601f89fa8662bca845899d127c46b4e.nq.gz
│   ├── 560fb3b168489b46b541535fdf61c16afc3ac65c.nq.gz
│   ├── 563c6716e1e4f31a6f6461dbef8704fdca1b67e2.nq.gz
│   ├── 5855c84dc43aadc7fd21b0897562596ef557aec7.nq.gz
│   ├── 5ea578dfbfc49e3b7a8676a44cf69b862ae0e169.nq.gz
│   ├── 5f5b305f2f11ac213fa2e0bee696f4eebeb9e7ef.nq.gz
│   ├── 5fb6e7829f5d833729afd7e3ec2299b07d7467e4.nq.gz
│   ├── 60a7b1e46e0bbc24441e8a056321bb6a775e893e.nq.gz
│   ├── 62fd85157d0fb704195488d7604ec1bf2c6b3a7f.nq.gz
│   ├── 69bcd05c9c72b858ce275146957b6af403a18b60.nq.gz
│   ├── 6b3e9bf49d478ab3ca62d8125f985507912c0474.nq.gz
│   ├── 6d35c0d84b8806e9d3fa14cb4c40d27db07034db.nq.gz
│   ├── 6e3d2b8d8ac051240614f5a6bc092ff7de6ca456.nq.gz
│   ├── 6f4652cf04152f4e76defda0085809d33a7716bd.nq.gz
│   ├── 775ec2a86c307ce898e10cd81395ddf7e6db1f3e.nq.gz
│   ├── 78b231bc4e83615968ec9d83974d6ee4d3d8b8bc.nq.gz
│   ├── 7eceb309fdf09204d9c3e86b6a886c4ec6d330cb.nq.gz
│   ├── 802b94fb9d039906116024978578319c53ab0b38.nq.gz
│   ├── 8829b7a16715692eb399ebff987b25f44ec43568.nq.gz
│   ├── 92c483c6752d1ec037a3b8055143e632356103bd.nq.gz
│   ├── 93f275c6b4f0e67aff5d2b621143f7a8566720c9.nq.gz
│   ├── 93f2e78845d9a948873a111e12410cba3eb201e1.nq.gz
│   ├── 94844937edd8f453eaafb8cf00dc0ec203d831a6.nq.gz
│   ├── 94dd69053277971ce8df0082646d70aa0f4fa2cb.nq.gz
│   ├── 96815a0eb5f0c39ce5706be79f46e3356f356916.nq.gz
│   ├── 9d78cc794ee9583988981a19ff8275f340116d13.nq.gz
│   ├── 9f9496fb4a611a668fc6c57a2b29e7c5abf7fb14.nq.gz
│   ├── a160bc651abf72d3cdbd6ce72efc19081bceab1d.nq.gz
│   ├── b75697dcee9d5e896cbc2adf4b9ced595d135a18.nq.gz
│   ├── baa80b5b98709a3665f0fa081338b37922b9bfe6.nq.gz
│   ├── bca871b9821e937a8581e5fdcb955d60f7112faa.nq.gz
│   ├── c474ac15d0f0091aebb7d201fe477943effae8c9.nq.gz
│   ├── c54065f3666a11ff58e02019a3c7c0ca63775d6c.nq.gz
│   ├── c5ccea6dbd4d9c519a4efc50c3d1e2815555f673.nq.gz
│   ├── c9cc23f97346907e9e9f50157bfc63ac005aaa41.nq.gz
│   ├── cb2c02684575d6c5eea214ec028f4e7ec0f87af0.nq.gz
│   ├── cd72af0f276289f28fa6e26b9666b0d01d89e6b3.nq.gz
│   ├── cf44f3f7b9ef0c546a52c0c129e1edda9de1f39f.nq.gz
│   ├── d5913401e5cc80320b4bebde1fc61cc1303d7508.nq.gz
│   ├── d5a579fc244979f37ecdcfc584314c0504507394.nq.gz
│   ├── e055aff94d70da13582392803ae47792e5de43eb.nq.gz
│   ├── e3b4e1d12b5cbe680b80f0b24b6ea0d4fa0e8825.nq.gz
│   ├── e6b84b7b8bd94fd11f1046bde29ba2175db81c67.nq.gz
│   ├── edd9aeb0c75fa71fef62aee2c7d4b7081f75173c.nq.gz
│   ├── f6b7cc78a7b5e39a1e30f5ef571793f1cf855460.nq.gz
│   ├── f7ddb259710407a8524a161f25e30953a72b05ef.nq.gz
│   ├── f866d86a8fa4b2539166f3fefcf92d74c42143b4.nq.gz
│   ├── fe561ca11e5f8552ebf81a4b85e072a1bad5de25.nq.gz
│   ├── fe5a38c8339fe38d7d011817ca32c047041e4304.nq.gz
│   └── fe9e87298b2e32ebae5bc83a00afc9d87e3cc408.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f0a1f920f222d9776584b26659a3c9326dd1aca1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 86 files
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

[akubera/bigdecimal-rs](https://github.com/akubera/bigdecimal-rs)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
