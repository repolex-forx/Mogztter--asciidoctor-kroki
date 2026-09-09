# Repolex Knowledge Graph of Mogztter/asciidoctor-kroki

RDF knowledge graph data for [Mogztter/asciidoctor-kroki](https://github.com/Mogztter/asciidoctor-kroki), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download Mogztter/asciidoctor-kroki
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 050e625dc939371788b2774cb3169f7749e1bba3
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 050e625dc939371788b2774cb3169f7749e1bba3.nq.gz
│   └── repolex
│       └── 050e625dc939371788b2774cb3169f7749e1bba3
│           └── chunk-001.nq.gz
├── blob
│   ├── 01cf9783797cc88b27bc684ba94ed7f493314b5d.nq.gz
│   ├── 0663003d474fc5109783a97370db515cb8827053.nq.gz
│   ├── 09a507796f7a05b261d9222471c9157b4b668625.nq.gz
│   ├── 0c0cab5ba5c793557f3ac5007fb3fa257314a6c7.nq.gz
│   ├── 0dfa4f7c6fb3850590b28c0ec70fb2fd02139100.nq.gz
│   ├── 10e0423912a2ed193b254ae3e42e435f32fb8cdb.nq.gz
│   ├── 11c268fc1fc712e97b1582fc31bc11e464157b5a.nq.gz
│   ├── 12db048bec831fa7a57c4d2ac526868df9b53da1.nq.gz
│   ├── 1436222a4f85959c3ab1e34696e8f15d01407c00.nq.gz
│   ├── 14cf9b7f0c1337c1f5d362ac2ee0d0ee2faeb09f.nq.gz
│   ├── 1592d092cc523d6b0302136618b8d8c9892127a8.nq.gz
│   ├── 1633c9dde0d2fbb42096dd72f7bce9a8e29d080e.nq.gz
│   ├── 1ff115f6cb2640a4ec85fd39cc86eef12ecc42ef.nq.gz
│   ├── 24a021a0cddad1d1307a161cf0d2d8b51063820e.nq.gz
│   ├── 27d4f82f87ed8156566c4d322ce294a689070ef8.nq.gz
│   ├── 2f83b418ed266f81100745cc9cce06e036ef3a77.nq.gz
│   ├── 2fb425f9d8adb6939792c4fd47b93a826758cf45.nq.gz
│   ├── 3489cb973065c5bf60cb0f0c5642041114aa946f.nq.gz
│   ├── 3516bd336d80d95d0ebd30bfbb55e7579b8e1d5d.nq.gz
│   ├── 356a2dbd28507b360c7ca04b23d261e4b17f0fcb.nq.gz
│   ├── 358c07d962d2d5dfc264bd250e81d8ca39b1daec.nq.gz
│   ├── 3cdaccf2edb2cc8f3ba6d305ab6094c28895a028.nq.gz
│   ├── 3d209d8836b206b3f6cc23de4aa03ae15e8f3e8b.nq.gz
│   ├── 3f09ba6dc5aaa7b90cd7ac7511c060aaa5d9e496.nq.gz
│   ├── 40f6ef52c35f91044c0c6ac51f8a41e9ae91cde3.nq.gz
│   ├── 44cd0d65d88bd875c8af89c4b88f62c26da9325e.nq.gz
│   ├── 458ebb89ec6461b0e4e65e30f43e520108f8a1d0.nq.gz
│   ├── 4751b654e99cd2ebb49c6172f4d0e34ffd957014.nq.gz
│   ├── 48be2fe99bfb0e4f3746d5984c3ddad3e2756fa9.nq.gz
│   ├── 49181243ef9c0fe0676cba2e4150fc93edae02b4.nq.gz
│   ├── 4b6f7997e7eeb3a60f18aae4372b519e57c2d38a.nq.gz
│   ├── 4ce42cb3a2772d03551f7defa155c6464442d857.nq.gz
│   ├── 55bb1bca5b9ad990ac4b14b1b26e2728c6574893.nq.gz
│   ├── 55fb8fcc92a4ad7558373f8afa34e30cb0efc248.nq.gz
│   ├── 58bef6437a0d1cb9981ea88e5b5731453075c9d1.nq.gz
│   ├── 5996c6f2bd0f0db63197ac186f6fb6b61331fd41.nq.gz
│   ├── 5a660f28e985a2a68b2af1e6d021eef173a380db.nq.gz
│   ├── 5b6dfef9778f0fe43361ca21b49984ebd00d278e.nq.gz
│   ├── 5d05eed9d9c501c9674ded2355ee2c38beef99d4.nq.gz
│   ├── 5ea541e6d691a1c5e919132b984bf88e5117e878.nq.gz
│   ├── 5ec56cce25f330d7bd872fdd0339cdd9d6974586.nq.gz
│   ├── 5feb3b0a1185fa8f4e08c3d0ed2d618e01748201.nq.gz
│   ├── 60b037aabc58df98e64977c8cea5005253525cfd.nq.gz
│   ├── 61811725f7a0a6b8b20944dcc9a7765eb6a2638e.nq.gz
│   ├── 646b21704f47149bf32ca371d957ef3ef6c71448.nq.gz
│   ├── 66108cdb0f41997de376e05bfaff6c728ae455dd.nq.gz
│   ├── 6748248ef8f69d6281213730e067caa895124f37.nq.gz
│   ├── 69891a0f795e1f4c449a37241598c201b90e0375.nq.gz
│   ├── 699c067cf67337c07312703ed52c5d8d46bd80e8.nq.gz
│   ├── 6b51ff7b6d09d8a1154258b3ac1b6b0f5a1057ea.nq.gz
│   ├── 6e4fd09d90698c7d7444f0670a7e693a15a023b1.nq.gz
│   ├── 6f4cc14699334c2eaf9436395b739363e0e4b88e.nq.gz
│   ├── 7104d4e209956a85f90dd03816f7b20c50eeea72.nq.gz
│   ├── 726e478dbe31a7d8e1bcb0939809ace752c927fd.nq.gz
│   ├── 728b40402b7a556eaf72da8c5082dcad56d417f5.nq.gz
│   ├── 72f3268a65ac091b9c275ef1cc0241c5a28adc40.nq.gz
│   ├── 740038a16de4602cf0572704e4d0de683d248a8d.nq.gz
│   ├── 7566b040bf39fbf8ed4afa00a8d0f01212cade55.nq.gz
│   ├── 77aab5a84f460ffd9990130139720e2e9310782d.nq.gz
│   ├── 78aad958655fc65c56cee423239f8a16ce2c2c0c.nq.gz
│   ├── 7c39183ffcdd83504d9474b81c9edebf444247bd.nq.gz
│   ├── 7f4f5e950d1572e1ce5607ca237375aa2e30d662.nq.gz
│   ├── 8415033a0ea9969ce8a8b0ddad9e1dca849c23c6.nq.gz
│   ├── 861d7e7cc94c4fbf45798e6171941f3e796c1f14.nq.gz
│   ├── 893862deb1a46153829222aa793dbcb8e7f97f69.nq.gz
│   ├── 8d3c35d9df5c5467151baeb408677e1129751fd2.nq.gz
│   ├── 8d6050f41530111426f1782318cb4c79874327f8.nq.gz
│   ├── 944880fa15e85084780c290b929924d3f8b6085f.nq.gz
│   ├── 94f2e9e3a5c50d3d3c360e7226a409f0c05dfe92.nq.gz
│   ├── 96f440ec5e2fa828e186e4451dc541024cbcc8a4.nq.gz
│   ├── 98360b91b9d553a2f24407ebc2ef8c3c50278082.nq.gz
│   ├── a0d755749322e26e84efba986d55b95e575b6974.nq.gz
│   ├── a4e1391540e0aa9a725287dc9a852c2b514a5c5a.nq.gz
│   ├── a50056dd5710e111ecd0796542bac7dc703fde18.nq.gz
│   ├── a52c0607e37f60eb96069ef6ecdcf41d41d4c506.nq.gz
│   ├── aea4b24ba97854e8ccf43b4a5b796347c0aeb87b.nq.gz
│   ├── b7a579bb52b45370bbeca9146ffde7968a249ad4.nq.gz
│   ├── b7d96d2b2e6c6e60e838c6fd664a7120894c560b.nq.gz
│   ├── b8c93c04930ab86c229d6016de66874aaab5afb9.nq.gz
│   ├── bc4c1f1bdef2ae4ba8eef555e6b8c02432d80c1b.nq.gz
│   ├── bd5b84267b18f39efa48fb2fa8b773fbec9e6ea9.nq.gz
│   ├── c0147af4546128dac092fca5a74c0aefa46beef9.nq.gz
│   ├── c03e465ff6afcb5d2ab449734fcfd3ff9372d2aa.nq.gz
│   ├── c1c15dec55e39de0f30e807aaf25ef6288c09e7a.nq.gz
│   ├── c1f3c5c6937c4a94a56859fd63ca8ef8104a5723.nq.gz
│   ├── c2ee3eeb762bad8bf3a8c4e3fcb2e23603e14ed1.nq.gz
│   ├── c37eb259e5c7c674d43fc57390c6a7e4edbcb7d1.nq.gz
│   ├── c396ef4c881a7d462e57d472161f989710415ba5.nq.gz
│   ├── c4965b43ed6035d6d68c3fc254789f9b15821fec.nq.gz
│   ├── c4e8e9738420bf0ab52aaa2dccca844cb1a78fa8.nq.gz
│   ├── c98d51542832e560ff60d8c0a6dcf99bc133ec75.nq.gz
│   ├── ca378ff4a1d114a934ad0e2248d173418da5ab13.nq.gz
│   ├── cc8d9fe202203793c5f2bba0ec37e1e3f541466b.nq.gz
│   ├── cce4b5305f90087a1f7180784c185f42a565fab3.nq.gz
│   ├── d05909079b42bc54cc5f6392ed0330a4c2f1cf3e.nq.gz
│   ├── d312624c32a4a2eaa330322430f74d7f9000a4d1.nq.gz
│   ├── d3627ca7b53a111aaf14540c6a4ea81ca1a2d7b8.nq.gz
│   ├── d390ad4f5cba5a2f56b427dcbcc1493ce292885a.nq.gz
│   ├── d52d19184636c2792fd6fca24cdb9093a71edfd8.nq.gz
│   ├── d7f50dd9b6373fb4ad20414e44a305cadaceac17.nq.gz
│   ├── d88b75359d509ed689a470d81cab543db362d841.nq.gz
│   ├── deaf4a6dce861aa06121034fe74b7ab9de04ca3d.nq.gz
│   ├── df8bc988dd35f21511c46c9d4bd5558a7a6a1033.nq.gz
│   ├── e12e32d75cce1bad52789764ee0141dd3e442ba5.nq.gz
│   ├── e278027d8dd05c92c2ea530e7ed56103c27e77f8.nq.gz
│   ├── e3261c039200a2152fe73d3c2f8b120885448dbd.nq.gz
│   ├── e3912f38bde7d9b0298a063fc4ed9f11942c2476.nq.gz
│   ├── e5ab8d648e28f194b0fabc45ce8b690a3f6993d9.nq.gz
│   ├── e642f6aa5bf4ef1762721f5fb22c882de5231208.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9dcc29d28c714a77a43baa627aa9566b1abfe64.nq.gz
│   ├── eb6d9cb752fe2ba48a2ae01734e868735624a880.nq.gz
│   ├── ecfd50bc580ae1e77732557c25b6f5f616459517.nq.gz
│   ├── ee44533ec8acecabdeafd0fbf38fead16ab56530.nq.gz
│   ├── f077431a6bf58247a82e2d5e83a1f06487f10db6.nq.gz
│   ├── f3667c7f32f920266fbf8ec7a9dafef5a807d935.nq.gz
│   ├── f70d8fdee6df456c57b0d0beb2f15a4ac258c990.nq.gz
│   ├── fa8e3d30cefdb1e7acbae482f68384ae08159051.nq.gz
│   ├── fa9855ebdc542dbcd811a16b786707366ad517b4.nq.gz
│   ├── fc5dd039465b51aa6db273d7dc44eb2de18d680b.nq.gz
│   └── fe3a99c9503398b910a995d2be21ebc57fbdaa1f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 050e625dc939371788b2774cb3169f7749e1bba3.nq.gz
├── filetree
│   └── 050e625dc939371788b2774cb3169f7749e1bba3.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 131 files
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

## Source repository

[Mogztter/asciidoctor-kroki](https://github.com/Mogztter/asciidoctor-kroki)

---
*Parsed on 2026-09-09 by [repolex](https://repolex.ai)*
