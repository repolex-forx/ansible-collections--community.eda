# Repolex Knowledge Graph of ansible-collections/community.eda

RDF knowledge graph data for [ansible-collections/community.eda](https://github.com/ansible-collections/community.eda), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.eda
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6341cc8d54755b6591ff13549133a3383d077d52
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6341cc8d54755b6591ff13549133a3383d077d52
│           └── chunk-001.nq.gz
├── blob
│   ├── 0164155b81025416095f31a4732098ec238e6476.nq.gz
│   ├── 0528c1755073b2f246bf267efe2efb905cafde4b.nq.gz
│   ├── 0815f74bbb7ed09e2c129672657500b2754bddbb.nq.gz
│   ├── 081fdbfff07f377600852e5c677829868ea19d34.nq.gz
│   ├── 0fef012122016940e749accc16c227445c705cc2.nq.gz
│   ├── 18783d51609f79cd94918ab3f228a1d485d2566b.nq.gz
│   ├── 18aea76df1581f8136f2e9d56fdd7733df37a825.nq.gz
│   ├── 1e3b279c4c6276e9322847aacf5cd0e18695d4e3.nq.gz
│   ├── 1e4614e979266f6063b148b41984f28601e52672.nq.gz
│   ├── 22c88c7b334e083b9e772b7fe88cfff54c7d082d.nq.gz
│   ├── 25c70dcd8692f65c106a016278743814527a1681.nq.gz
│   ├── 31539dc7cb60e67effd0bb6e4692d840a4e8fc52.nq.gz
│   ├── 4e8751313b123989d35679740c879a8b664bffb0.nq.gz
│   ├── 58288578ef0624e9f0fa429e010956661fe91f7e.nq.gz
│   ├── 5afbaeacfea0bc1c284327fe9807ab2c9be12caa.nq.gz
│   ├── 5c4b109783f2bd9e151a4d61ef4b2711caff5a85.nq.gz
│   ├── 5cae24f9438285bb0cd854d9e42b61299f333dad.nq.gz
│   ├── 5ed34906057e243359dd3546056aff9808004f6f.nq.gz
│   ├── 60f2a4f06b2e8efaec042599f0ef482350262e69.nq.gz
│   ├── 6d385891c9d5313040f24caff78fd262a919d7ad.nq.gz
│   ├── 6ec0da76140c01dc997b1a4b1a7f07c24cef8b01.nq.gz
│   ├── 72068173d562fa0075ce392b1ae9bce4503835ec.nq.gz
│   ├── 72d932851e5984b386f271a0fc08674aa6ab4d83.nq.gz
│   ├── 7328413cf484ea1f53b61455d5d4dee1868751ce.nq.gz
│   ├── 7612a85a4ef2d459df15e003f42921cb38e7309b.nq.gz
│   ├── 76f088b8b0ad5a08082d609e152a6922732b1f11.nq.gz
│   ├── 7c3b6bf44f375a672ca998b5020bd65a4b472acb.nq.gz
│   ├── 80e8df370c6d20458ccbded13f8792f1a31bc7f3.nq.gz
│   ├── 850a330e6aba4d0a8fc0f72cc19c5135c5d769f9.nq.gz
│   ├── 885ebcdf67e1a4364ea8fe01bbcc57120201f57b.nq.gz
│   ├── 89f6959f9c2a5abf2131d4c436495462afa35a69.nq.gz
│   ├── 8a4eef09cdead2b53fec5899bb32525b0b9d0e5d.nq.gz
│   ├── 91344a46063a8e95844fcbb6921dcec9e5778a30.nq.gz
│   ├── 9a7aac7543b8ffb00bf5b55690d79a83acba42f2.nq.gz
│   ├── 9bed430665bd0e907209675cb15b817c3d0904d4.nq.gz
│   ├── a056a90e5819e018af1cf914f42fb88a8e819c11.nq.gz
│   ├── a2463cb59d3ca2586dd1aa18fb91b50632e26a5d.nq.gz
│   ├── a5da639e35e52cf43b503e9b701f3a543c981dbf.nq.gz
│   ├── aa7f20a4a5841e9e28a06e39533788b16e7a932a.nq.gz
│   ├── af445fae7d1d15b406abfb68c1240cd64a8778d3.nq.gz
│   ├── b2c18a90c2e9878cbb90a95f8e4fa6a87ca103be.nq.gz
│   ├── b818bae18e67fcfd52def1d0669e17204905e1ea.nq.gz
│   ├── b8c438127bc30362a9fbb2420699d67558e15a36.nq.gz
│   ├── b9cbfc6d1be7e249a1f6813793dd228083d669fe.nq.gz
│   ├── c08cd6a7b7bcc4fe4fc04de3ca76e2c749491a89.nq.gz
│   ├── c1ac2cd1b4e0d1e37a94c8bb3524693fc5dfd662.nq.gz
│   ├── cff57e55cf39d80d8ce7f199edf75619c8c9cdd2.nq.gz
│   ├── cffbbb8dfa129622b4425cc3577c22991ca27d5a.nq.gz
│   ├── d029b4727bfdd4853f042857b9467697ed219608.nq.gz
│   ├── d2bd8508d084ba9705740ad23b64be9a3daa9f45.nq.gz
│   ├── d9fed47ab79780cbe41d453c2aeead8c360bf0eb.nq.gz
│   ├── dd3ca39b09b4894c3ccb4ed23fe42fe468bf0a60.nq.gz
│   ├── de1059d2d52bc7ec8dad0c0ce274be313c0eb95d.nq.gz
│   ├── e141bdfda973f46bf653617e7311214e58b6f258.nq.gz
│   ├── e1594e309373121aa70425014ef46aa1cad04133.nq.gz
│   ├── e19edc2790476c85781a9a9b484c48a6fed390a2.nq.gz
│   ├── e1cba0ca4616847acc9b59aa3934fec906f76284.nq.gz
│   ├── e32284a57a4cf5a67c8a3adac68040d87645e9e0.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   └── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6341cc8d54755b6591ff13549133a3383d077d52.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 68 files
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

[ansible-collections/community.eda](https://github.com/ansible-collections/community.eda)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
