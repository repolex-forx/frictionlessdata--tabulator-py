# Repolex Knowledge Graph of frictionlessdata/tabulator-py

RDF knowledge graph data for [frictionlessdata/tabulator-py](https://github.com/frictionlessdata/tabulator-py), parsed by [repolex](https://repolex.ai).

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
rlex download frictionlessdata/tabulator-py
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── aecfa88d7ae8c633b1f8b691d061c5e9609ad95d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── aecfa88d7ae8c633b1f8b691d061c5e9609ad95d
│           └── chunk-001.nq.gz
├── blob
│   ├── 0085e0c1a795ca29501dff5a2f0ab41cf289727d.nq.gz
│   ├── 0252882f2820ea7411fcfe87edb53cd13f93823d.nq.gz
│   ├── 0887e4d05aa7798f9c1f8b32506a292e51f8306b.nq.gz
│   ├── 097a5189931c91c0d2893b09a18847374c8d5d65.nq.gz
│   ├── 0daa886c103bccae07bf2fdb1e51e8fbdbbd2e4e.nq.gz
│   ├── 0e7ebd8bcc1b99db42a1429825c3138794b5d966.nq.gz
│   ├── 0fdbc7f44a99956fbd45d542986697ed2d8c681d.nq.gz
│   ├── 11762b2b6eb37efa9e55c7b44748458f457878ff.nq.gz
│   ├── 1182cf8d73eed5eaaa79f15c3a869b59ef9d63a9.nq.gz
│   ├── 13b51e18cb7ddc5af2ad7a28994134509a5ac5a5.nq.gz
│   ├── 14bed17352ec547c2089fbf70982fd850723d3d1.nq.gz
│   ├── 199827891f9ca45d3984063151d812733461563e.nq.gz
│   ├── 1e1e019e7bdab9ec41e9b1705b8709c64d6a1bdf.nq.gz
│   ├── 20801d18fcfa6cf942c6b4c33b2d3fafc1de4c1c.nq.gz
│   ├── 21209f5b5386043fe8b4bb4fa84fa25ff2294497.nq.gz
│   ├── 23e9c3505c281594e667e6f65cba09687cd6c3aa.nq.gz
│   ├── 24cbd547cc5b008df24908a347c850ea3f1ccea4.nq.gz
│   ├── 2686249f506f252b56788fdc855bb8a961ca951a.nq.gz
│   ├── 288c3c042c1ec3403cab37004ac2c5c4f9641bd5.nq.gz
│   ├── 29180d890dd649f332cb2d8af388399c1ab8569c.nq.gz
│   ├── 29996f60fde6f0a7db7294f78d980d29ea255367.nq.gz
│   ├── 29d4af7c8fdb8a138eba08ed172166cee6d3d4be.nq.gz
│   ├── 2e52b1b1091662f3abf9507906c2906699d91633.nq.gz
│   ├── 2fe2111f311b713e15b2c8fd805e0b31cf9ac6d9.nq.gz
│   ├── 30caa9fd6c266831986c8095ce147db7e5957ae4.nq.gz
│   ├── 3193e5284eca8780c4c8b21bb7f286c96c03dcee.nq.gz
│   ├── 32e5afee60e19432156dd729b34b2a3fb90d8bb1.nq.gz
│   ├── 355d0df1fda159a4053d24e9de5bfb62ce669c8f.nq.gz
│   ├── 3864783e4015f61a594154402409281be78a8233.nq.gz
│   ├── 3a887b78d6d61f34bb2b35d77e5f9bd1be905a37.nq.gz
│   ├── 3c6e79cf31da1c0433d2fa666bf50b53f6359f26.nq.gz
│   ├── 3c9af7ba0b9d0d92526345a15d091f2456730dc9.nq.gz
│   ├── 3ccf81a1a6daadeed86c4ccb4728ea3ce2dbae1a.nq.gz
│   ├── 3d5c27023e6d1f180bdf98a0f434a01875a72c96.nq.gz
│   ├── 412d0ca43b9bdaeb613c041e1d557f68d7580193.nq.gz
│   ├── 4376c4d54fc9f559f8e92d68f85980822228f576.nq.gz
│   ├── 45049e38f7eb37fc43c1e3c0659805200866b889.nq.gz
│   ├── 48361786876e39da16aba915454fa5018bb73b59.nq.gz
│   ├── 4854f25f3cc8d182b07e54a3b26424205a6796c0.nq.gz
│   ├── 4c1681e859352cdd0a80b952b3b5691da17d875f.nq.gz
│   ├── 4fa7e0e31312c8d85003ec89105074dd8a2db39c.nq.gz
│   ├── 4fc693d93d7240ec2fd75839157bbc5c845cec60.nq.gz
│   ├── 51571ffbcb3a7f9cd4441e1c496cf585eb65628b.nq.gz
│   ├── 601b5d99c8d390e10b86791c736f105a1a859c91.nq.gz
│   ├── 64ddacbd6c0b26c39297228a21e9f50b8aa2b430.nq.gz
│   ├── 6733975fac1c2cf4b292b160cc7bdf0e6fa2285f.nq.gz
│   ├── 6898242abdaaa874f3bcb12aa4118b6c9cc96986.nq.gz
│   ├── 6b250d5a96d37ba83e04e97ad6f308a9df940b10.nq.gz
│   ├── 6d3b8f009f87024ce726d52f377dfe86b94b195d.nq.gz
│   ├── 6d6b5ab1161024e8afe842cb9232e77a36a41bfd.nq.gz
│   ├── 6dae6aa2fff67532d6b0cf72dd42b36ae201e5d8.nq.gz
│   ├── 6dea3c537895e9ecd5f512dd14eb8c39fa3b7084.nq.gz
│   ├── 6f5147c6fac81826906c4d2036e783bfae95ad87.nq.gz
│   ├── 723df14118bf2c94a7895c11f092e636bea6a704.nq.gz
│   ├── 7342c35e53e18c38f383035594a5df7b5295a463.nq.gz
│   ├── 737ac7d7837f6e42aea6413949cee82ed7835117.nq.gz
│   ├── 73bdff7311add0678910e8b0d57d83c197004e4b.nq.gz
│   ├── 73d0ced8c12035b4cf154c87d3d98568ab27bbac.nq.gz
│   ├── 7b547ecdce6edd99deab9da038d99fbd61fe9dff.nq.gz
│   ├── 7c55b0c67c2b1f5931d973da31888ff5132ac5f5.nq.gz
│   ├── 7cb86ad655d859e133deb96b00db5bc5fd4855f1.nq.gz
│   ├── 7d8209f8ea7c49bbe0cebea96e4b09a3f92fe4c1.nq.gz
│   ├── 7db3301758829146e346bd0e4d88829d8b267ffa.nq.gz
│   ├── 7e372fd4d9f2d4858a10831794a84f14bcd82a6c.nq.gz
│   ├── 7f36ea2272e5c0d6908e10c7d481aaa339ed19a2.nq.gz
│   ├── 841795dae2007efcb61a3e5e6ac8759dc8a869b2.nq.gz
│   ├── 84c4636081887ee0ca4531d90b2a4c4218f04b55.nq.gz
│   ├── 87512eaa42b6f779365261af338ab7fb7536fbff.nq.gz
│   ├── 891be98e428a66e541e1149d1838ea3e2ce82402.nq.gz
│   ├── 895affdca5d82bb839072a8bf579e39ee63df6be.nq.gz
│   ├── 8b1db260d72dd585414727437c11eab099bf84a4.nq.gz
│   ├── 8b68d312886b4efd870ee117619508c4d89e6657.nq.gz
│   ├── 92463af74c6bb90e31f127d66c5c2ae7352065e0.nq.gz
│   ├── 93dbab3fe1cd2ee834cba72317e8ed996a2bd4c0.nq.gz
│   ├── 993517cc01b717620082d2d88f3e62bd1c56a467.nq.gz
│   ├── 9c55441d2476d15d4f897d5d1e313636c320b48d.nq.gz
│   ├── a189b43262837e80adc644d2549ce4bd5453b50e.nq.gz
│   ├── a1dfe2106e676e241ad5902497a625aad19139fe.nq.gz
│   ├── a1f9dc825e18d3c87b48eb9d594f723fb7863014.nq.gz
│   ├── a32ae248177ffe59d4d7ada16a06d62b8c25a948.nq.gz
│   ├── a527dedd0ff87d7d38137cd580482a0a5a906a48.nq.gz
│   ├── a90134c72a69c6c1f7d511123046b44f1ed31e2b.nq.gz
│   ├── b3eb112917ac0b95570f450ffaae559a5a2281ab.nq.gz
│   ├── b93e5a2e2373736e21c70db4230b173f976c4879.nq.gz
│   ├── bdba8c0214b68b1e9d8b275b36b9daa4468d4c1c.nq.gz
│   ├── c8df181d9d5979b1fd38789d4e868070367afd10.nq.gz
│   ├── cc7278093cce88f10c3348a9c45df31d31c1be14.nq.gz
│   ├── cd69f10e4b0f438534a30c9c636149fb1c7a4edf.nq.gz
│   ├── d172434cfd552e80fc161e5cc8e4fc4c937c9a97.nq.gz
│   ├── d1eba97af311d0718fb58ea924ca602e97dbe81f.nq.gz
│   ├── d5792919ae6da696e7b4eb4718fac6b1504af441.nq.gz
│   ├── dc0f7842e7c6fb9e3e687ed173624957a9c3999f.nq.gz
│   ├── e3040361eef0f22e7e7cf707c31e51b24d068003.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7b7c653a25d60e5d3702e9745b84ee6b24236b7.nq.gz
│   ├── e8b747f77f1d8d1677a84755c4ae2ea01454ad6a.nq.gz
│   ├── ea33f91df0d13350b5072a84cd8dbddd92612e92.nq.gz
│   ├── eaa127149648dd83f13451baa8b55e0a35d1cd6a.nq.gz
│   ├── f398ec9b2632e3b1def304f300f028668521aa6d.nq.gz
│   ├── f9de8c71e8e0a1ce436c8e298c7367494cad495f.nq.gz
│   ├── f9e26b8c6d1ac8196662f66b7494ec5b85514bce.nq.gz
│   ├── fed61133cddbeb455ed3b8678913abab80b9f70f.nq.gz
│   └── fef4af7b6fc0a8ed3b6b58068820ac4e8acb494d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── aecfa88d7ae8c633b1f8b691d061c5e9609ad95d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 111 files
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

[frictionlessdata/tabulator-py](https://github.com/frictionlessdata/tabulator-py)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
