# Repolex Knowledge Graph of poolsideai/acp-go-sdk

RDF knowledge graph data for [poolsideai/acp-go-sdk](https://github.com/poolsideai/acp-go-sdk), parsed by [repolex](https://repolex.ai).

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
rlex download poolsideai/acp-go-sdk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0845a3bb9eddda5bfc22a94dd3598c90cb842451
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 0845a3bb9eddda5bfc22a94dd3598c90cb842451.nq.gz
│   └── repolex
│       └── 0845a3bb9eddda5bfc22a94dd3598c90cb842451
│           └── chunk-001.nq.gz
├── blob
│   ├── 0127442251e347b6d37f31fb89b1e5f5fdc07d4c.nq.gz
│   ├── 039e3e0c995943f78fc7fa3758c1b138be889f55.nq.gz
│   ├── 071a291d0840bfec1bc2bb5fa590b7e7abeac1f8.nq.gz
│   ├── 07fe87e3f27f0d6fb4fab57051fb2c9419a355e9.nq.gz
│   ├── 088a7d186dad64706346c3260bef96eef2f33fa4.nq.gz
│   ├── 1108b0a4da92f9a6a50645a12c100a8fa6c776a4.nq.gz
│   ├── 114b8bb3ecc1a897ccae2272a255f1f1b51ceea5.nq.gz
│   ├── 1847f54956e35ec99b043b710b0d5858b1497ead.nq.gz
│   ├── 1a27f02d7742ab33052dacf9af3d5a10d27b028a.nq.gz
│   ├── 1cf0bdaf77c03b0a7f67c6840088afa4f0fb1230.nq.gz
│   ├── 1fb297f6918766fde10752cbf430160678cb0bb3.nq.gz
│   ├── 22dc45c72a39de06855e5eea9894e0184d861ddb.nq.gz
│   ├── 26efc57bd2714ca517e4fa224436c2cd8b0040e8.nq.gz
│   ├── 27f57c2dd1e2c40a4e286f0491ef4d1fd8b15465.nq.gz
│   ├── 2ed5b489f0c7fc7fbb84531318cfbcbd91435490.nq.gz
│   ├── 38f0331dd34edc3729ef9e7b1e873bbece6a045d.nq.gz
│   ├── 3a194c2f184e926465d4ee87b770339f3d0a0166.nq.gz
│   ├── 3d3ccca4743a19b0a8dd073074d941e7c82f95d0.nq.gz
│   ├── 42251b54e0b6ef7fd29c5bb00cd3fe23f94069fc.nq.gz
│   ├── 448649d208b8c29272359e1e9a6c6442eb01f98b.nq.gz
│   ├── 48325031c8620ef8449f5847885b5475a28d5d09.nq.gz
│   ├── 4b446ceac892dd00453e0da5ffd5ad690ed1be55.nq.gz
│   ├── 4bd069c7f916caa2f2ec811a3ecac4baacc1dad6.nq.gz
│   ├── 4e33c1ee49801888c0b90bef631277273a34fd1d.nq.gz
│   ├── 537e458cf238164feda2e7a3aa608073525d02ae.nq.gz
│   ├── 595a522d09669ed3bc37e5122d29eb428552536f.nq.gz
│   ├── 5c837448f581d0ce26fb48444c01ae254f812600.nq.gz
│   ├── 5cab979dd8c22d2e15721c2564a60d405484911e.nq.gz
│   ├── 61e51d69e5fc6ab8d988088bdbe7719f6fb9c94a.nq.gz
│   ├── 63b2e85b320fdb0fbe13650f6b23273d659dcf87.nq.gz
│   ├── 698b6d5e22f4acaad0c62745275fad053da8d557.nq.gz
│   ├── 6aa9c3cabf8cf76a4503fdd998431d7defa5c96e.nq.gz
│   ├── 6cd650eaf3c049b03c509b01bfdebd86abd32556.nq.gz
│   ├── 6eb317346cd10cb58079e91ee991c73f4fe3d053.nq.gz
│   ├── 70afba0a0ba828ad52e131a18cf9358f623b0de0.nq.gz
│   ├── 73eec5dbb2d16a95ef9d105104dcbbbe4acb5801.nq.gz
│   ├── 77a4f5dbff11051317254e9a0bc0744a15fca50c.nq.gz
│   ├── 7ace7edd62aa691d64b2c77d5fea350a312d291a.nq.gz
│   ├── 7b15a44c466f26adb5b1b986fc893072c17bfaf2.nq.gz
│   ├── 816fae1388dee7552f19755efcec6042410526a0.nq.gz
│   ├── 827659a5e53747749c214f6f2d34bd609310b86b.nq.gz
│   ├── 841392618a6f29c21c56c8cb1ddeb2d4e184939e.nq.gz
│   ├── 8670984f9792779e224cfb741d8bdd91474379b8.nq.gz
│   ├── 872918f5eb48a3b71c8663a0733898ca9c1dc73a.nq.gz
│   ├── 881530559d1818eff7a06b6639df2e24efced5f0.nq.gz
│   ├── 893c13bc523cd7e1e89cee6146666dd813000504.nq.gz
│   ├── 8ca73e7bec8564f4766eaf7b8bc14e8ced0e0a05.nq.gz
│   ├── 98482cb7dcb86e44881fb56138166c1deb226ae0.nq.gz
│   ├── 9af59833ed8f3819ca38bde0e4f2d4c61c5b1d8a.nq.gz
│   ├── a00bf7bad31a2944c40c2859d015b2a8ce1304e1.nq.gz
│   ├── a1ac3e47718cbd7f29d8d87fccb2a206cf81194a.nq.gz
│   ├── a5461d26dad4e43e22b72c884f1ac81bdef21b21.nq.gz
│   ├── ac3dbfe42e99f935e4e614f4e85b3ab27f89b307.nq.gz
│   ├── b33ca31898f0aef337896f9a4ab9db6122f89d69.nq.gz
│   ├── b5dac57479cfe11432e8c0c8f11dfa4e45cd7269.nq.gz
│   ├── b66a034d8dd4f343f41c470bd0cea7f1d8568c63.nq.gz
│   ├── b68cdf36b9cc122e6583e7fca4ad5e42a0386ad9.nq.gz
│   ├── b6ce47dba4c3a0672ada5163e280a01917b5998d.nq.gz
│   ├── ba8e79fbcf2f2c053b9af7a2e2c755c8726aa7ba.nq.gz
│   ├── bad3e8a1e839b1743d07faa030f31dbf469acfec.nq.gz
│   ├── bc37b611cb6261eeca8259973b2e19e48e3d6c79.nq.gz
│   ├── bc5135b29c9864e8dacb4ebee3f4c034f5754363.nq.gz
│   ├── bf3b6f77797555d15d6a5a8d7b4fdbb72a86eecb.nq.gz
│   ├── c044187fff25874c7b4a9f08066e261f3d1997e0.nq.gz
│   ├── c1f1255a60bf7d64cf31825615fdf871c308fd54.nq.gz
│   ├── c37136a848249f696b75d36771e7de99844f07d7.nq.gz
│   ├── c5faca7ee756303c936bed4959e549208bf79675.nq.gz
│   ├── c90cca4dd6122b3b7e3d2cb5ec7eaf3bf5a81ae1.nq.gz
│   ├── cb8a0e055d1d2faec87fcd8ac83c666a5b01d6e3.nq.gz
│   ├── cdcec5bfe2a620733c44dd380f79886190117eb9.nq.gz
│   ├── ce036403499f785e063bf7b6689cf99e02e428d9.nq.gz
│   ├── d35398bba62e80ce05e58cf88b85c55ee4882b42.nq.gz
│   ├── d533afb64446572752c7dfef272bfc46dd165355.nq.gz
│   ├── d5af3359df0e7f0029197c82635bcbe83e2f8edb.nq.gz
│   ├── d785184ceaf0aba7377d18dc0df6f2195b496064.nq.gz
│   ├── dfa3f3dbb863aa890ed9751f6af258343f2858d0.nq.gz
│   ├── e28b46146b9fd3c147b8ea93ab0fd0448b0fcecb.nq.gz
│   ├── e29b89ba243d70a29ffc919801210299945176e7.nq.gz
│   ├── e33beb070605b58159638552bd8ef841c83bf65c.nq.gz
│   ├── e8c4ab8961ca4f312bceb81fb0fa1eceeef1578f.nq.gz
│   ├── e92899013b98f2a3c1613859a212b18b4e04d347.nq.gz
│   ├── eb0e31d16ece70fe2e0f4fe1cd1ceccbb4f5a75b.nq.gz
│   ├── efbad0931533f363fa3643c754fba40c9b22e1d8.nq.gz
│   ├── f26f752e3a3fd24930d4166f84f59d6c9d931b0c.nq.gz
│   ├── f408c158278d2e3201a9ca0b59f337c01627260b.nq.gz
│   ├── f512d82961dc7d8d4c71e9b841a1a4dbf851851e.nq.gz
│   ├── f73945a324010af8e7aae2ad76170562eb0107aa.nq.gz
│   ├── f763904e84d01b040dab8b5a057fc72d7863e155.nq.gz
│   ├── fca8b8805f39fc8c398e5c811f8d05c6807e9ad4.nq.gz
│   ├── fcbe25dd18f12f194d79862e8058156a5a63bf8b.nq.gz
│   ├── fd0c6762f23d198647f13b21492059057f376e17.nq.gz
│   └── fed775eb3377306d25f9116cb08b654598085692.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0845a3bb9eddda5bfc22a94dd3598c90cb842451.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 99 files
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

[poolsideai/acp-go-sdk](https://github.com/poolsideai/acp-go-sdk)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
