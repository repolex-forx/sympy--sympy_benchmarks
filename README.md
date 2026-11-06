# Repolex Knowledge Graph of sympy/sympy_benchmarks

RDF knowledge graph data for [sympy/sympy_benchmarks](https://github.com/sympy/sympy_benchmarks), parsed by [repolex](https://repolex.ai).

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
rlex download sympy/sympy_benchmarks
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3a6f8897c0837c628a0cdb8a20663638b5de53ed
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3a6f8897c0837c628a0cdb8a20663638b5de53ed
│           └── chunk-001.nq.gz
├── blob
│   ├── 0043eda2cf9ef3d56e97154ce072a25ff024d3fa.nq.gz
│   ├── 03935e0d753e2958c34b9eda1c8fd76c9047f1cd.nq.gz
│   ├── 061204d526e42fbc18a5e86f560b39ad3ace0593.nq.gz
│   ├── 0dae800277fc4f689c4d741f0126246b4f4448e4.nq.gz
│   ├── 18440924ab9398b83eb437b6a4468be20fff4f2c.nq.gz
│   ├── 1845563e8c6a2924c8f361cb29d1230d693a7a1e.nq.gz
│   ├── 18854876c67fdee2dbd3d0448dc69a530d5f30a7.nq.gz
│   ├── 1ac8853120354cb21291b0f89b11fb83044863de.nq.gz
│   ├── 20ead3924feebb1393f959820809d3e2a04cb92e.nq.gz
│   ├── 22b6043a1dadd98cd7804e11078116ecfde24a57.nq.gz
│   ├── 2a1ef6c2a1af3160d5f2c18effeafc7bbd95fe28.nq.gz
│   ├── 3056b0663551482fea412248b48efd8491afd3ad.nq.gz
│   ├── 3167485f25b4f59c16da8f6ca91eb6042963f977.nq.gz
│   ├── 3372247065fc86a0309617b55fd3acba603954d5.nq.gz
│   ├── 38db7da426bba9e5195ba03bbc18ad8749010f9e.nq.gz
│   ├── 4120bd68ee577fba85fc8a68585bc4e780fb2417.nq.gz
│   ├── 428e69adb4afb331c02ae5958bb245c08e1aa50f.nq.gz
│   ├── 4508554b92e67484568a4dd03202dfb6336ed23e.nq.gz
│   ├── 4b78f38dcc2df32609edbd1a1a97bd819615f1ab.nq.gz
│   ├── 4d8d216f78b68551f49863965d37c275ae51af2b.nq.gz
│   ├── 5ae0a1474e25d9fac14be2024c7ecd6c0804def4.nq.gz
│   ├── 62d6cde8e7401f6e0daf0a990188c9b83f1cf735.nq.gz
│   ├── 655c61a58afbd87c6c2c176b43478a98e11dffd3.nq.gz
│   ├── 65ea262d9f1481796648c065110aa2e9c50a1635.nq.gz
│   ├── 68e8929c3a5e762969202f3ca525399c75631175.nq.gz
│   ├── 6cda883b0b92f02a6215f347e94357e084d51798.nq.gz
│   ├── 6e2fa64887440fcd79f0d4f9035783c1fb025629.nq.gz
│   ├── 70e0ab82a2bfd126878a75bfd009a9eb4d465ff3.nq.gz
│   ├── 74ee4f005fc882661c03d1b3ff80517030e4b451.nq.gz
│   ├── 7e589dc060972f5328cfd23db7292572e2316ae8.nq.gz
│   ├── 821d6aa6a402cfa6f1a502aaeafa1cd16d515448.nq.gz
│   ├── 8576b72cda1335ac1a85513b89bde54e566e083f.nq.gz
│   ├── 87c2122fb0476d6d86129ade6bd9e480a13bae40.nq.gz
│   ├── 87e656305f3fc89e8ca90e13d47544ba49873c63.nq.gz
│   ├── 8a9bf9ae0ef017c92d5a36bfef999926706aa99d.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8c7f22b028cece487e394929c80ba68d37a6050b.nq.gz
│   ├── 8d00b9b2188f54ce1bd95e4af7693bfa57d990e5.nq.gz
│   ├── 8e66762afa3207ef52486a5346d1bfe96784b9b4.nq.gz
│   ├── 9e5af21897a43a97e66266cef7eaea73a78d77dd.nq.gz
│   ├── a0307cb6c3b68d6b6d2124c95a9e1ec01033b63a.nq.gz
│   ├── a4a39dd4c472cba878ff0f3c38e30597567dea80.nq.gz
│   ├── a57ecc3db6f88a1977a8727d9dfa8ba01df92a30.nq.gz
│   ├── a73742fab8d2c00ea44b3a5178e3e5cbf7591260.nq.gz
│   ├── a8de87dbfb7548a603fc6980b297867644f0d150.nq.gz
│   ├── af3e5e76cb0306e8fbee6a7e08c5474133d72b9d.nq.gz
│   ├── af727d6960cc39f2f84f7b25159cdeb17e299499.nq.gz
│   ├── b3ea7737f91de10a0d03a1185b29c923752738c8.nq.gz
│   ├── bfc667e0114b6ee362dff5b83d2801ebed160fe2.nq.gz
│   ├── c055131ecb494c4eb45f1da379780007c3742fed.nq.gz
│   ├── c134958a363308e95582afca1471ee1449339475.nq.gz
│   ├── c483e47665fda2f21242f105b761ff7c9d851ca3.nq.gz
│   ├── c75c9bbbfa99a68fe68b4694e670de0d11aa68db.nq.gz
│   ├── c7f5bade184083f88147bf55174496208b0a1071.nq.gz
│   ├── cb5cc87625b74bc74ba6eb30fbec2cd3dc9148ba.nq.gz
│   ├── cc33154dbe840f377c6004829cb817f78532bcab.nq.gz
│   ├── d77d0862bad31a99b5a6d523885e2c43741b2d52.nq.gz
│   ├── e26851b0bd3d66ab155cb2ee4e173b7b77d60157.nq.gz
│   ├── e3ab4af1b8d6de770a036e6cf02d57f27e9b0659.nq.gz
│   ├── e585dafcbecf239bff84883949ee75015eba18b2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7746169c3d2c0d5ac5d34fda52f9dfaae9a482a.nq.gz
│   ├── e9c86729f904e5e0aa89a91195b6e39376fc7b85.nq.gz
│   ├── ea5bcd8c0baeb32521f6a1c8dca77722dafc82e6.nq.gz
│   ├── eb2792af3c9d753a8e10290bc28481028c974505.nq.gz
│   ├── edc143c4d73f728dec73e7ff60c23ebac4d00ebd.nq.gz
│   ├── f156d946252f8bce9187c068fb7994981206fa59.nq.gz
│   ├── f5ebb269e599530eca9dc71be6047b239d22fdf7.nq.gz
│   ├── fb0f3a8cb4dafd9071c4b5e0dc8a40cb367136ba.nq.gz
│   └── fe4f32be41f79e91725805ca17da2285dd5f6080.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3a6f8897c0837c628a0cdb8a20663638b5de53ed.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 78 files
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

[sympy/sympy_benchmarks](https://github.com/sympy/sympy_benchmarks)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
