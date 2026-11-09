# Repolex Knowledge Graph of micromatch/micromatch

RDF knowledge graph data for [micromatch/micromatch](https://github.com/micromatch/micromatch), parsed by [repolex](https://repolex.ai).

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
rlex download micromatch/micromatch
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8bd704ec0d9894693d35da425d827819916be920
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8bd704ec0d9894693d35da425d827819916be920
│           └── chunk-001.nq.gz
├── blob
│   ├── 022441874e76373050c6bdd1a77c8050ba3ad2b5.nq.gz
│   ├── 0453af67569ac632a4bc686952a101077f58c913.nq.gz
│   ├── 04fba9485a8f5464273abf7614858a06ba9a3e38.nq.gz
│   ├── 060f85e845dfa9a81c569f8e040d2396eb9ec9ee.nq.gz
│   ├── 0a33c3ab31a1d46fa4f0376bd5f86edf20d2c261.nq.gz
│   ├── 0b80e5d092369c7a96b0f90a081f85d2fc2b610d.nq.gz
│   ├── 0eaed95db4865a3eaced1f55311334241c40adc2.nq.gz
│   ├── 13db44950a70c250307013484c068ac5338216dd.nq.gz
│   ├── 14777bbbbd9c4ec7d7e68f8086fa90108530596d.nq.gz
│   ├── 184457e6a199b56c1c6a89abf7d063cf6b267a75.nq.gz
│   ├── 18a7c441aee8ff23a33af18784ef58df991e81fb.nq.gz
│   ├── 200d32f493685c22cf1d9bda22f1d0ca3e3c62cf.nq.gz
│   ├── 292a5e181788b01ebb9a684de8393cb2d01f5f9d.nq.gz
│   ├── 2a8aff7cf7b66c07986751c402084f7a9bf967f7.nq.gz
│   ├── 2bac331e7f9a915802914bce37c135a93f09e9c2.nq.gz
│   ├── 336b01936a491f29dc2914cc570d8a00c9f2018b.nq.gz
│   ├── 34adbe5ad184f07588d3cfa6bd8fd4bb3699e6f3.nq.gz
│   ├── 3ecb202fe1c9463f41fefa9b2753aaece65b35c5.nq.gz
│   ├── 43c97e719a5a824700932f72e6e7e6748ce45d01.nq.gz
│   ├── 4c4d0eeac62a23529033875789d4b61ff34ae5aa.nq.gz
│   ├── 60e76fb9adbfcfa690b5df5e4c25f7239a4438b5.nq.gz
│   ├── 660957e70cf2a2affa82417f757eb8d6fed0d23f.nq.gz
│   ├── 6e5290ecaa2ede7766097aa9550a3fdfa341b375.nq.gz
│   ├── 7299063ccb231478ec6018e024f742921c8988f9.nq.gz
│   ├── 76c11c369e4b1d8b420cb36f525205dad78c6552.nq.gz
│   ├── 773cf1cbfc0d639310b10e0a81fdf8d6c242562d.nq.gz
│   ├── 77cc70a4f897276902ad4a8d064d2f65be3c29b2.nq.gz
│   ├── 7b55d32895ff1d9d3c77426cceb9e7427a383cec.nq.gz
│   ├── 80065c8f246c45cea1b364de1cac7d6695afcbfa.nq.gz
│   ├── 80d0ad66e65fc6cd89b79a8b250564b99f396315.nq.gz
│   ├── 85459fa92296e8ab8abdcd9c50ca5286a6bf6121.nq.gz
│   ├── 86e102887e108eddc7427b6744a0facd67a48424.nq.gz
│   ├── 88020d806f3879b62322f2222ced9ecaa2b2bb4c.nq.gz
│   ├── 8b45823541571431096a70a869e8832ec6a0eeb0.nq.gz
│   ├── 8b8e426ea90b4fc9107d93fda9680ce32da22c61.nq.gz
│   ├── 8cd1883b96512865dc394dd6e69b9d461dc6dca6.nq.gz
│   ├── 91109443d5fde7bc7293fd774f2a4972342686ae.nq.gz
│   ├── 9198e561cd5e93e9c7e543677d078c4bb64e14ae.nq.gz
│   ├── 92ce44a3b27a0313f218e6636fb08f3a106a1385.nq.gz
│   ├── 955951425bb65aa2e02da3fbcafacf6cadbabde2.nq.gz
│   ├── 9a39632b7da700fde7c510b7020b7af0c8ca548e.nq.gz
│   ├── 9acc2acaf838d80b1554dde9430177515df997d3.nq.gz
│   ├── 9af4a67d206f24ecdbb5fdff2839041ca0bbd346.nq.gz
│   ├── 9c4c496b978a80a6dd7783f8a3816754f6900b17.nq.gz
│   ├── 9e0889929d7742d488abc85222bc4244a105b5c6.nq.gz
│   ├── a6a24c9d6c5b7867b3abee4be7c74a29b487df73.nq.gz
│   ├── ab25fcef498eff03f62db074c5d4938b8256a807.nq.gz
│   ├── ac0c804443ee72b430f7e39438ffdacf3e9c370c.nq.gz
│   ├── b38675946e1f81900f2b44885d83b1129f87bc3e.nq.gz
│   ├── bbaa5aa7029b0ad10719dad348072ec64cbb3ad5.nq.gz
│   ├── c1615cac923ada447809f2823882ea7a65e34e98.nq.gz
│   ├── c258e1c93e239f663c6449405060f5d5edbca9e6.nq.gz
│   ├── cb9d9ef3a6cb47647b85e680df74790cbb6daa13.nq.gz
│   ├── cd7c131b655cf1197fb8f58e65efb207da0c09bd.nq.gz
│   ├── cdd1614103048a56c67459515c58315cbe76206c.nq.gz
│   ├── d72a059a4d873da1b682c253ecde372e2bb267ec.nq.gz
│   ├── d76123aebed7494281fb984cdaab970175693870.nq.gz
│   ├── d9c6049ae75d447a4c42427ff34386fbf3e16572.nq.gz
│   ├── dd22d14007e72f94c61df8235224c54e0ed4836d.nq.gz
│   ├── e17c68845fdb9a5dab86edd95f9b5048857e03d1.nq.gz
│   ├── e1f4d09c4b331a629f683528d72f461fa434e4ef.nq.gz
│   ├── e939d496c3f09d549097713d82ef191151f6282a.nq.gz
│   ├── e96971d6f5dfe95d4b40137fbc24405565024ff1.nq.gz
│   ├── ee9bbf80da5dd4d1ece01b91dfd40c5d84e1471c.nq.gz
│   ├── f89b4951d940ee8504126c602a6e115e4332cee5.nq.gz
│   ├── f924df311a86365b9a62016de9a125ca4c1f6747.nq.gz
│   ├── f969a2c6b5d10414d9025c157d42615a55bbc872.nq.gz
│   ├── fa52c395127e4939be26cb2d40ae0d10b0edaa40.nq.gz
│   └── ff3732429bac18ad8e6bbd53f95375bb3e423899.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8bd704ec0d9894693d35da425d827819916be920.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 77 files
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

[micromatch/micromatch](https://github.com/micromatch/micromatch)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
