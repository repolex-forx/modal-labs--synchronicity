# Repolex Knowledge Graph of modal-labs/synchronicity

RDF knowledge graph data for [modal-labs/synchronicity](https://github.com/modal-labs/synchronicity), parsed by [repolex](https://repolex.ai).

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
rlex download modal-labs/synchronicity
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 452d87532837a81d186f3edaff4c589ea800a135
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 452d87532837a81d186f3edaff4c589ea800a135
│           └── chunk-001.nq.gz
├── blob
│   ├── 01c9fc3227b4408fd2bd213cc3eed234c3e1535d.nq.gz
│   ├── 0454c7924ab71a3018a47f06ea95721aac35acfb.nq.gz
│   ├── 07195eb9787ccef945d1919e26c9f811f2225930.nq.gz
│   ├── 075c46f3485fd5271bdb026a6b2b3c2a4696fb43.nq.gz
│   ├── 07f556c758ad488d5a71c6f8750a49dfc34ec842.nq.gz
│   ├── 1197aff819f3df104ccd0ded1e246e940e99be76.nq.gz
│   ├── 1be2792d38d46477da80811087f697d68b2d5c83.nq.gz
│   ├── 1c1fd8387740315b6018d0e7b329a6650b49452f.nq.gz
│   ├── 235606a1cd63b101f091a033d2c5c3155a5b1d4d.nq.gz
│   ├── 245c3513f9d88a30305c8e4a0f39a800ee23cbde.nq.gz
│   ├── 24e0e8cc1bd1adf660717feaeefc906ab63b88ef.nq.gz
│   ├── 25d722e32719a7c78aa6575eae35b0f1357d9aca.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 36d148be5b7f7c97b49958d6896208ea4dd6e7b8.nq.gz
│   ├── 3a6207dd594d5fb862b0e985ed487208f9cbee6c.nq.gz
│   ├── 3a6c7cc72157a5b6950482fd1458475c35b84f5d.nq.gz
│   ├── 3ccc6d95884d08a0a5333b942e55095db2362d9f.nq.gz
│   ├── 3d90b7c8debe50bfd421e9104825d3cb7fd7bf51.nq.gz
│   ├── 40f5378df4fbf2d4fd5cc935cf8a6b9ad584a815.nq.gz
│   ├── 420cc3067c411b372aaf454edebac77226d7647e.nq.gz
│   ├── 4324afc42e2fe52197649b8fae1acac320467955.nq.gz
│   ├── 46b285be945cc9a8590afe09b567379d15acba71.nq.gz
│   ├── 49484355c440071bca4dcf089f6820f66a046447.nq.gz
│   ├── 4fad8fcb1c19e7b763c37adba52564d4426ede79.nq.gz
│   ├── 52e656803ba2bc8dfa67151253bb33fb674db746.nq.gz
│   ├── 610cce60b2d95113355ea12ed6d6bf0607a743e1.nq.gz
│   ├── 64f6c820347316e85a2bfd1e96963dfb2884a2e1.nq.gz
│   ├── 6c61f0cfd8aac064b4399eb66970f9905f4bf02a.nq.gz
│   ├── 709d28755b31afe0af429383ca0358849792eb73.nq.gz
│   ├── 70df70710a47a0a6b4712894c51d750379670420.nq.gz
│   ├── 71f0fceb02fb2d37ff94823d9be0606115066893.nq.gz
│   ├── 72c0ea77b15f239380dfe9286058527cb1b69999.nq.gz
│   ├── 74568b7a2574be7ab108d1bb8b17c2c1756a8bbf.nq.gz
│   ├── 76ada8d4f922765525a1d4516834d2ee50ab4376.nq.gz
│   ├── 7aaadd1d566102f12828ea9229f8ac5836c1a79b.nq.gz
│   ├── 7b004f660234abc6997c5fc43cf7a2ed25637404.nq.gz
│   ├── 85e28c948fb16681b1b104ce7783a9bab2fcbd07.nq.gz
│   ├── 901810f55ea403389f43f4e60d2d492dbd52a400.nq.gz
│   ├── 9448ebec054ff6c44a57b61c4eca9f717044dc91.nq.gz
│   ├── 95b0d99e863154d34b94a63465e7465bfc631b35.nq.gz
│   ├── 9a9a728b3c5133bdc5062a6a26522bf44b86466d.nq.gz
│   ├── a1a3e64315acd3d0fbdc65406c3a4760f35b14fb.nq.gz
│   ├── a8113ec2e77d5fbaf5acd424c4e8ff15e0402aa4.nq.gz
│   ├── a8604bf947b6a3e968b754010ffcbd1f9b1b3367.nq.gz
│   ├── b19a00ebb210001c475011a54ba23e4de80034a3.nq.gz
│   ├── ba25e87b508421687c689ad53a488885f954545e.nq.gz
│   ├── cde67ed1c6e043ececa6765d4411f53c9d0440e7.nq.gz
│   ├── ce378bfd8247e56c73c4748c508e556fa0fb63e6.nq.gz
│   ├── d3239ed272261cd5064fb819695c3a53f5a52d66.nq.gz
│   ├── d7526218ca2d666bd941be54528afc96a03d307c.nq.gz
│   ├── db97a4c0e41b5b146eedec67d57d5c5bf9a5c381.nq.gz
│   ├── df63a7aa6657ad95e7e89962d18d8c44f0e13c42.nq.gz
│   ├── e1378c5234b610981330d434c0547f30d0456736.nq.gz
│   ├── e198781f39d08e2375242520ff8ea3a62af0e41f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea947d6f344c6f1e0178c276388970f355308ac0.nq.gz
│   ├── ed7792bc96a73ce2f45bed27b8f9fdd795a97710.nq.gz
│   ├── ee471e3c1d76a18c638acd81539254cb3d393b89.nq.gz
│   ├── f62c89eee77040c481d3b4e38eb8d314d8cfce86.nq.gz
│   ├── fa3bed5d56c3885d1581a509d42e416c0aac6663.nq.gz
│   ├── fe6f23c9c6250b0992e8b2ac9c1cd1474d537e16.nq.gz
│   ├── fea30bcd585fdfe40c8106fb277407ba224b269a.nq.gz
│   └── ffe2903f0e3cf1a63f200851e66d4a24eb016808.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 452d87532837a81d186f3edaff4c589ea800a135.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 71 files
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

[modal-labs/synchronicity](https://github.com/modal-labs/synchronicity)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
