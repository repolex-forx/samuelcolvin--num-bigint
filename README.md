# Repolex Knowledge Graph of samuelcolvin/num-bigint

RDF knowledge graph data for [samuelcolvin/num-bigint](https://github.com/samuelcolvin/num-bigint), parsed by [repolex](https://repolex.ai).

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
rlex download samuelcolvin/num-bigint
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 14ced94a43038ddb97896e94973ac2b1056f7a46
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 14ced94a43038ddb97896e94973ac2b1056f7a46
│           └── chunk-001.nq.gz
├── blob
│   ├── 06cf1f4235a94fd858d3b4fb03ca492b156d94b9.nq.gz
│   ├── 0c6cbffbc2aebf3a7ea36997cd87bd1d4135b166.nq.gz
│   ├── 0c89bdf350c2d2d1c3910fd534503d9f73e217ca.nq.gz
│   ├── 0d3a0e2a5404cbfe0f68f4c45afadad7219ddad5.nq.gz
│   ├── 0d4d23f364e1d33469898a4f04b97a1a9469adfe.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 194855d1c3d43d5110bba81c6d34456895dfe28a.nq.gz
│   ├── 1a8fec1b9a9583a7a792cfcab4e7f2ffa38c0710.nq.gz
│   ├── 22bb7443ee0576a5f8c56ce7a4081502b46544ac.nq.gz
│   ├── 24bf4b5325ef544632531e18b24b7174c81e77a3.nq.gz
│   ├── 2925d4383f007190e0ea2f09bec90be7260de78e.nq.gz
│   ├── 2a19fafb3e49056e2e7f9d33bb9e08371b3e4d3e.nq.gz
│   ├── 2afacadc85ed63256fc97bebdec87ddb033f15e4.nq.gz
│   ├── 2ca2a4081c25b8dca33bea032716764cf01f2bb0.nq.gz
│   ├── 399bd498516b7677d4a7cf54490e45610be9a13a.nq.gz
│   ├── 39d4bdb5acd313c1a92dbeaa1c379aaf0596a315.nq.gz
│   ├── 3adbae1bb4c99c28128f5021e245c43f42f760c8.nq.gz
│   ├── 3cb90b304dc1d5b6fc0adddd9c159e9f1d59bbff.nq.gz
│   ├── 42d7ec0c47b74b8bf47c09853d48ae3eaa1d78af.nq.gz
│   ├── 457fbd3631dd7a4317f852000403d17404bc5b85.nq.gz
│   ├── 47412d199fae38afdf84a1018cd9f4ffc242d44d.nq.gz
│   ├── 502d944b78d9234ec94414d2752e0cf0a25a3d41.nq.gz
│   ├── 50668104968a5d12f49903d475c7bde7cdf4fc94.nq.gz
│   ├── 5ce6b4879d1f5937fec42a9344e6a9d3311f1d91.nq.gz
│   ├── 5e44e22d27d43b7142fc5a59c3fee1c6ba4e53c1.nq.gz
│   ├── 62bedd12cfdfa3aeb43e7e2ee8610685efa27e63.nq.gz
│   ├── 6809567db365433af5e8b6aa4d659c53882caf8a.nq.gz
│   ├── 6c476920edcc81c8f4470d4d7c11c541d2201dc9.nq.gz
│   ├── 6ec37ecb859274274521f1e1f9ccd599097ac676.nq.gz
│   ├── 7110adf904ec7d783856ae1c29606301d11bdff9.nq.gz
│   ├── 771a27c3e622ba56d50f0942bffc8187cda5d81c.nq.gz
│   ├── 7794c78574fdd3219fde683762360f4353224288.nq.gz
│   ├── 781dbf592938f8d697210e41710882dcef6ea1cb.nq.gz
│   ├── 7935e31a881c8ea184f30abb243adfa12250d10c.nq.gz
│   ├── 7a1749fdbd0c62860f592644fa76a9c70a64524e.nq.gz
│   ├── 7c34f7ef7d8eb28c49064e78eba6e2e1bf256e00.nq.gz
│   ├── 84bdf5052803f6a1f8ea66c9aa1cdcc9c386744c.nq.gz
│   ├── 85097fb0b636eda269c57e0ebd9d614461a8f107.nq.gz
│   ├── 87871a88c2c8d63bb4351395594c383599555e13.nq.gz
│   ├── 8a2439523f5b97b832c9df3b6411415cecda722a.nq.gz
│   ├── 8b61c5ed7622c13cd2186f0e1f1557f0934d781e.nq.gz
│   ├── 9064c9b13a626629be59cce5c60d1dbe7bc1e62f.nq.gz
│   ├── 918fa028bf15908c2858c98ccf72bf78b7f5d47c.nq.gz
│   ├── 94d92e1d77f91fa287d696279b264e22c3a450c1.nq.gz
│   ├── 96416020a9ba0050dc54bb094d0a34a139a16e13.nq.gz
│   ├── a147cd1864a6652530548de6bcd2cabb2755f5eb.nq.gz
│   ├── a1e7b3cf1a78356af382059182e8434e5fbfd22f.nq.gz
│   ├── a4f5e9cb23b4f511d13f7402c3133f3e60d52d15.nq.gz
│   ├── a875e424e16ad02db403dc9ca3fc7ecd22ffa7e8.nq.gz
│   ├── a87c20b2685ade3b4923b2242acbefec5bd5f825.nq.gz
│   ├── aab87ac2e85208755070c01e78a29a2e47d3f83f.nq.gz
│   ├── ab7403b45482fbea07fa6b9bee3ddf94511a33e7.nq.gz
│   ├── adcd230514126a0e4ff6247cfb8e7353fd722b88.nq.gz
│   ├── b14cd577de0093098eb09e681e83da1fe49d274d.nq.gz
│   ├── b956d81e80609a8179a623898a878c2bfe5c4a78.nq.gz
│   ├── b95d42cc40a5334adf4dd5276d5d4336fc26d6f1.nq.gz
│   ├── baac64847da51a18b94312311a1b6c1eb0ac48c5.nq.gz
│   ├── c2fcdef7b0d61ada47b2271e57bf4c0ece11ff70.nq.gz
│   ├── c8c639deed459ca59faeaafef78a30f182879c16.nq.gz
│   ├── d75f6dbeb6fe7372284dcbbd592734c6297f0ec4.nq.gz
│   ├── d7a247b0e6b1ad427f8e8aaa128e0646f89b6db1.nq.gz
│   ├── d916436ff9c49f677313bde2a5c30fde7878ebd7.nq.gz
│   ├── d9227727bf1e4c8d369edf05a6b4dee010b94be0.nq.gz
│   ├── e37586ae3d2a9fd2484f40e3cfb850ce4c111a72.nq.gz
│   ├── ef254c8963453078a860fc2ddafd4533e720ac71.nq.gz
│   ├── ef778549849c676559233635b5808fa1a8cc59a8.nq.gz
│   ├── f37c82f8b7c12c2975d59ed9f7e575b568a041cc.nq.gz
│   ├── f868778700d020bb6adbe79be71dba4d7751217b.nq.gz
│   ├── fb274922edc411562e6d3dafcd7387d576db3063.nq.gz
│   └── fea5232e040a40652363892965918ab7ac2c5bee.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 14ced94a43038ddb97896e94973ac2b1056f7a46.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 76 files
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

[samuelcolvin/num-bigint](https://github.com/samuelcolvin/num-bigint)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
