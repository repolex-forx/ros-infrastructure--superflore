# Repolex Knowledge Graph of ros-infrastructure/superflore

RDF knowledge graph data for [ros-infrastructure/superflore](https://github.com/ros-infrastructure/superflore), parsed by [repolex](https://repolex.ai).

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
rlex download ros-infrastructure/superflore
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 03508a6cec0c8646025c73baf18306a05b720549
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 03508a6cec0c8646025c73baf18306a05b720549
│           └── chunk-001.nq.gz
├── blob
│   ├── 01cdf05262dad905984fce00899747bb5de88129.nq.gz
│   ├── 040e8486ea9536a743f8b9958f650be4b61c7d13.nq.gz
│   ├── 06eb4a682a04c8154f41e677e17fd3298e2bf2db.nq.gz
│   ├── 0af460fa013e5444a5187ad06695cf4321c06aab.nq.gz
│   ├── 1253c370d1ce35e309869cab1cca6baa899195ee.nq.gz
│   ├── 184c984f9de840be91f5180ec7d021fadd2a9f45.nq.gz
│   ├── 186012da0b6b6966dee4eebebc86b481c09a32e2.nq.gz
│   ├── 196ae0b2b1dbc33185b842764257208e027a99f9.nq.gz
│   ├── 19f3abebbb88d90b1b416da8bb74a51fa8efca98.nq.gz
│   ├── 21859bd70d61e7aec15e23066e60140e29fd015d.nq.gz
│   ├── 22149e3c205acc56a14734e4cc25e8f690be6093.nq.gz
│   ├── 272d4ee93c5eade4145685c5f930b3b5b3bce73f.nq.gz
│   ├── 2a5d1ab1e7f96eca71ffbd06d05b756d65ed61ea.nq.gz
│   ├── 2c8f7391ee541ac4725d6973c29ba4d1bc5b448a.nq.gz
│   ├── 2d22fdee24e15e16edec8f2d71bfd9705fdb4e97.nq.gz
│   ├── 2d9e9f12c1347fcce06ce11f142ad5a8cc98da07.nq.gz
│   ├── 2e90ea3df2239c2a4881d70421c95ed5520063ad.nq.gz
│   ├── 315ce27a3b7c4d1a02e201eb369bb3f2f194fef8.nq.gz
│   ├── 5e40da76401c26ab505e59c55b4138abb26b632e.nq.gz
│   ├── 713fb0db35809d3ea148e7f4a243493e796c3893.nq.gz
│   ├── 714c101ec7d1b9212cb9b4d80a7ba591fce18cd4.nq.gz
│   ├── 72d742ea3f4083d940a0316749f4274e6290fe60.nq.gz
│   ├── 74e91d3442045b95e7eb41e11956f690319c0724.nq.gz
│   ├── 753a112ffa29fc4365b5568e71291d2e16bb1ac1.nq.gz
│   ├── 762e6654d33d8ad7b2189ef941be2e8b6163beaa.nq.gz
│   ├── 7af3ad5efe32ce8b8963cdf37ce86a629d06933b.nq.gz
│   ├── 7c4ca0c2d1d10f1aa867513383c9dd348c68df8a.nq.gz
│   ├── 85785f5891c62378381ac340a0554ee67ee56a70.nq.gz
│   ├── 87032d60ed17c3dd882811e8faa7d1ebd319428a.nq.gz
│   ├── 952e87f2619bc196927147673d6cd9101f6e9718.nq.gz
│   ├── 95df620b09a6e9fafa78571deee3039f629cb8dd.nq.gz
│   ├── 976b6c88da317fe47025aa94d51e378152980555.nq.gz
│   ├── a096350c938992882e53c2c313498777f13edf91.nq.gz
│   ├── a1f956d5f2bf67dbefbee307e4ea446f23fa6f63.nq.gz
│   ├── a28c9f4c26a8626971441586d0156cb635ad9428.nq.gz
│   ├── a3abae905add00e8438c5811c5d66fc8936abbff.nq.gz
│   ├── ac8965878dc387f5bea45ac6059b80e56fab31e3.nq.gz
│   ├── b2d5529ccb089350640de7c3e9988b53373aa59c.nq.gz
│   ├── b5648d4b260d1d5e55607a51b0dc06948b1153d5.nq.gz
│   ├── b94dba79eabd3940f5af7c99e780f1bdc6691b6a.nq.gz
│   ├── b95c42b8fc2f852517b050b82308028a4d94afdc.nq.gz
│   ├── b9e9bce8da60d1686460bf55a253043fdffbdc37.nq.gz
│   ├── bb91b6abb36c0633ca75ef925a2802ab39392ead.nq.gz
│   ├── bdaddd14616937e08bc1aca4f1b0e68ce15d0892.nq.gz
│   ├── c31dfa7cce435e50142f6b6e140e151c0cbc9f55.nq.gz
│   ├── c4dabea0082126e46acc04260f49374b29da00fb.nq.gz
│   ├── c6c9377bf17baabb98a1ac1e017134df86153ec0.nq.gz
│   ├── c8cb0ddfd3d8aa404fac26e2c0e1cc72351e10cf.nq.gz
│   ├── cacd0a78049f038f66c2d0ab8f8d7406b511883b.nq.gz
│   ├── cb0f5b5d7f6de2ef6b03b2f7f7003a5f53b35318.nq.gz
│   ├── cb74036499668a710f5e23bb0eb133543b2635e4.nq.gz
│   ├── cd3ee03ae799dffa6d9ed236fe9d42d0cae25933.nq.gz
│   ├── cf2e26288c1e202aadbbdb7cc91375552bf54c98.nq.gz
│   ├── d2f41209ca36baba28b9e3e7c4f3f6124904aa30.nq.gz
│   ├── d3e3430143e605d1aa2965fe9991e16244783130.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── e096e6ec78a803480096cebb565cd06633531da6.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7213fdcbdea4484999776188151654408f329d1.nq.gz
│   ├── e8874c8e3fa5f599eea214473046f2877ba3d2de.nq.gz
│   ├── ea2345e320a9dd699912530960a623a3a6e1aaf4.nq.gz
│   └── f89093c7e462d08f7add4d1e821e2273fda0b8de.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 03508a6cec0c8646025c73baf18306a05b720549.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 70 files
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

[ros-infrastructure/superflore](https://github.com/ros-infrastructure/superflore)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
