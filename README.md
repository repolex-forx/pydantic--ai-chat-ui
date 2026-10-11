# Repolex Knowledge Graph of pydantic/ai-chat-ui

RDF knowledge graph data for [pydantic/ai-chat-ui](https://github.com/pydantic/ai-chat-ui), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/ai-chat-ui
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8014d57f8fccda48ff643126c6a10f91812f61a6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8014d57f8fccda48ff643126c6a10f91812f61a6
│           └── chunk-001.nq.gz
└── blob
    ├── 00f6755d399845b8f3df4f5b9515b75bbb64ce7b.nq.gz
    ├── 02fc3ba4a2fcd56b7dabc1ff60296b9925693cb2.nq.gz
    ├── 034a562844e030e6bc415c2579fa50a629f92700.nq.gz
    ├── 03ad6b14d1e9db550bac57f2f10071beebee9535.nq.gz
    ├── 03f99757a0e305403092556eca057a7d4d47cf2c.nq.gz
    ├── 04451c0bc69814dd8ca35ced33c57e319e794e7b.nq.gz
    ├── 055713874b5fd56dbf6df64c4f38d9e1363f614a.nq.gz
    ├── 07424b785f92d61596a6e20b3b1dfb14b955d788.nq.gz
    ├── 0797d22618c1d39dc611e34b18ecb390e44de8c9.nq.gz
    ├── 0a8e1603a1366eb56568b307c175565c36c4a264.nq.gz
    ├── 0c4e5b74eff3c4342f7e4bf4660cfa4a7a8efbbf.nq.gz
    ├── 0d69741da5cee6c084b186cd6a983a6f917d7ed2.nq.gz
    ├── 0d880409ddf86a604f238396891b5a7af9cd566a.nq.gz
    ├── 0dab40c91974b208d920b26f85c3a952bd82756e.nq.gz
    ├── 0e4641af50555ccfa40698c1071e49fcf4cee4ca.nq.gz
    ├── 0f0989aafacfe7445c30f74fceb7f47e3a70e9db.nq.gz
    ├── 1109607fdacd2e496a70a55bbb0923c7274c3c22.nq.gz
    ├── 11ee389ac0eb47192ca9d20e193721e12495c669.nq.gz
    ├── 13c26a3d99d38243a0be7c67a97c3df20ee89343.nq.gz
    ├── 18bd6a30c9c028aba5e18cf54ede62017b1e2b56.nq.gz
    ├── 18ec3afabfb67adb493f5f7c0263c0995b08d487.nq.gz
    ├── 19ad00e3f66f021115662b41c87d6743e92a1abd.nq.gz
    ├── 1a7a33dda1157ed5c40dffa9c5f10a972bc47f31.nq.gz
    ├── 1ad61d14b0e5406481ade607c44fa402844ddecd.nq.gz
    ├── 1c6a2fb8be03bd7d59801b7f9047f06f5ffdbc2e.nq.gz
    ├── 1dd4591cbc1352d00fa562e0ce1e58a185741a25.nq.gz
    ├── 1eaa6570a5b23f17a7cc6d073a9eae2c1fb79e78.nq.gz
    ├── 20b7c6dec3cb4f1a3c4c14401d60c9c9af19ca14.nq.gz
    ├── 217649831e21cc867ad7ac6845a302741ead8665.nq.gz
    ├── 228d98ad140563204c56586af1077f8c03e84dce.nq.gz
    ├── 229dc253ceb83adbafa57a5c1e2392aa93cb746a.nq.gz
    ├── 22fd6312658e35963428da337bcd2d37d7cf3355.nq.gz
    ├── 23b4326e27e406d070debac7253d54244a95f137.nq.gz
    ├── 281c8f86aa94a6190e357058e99abd0e99d2f15d.nq.gz
    ├── 29b8349ad161b897ca7923daddde485eafb8603a.nq.gz
    ├── 2f9fecc96be16d6ecba923933c406be7dd794b14.nq.gz
    ├── 2fb8a209119f01fe38a900fff23b2d5b1af4a47b.nq.gz
    ├── 3018ea67c1ad5a883013dc16c14a0578b44c5752.nq.gz
    ├── 3126758e50f3504ecb78918369b18c8c32007321.nq.gz
    ├── 3363ab762ed7658b3e45465a6976e96899fe62da.nq.gz
    ├── 3463897f102686f06084a2bd188cf1b116682122.nq.gz
    ├── 36cb5dda09bbc4d870789029fc31b13ff82d873d.nq.gz
    ├── 3809775e832e192bd6d6d50d595c5b47c81fbda3.nq.gz
    ├── 3876b8a6967ed00cf4ea30baeb3bbe66865b728a.nq.gz
    ├── 39fcd14e42958c40160da26f81d6dbae2170b84d.nq.gz
    ├── 3cd4eb938d88a4f711293a70d842b02f14c418ba.nq.gz
    ├── 3d87e7e6e17f7cc95f8680760d4c66c981c8e69f.nq.gz
    ├── 3d8a2808e87fd40dc2201215957ed3b1d3aed0f7.nq.gz
    ├── 3dae3afa7a37ea5dafd35dfd1d3aabec854aafb1.nq.gz
    ├── 3db3b51ec2ec7304ecbf9438027db28d597b19ba.nq.gz
    ├── 3ea5cd3cf786c364b2d50dd0e321b1741579f6bb.nq.gz
    ├── 40188b51ca1aba9d716f82ec60ae0ddee0ae5d07.nq.gz
    ├── 402e45a8c7a0bc3393bff92992792988138e1643.nq.gz
    ├── 416f609270e6206853f27fdb1e4a63248dd82ec2.nq.gz
    ├── 42cb8ec35f4976be198d2be5060fe70d5f826c47.nq.gz
    ├── 43a479064caee289db1910a786a31f8392e57df8.nq.gz
    ├── 4407b942d32e7b885e9af116443371637b1b047d.nq.gz
    ├── 44139d1d42db1ac14fe427e91f0ed40cb867284a.nq.gz
    ├── 45868303f0ad1c9a7e3e425d2a6562c9b6bab356.nq.gz
    ├── 4613d9df17e7c1660653cd1e10bba95d0bf43816.nq.gz
    ├── 461e80d8128903f83e7b9625a7be0bcc3bd97c7d.nq.gz
    ├── 46697561cd7c2184ed8e0eeeb87218cb9ae1b410.nq.gz
    ├── 4821dae2c75a3428fa341544ef72a3ad1c718cc5.nq.gz
    ├── 49a9bcea2019702e838c4e5f5168c2dce4e76a83.nq.gz
    ├── 4a3bdb09b06728ed6583136c9556fa4032718758.nq.gz
    ├── 4aac3995130855493eccfb64b3a7feb6cbab5e45.nq.gz
    ├── 4ad9e3095340947333c192087c14449fc0cfcfe0.nq.gz
    ├── 4c1283aff9e942241723cec019a395ad6e781668.nq.gz
    ├── 4eca3ff5abaea72ec8ef7127a20a56d74e72ba59.nq.gz
    ├── 5133167bf5fe2ec35ff27d5c7c83556922c3ff07.nq.gz
    ├── 515b2cef2e97c10902fa6bccb58d9e48dd31157a.nq.gz
    ├── 559f2fb333fcdee4259d89dcd77b86660c633bf0.nq.gz
    ├── 56161c76986ada3626113418e99dcf11060e0b72.nq.gz
    ├── 56a6f3c9e8ac576a168e6be1307fbd2b75d664d2.nq.gz
    ├── 5a7e66e7e9f1060e0a14580b9aaaf36f8161e4be.nq.gz
    ├── 5aa24259761022c6a54f5e5a6c464e1f2df6c23d.nq.gz
    ├── 5c0a2a9877df110b1da249e59e3830d0b0461edb.nq.gz
    ├── 5c2d8056ca0acfa7e04e9c0638b621b6de3e0c92.nq.gz
    ├── 5d92a2146bb6604c49817b7fab936aef8a07a51c.nq.gz
    ├── 5e3c4b963d24468249dff7760babe5e4ad6b4a4d.nq.gz
    ├── 5e5d6f069da119eca5dee240c32180ee76c67854.nq.gz
    ├── 6199ad63aaf7cf1e76989026dafeb9f9503d1861.nq.gz
    ├── 642c2712d4b62ea9c58d6d1b12dbc3ed6e203e5a.nq.gz
    ├── 6556a88c1e8d917b11662c780bd40631da3be0e3.nq.gz
    ├── 65a7a6b228c7e84ec38901c3a29947d2bc7fe6d1.nq.gz
    ├── 6651464a74690753117b9f7df5fd1b7ea67e6239.nq.gz
    ├── 6817fbb7a41b962f19b6e0960396c71602d5c71a.nq.gz
    ├── 6c9d8e64e211bac8a4de52cf9499de3bf6295678.nq.gz
    ├── 6d94ef070584361010d1cbcc48aca083e32ff7aa.nq.gz
    ├── 6dd12b50ab53030b896139e04954d187a11cc9e4.nq.gz
    ├── 6e0f363f6ef7c3beaff00f1d474f606795773431.nq.gz
    ├── 6f0ed8317a21f35cf80ae4e8af8ba8177a716c64.nq.gz
    ├── 6f8134f7d28bd9bfe39c0df9bb04bfd4ba658280.nq.gz
    ├── 6f9dde7a94665f6bd642e5a00e0a7c43f0d38f7e.nq.gz
    ├── 6fc804c08987ee55a6e4c07efe1d547eb5a70cd9.nq.gz
    ├── 71af40ab2516567fb93ff555af692c558cec4058.nq.gz
    ├── 725ce90e71b1f5616cf767998793473e20e0f7d8.nq.gz
    ├── 737f21dd1423ef22197c7a8aa8c93f10f8fa41f6.nq.gz
    ├── 75fee7dfc8f583eac4606c470c7877cb77896864.nq.gz
    ├── 76858eef3315673064f5c2223ed4d68a84e34ecb.nq.gz
    ├── 770c0ce610da6f0f67b8d3c70544d6979911ffac.nq.gz
    ├── 772661cde600fa002e461cb245e28348c4157d09.nq.gz
    ├── 78aaa5931c1db0e08587949574453aed4d67cf26.nq.gz
    ├── 7a3ada65811b938267cba17f0eb752181017b6e5.nq.gz
    ├── 7a958adf4a8306412bbb8deea1d9639a8faede24.nq.gz
    ├── 7b314c59c34f938a6525ab9817a10c2c9621cda6.nq.gz
    ├── 7c4ff4d984107759ade90b600caeca9637f75883.nq.gz
    ├── 7cae4dbfa997ca967964a3c42ca4ee8d4bcf87a3.nq.gz
    ├── 7d7fff309d1edab9c10aee7b4cb82916d575dfb9.nq.gz
    ├── 7e6a5dd62c0b42940a28de4b8deff8e6e6ec82a4.nq.gz
    ├── 7e6f2e70a140844bec65fd470c7f10c5f5aaae17.nq.gz
    ├── 7f7f3740440df8f127aee20c264fb1b5ae390aea.nq.gz
    ├── 810d257b3c95677a667125055c0f9b7ee4492ed2.nq.gz
    ├── 81e2bdb91d080b33ec8e103b145b768fe98cf767.nq.gz
    ├── 834fb3ddf627078be8fbea1992e64648d25f1b4c.nq.gz
    ├── 849602bc98abada98e7673c9e2f55804ed542b80.nq.gz
    ├── 861a25b9a59cb7462a84ad6a372864b3b43e4fc3.nq.gz
    ├── 873234c0bb2255f7f3107adec0895d9a36181ab7.nq.gz
    ├── 899486c52a6d6ff6ec4ad5e3fec162bb12ce575c.nq.gz
    ├── 8a4cde282094242e90a5d63cff1d6b386d9ac766.nq.gz
    ├── 8d06e38e88babd178dbcd3279eb961c7ffaeff1c.nq.gz
    ├── 8d5f4c65ff873c6b4fef207371d4e455f17517e7.nq.gz
    ├── 8eb0b07e1361a5740dfdd55aa92cf2ba49cb74b6.nq.gz
    ├── 8fdc460bc1e23269fff11ea2ab078cf4b9d40c8b.nq.gz
    ├── 90effe7df7de854d702b7414da9b29a067c67d55.nq.gz
    ├── 922245bd193e8f2546b73e9da6dfaeebf3b71ef1.nq.gz
    ├── 9780c07b3eef51ccdc224c20a5339e767fcaacf2.nq.gz
    ├── 9a165a015ea9af1399696d1a8d243033c9a89755.nq.gz
    ├── 9b85443e8a88e7a1aff82a798c099489d600bf1b.nq.gz
    ├── 9c0c7293efaad8aa18b92495a242e8b65f3eb407.nq.gz
    ├── 9e8b5ad71094fcd19341483b4ab49eb9eb9ab570.nq.gz
    ├── 9ebb568d8a4dab6c3be094516b0c4f73f7240298.nq.gz
    ├── 9f0bc561a946367cc6e7e55139163c73c5d5fd62.nq.gz
    ├── 9fc803a097d7869430f0c8e6004f9432fde3224b.nq.gz
    ├── a0176a5b2747a8a0accfb13d7190298b7e853f36.nq.gz
    ├── a0de7d6760c930e873165933f0202fd4d82697a2.nq.gz
    ├── a10abb7704363873cac74b93d00bfb5d97bee636.nq.gz
    ├── a1517da6e2658d8987ef90fdb66db9a586335f4a.nq.gz
    ├── a1ef93bdf6bb1b7cf71fff07546a3c9904043fa1.nq.gz
    ├── a33d22be277c6f68b74732d7a76d0cb4dfb17197.nq.gz
    ├── a3aceb16fee3dac8cf167507a97df23af42c9234.nq.gz
    ├── a43c56e48259e45aefe550728f1aa597938c5f4e.nq.gz
    ├── a51677c25647ca9de5666f51596998620e9c2f81.nq.gz
    ├── a710568001a46ab919e9da11a7b080494b2c6f79.nq.gz
    ├── a719ccf72e56440475767518a0435d1816764057.nq.gz
    ├── a76868dc7acd6cb899f902e1c4522f698055a5eb.nq.gz
    ├── a77262753f111037e1d69f2d40695a42f6e94e38.nq.gz
    ├── a95186015a25e43560fb55ee8d20ec0f41e0194b.nq.gz
    ├── a9a799156378986f6c07a514ab4ccd4cb7e2c298.nq.gz
    ├── ad311b57a293aac09ce0b9c8d11770ef9946e5e5.nq.gz
    ├── ad638d4bbf495cbd05cd33184adc2a87ad111c1b.nq.gz
    ├── adf834996836707ca0678a62ab6f57fa3d0b1c2c.nq.gz
    ├── afa0303f5305121b4b179a48d4f93c5372cd6a98.nq.gz
    ├── b392545de79da34e7b409a2f9863359fa3762e1b.nq.gz
    ├── b3eeb1ce5d97dd2e9bd2f6ee6460c5e30b4cbe56.nq.gz
    ├── b46a15a847c18f7ad7b692cf51fe92b5b4be1b89.nq.gz
    ├── b6db352312b6729cc3da4928b2326e9f91d880b2.nq.gz
    ├── b7f9a4f113bb5d24c8b2a3d5a0ac6c2cdb8a5a97.nq.gz
    ├── bc183d1919a64b32f7a95a2f714fa0020d8d97c3.nq.gz
    ├── bd2d63a2ab10317b3e429007cc7b7f856e0610a4.nq.gz
    ├── bef5202a32cbd0632c43de40f6e908532903fd42.nq.gz
    ├── c37ec30364562cdc0766fbc0c6051952ee4b62c4.nq.gz
    ├── c4ba9f9882c6d34a6f6ba93f19899afa7db85a71.nq.gz
    ├── c746b39f546320cbd7d72ec771cb364c7240399f.nq.gz
    ├── c7f152ac4ba3f8fba1efcda40b0c9f5871f00c3d.nq.gz
    ├── c9686c6306e1c36efc1fb393b1207746d9b18c6f.nq.gz
    ├── c9ad8a352249b4b3aaaf0b85bc25998e75d00f12.nq.gz
    ├── cada01691f2b4ada0da5c6986cd7e24883320513.nq.gz
    ├── cb484ae96471bdb37b95b7e59e5cdb46a05b5ff5.nq.gz
    ├── cb98348381d090084e768fc0eafa4260bc09be61.nq.gz
    ├── cbe11112a0cb0aa24bca16a347abe844fe15dac9.nq.gz
    ├── cf11ef8347cc5083c5672c3a3b6128117e73fbbc.nq.gz
    ├── cff91fc6b07f537cdce5e82c15537802872c887b.nq.gz
    ├── d01a24a195e5369f0c1348be210cc96b3206a741.nq.gz
    ├── d01a99df0c6bb72ef38ceb5bda2833a154a6d03f.nq.gz
    ├── d0e9c1b4ae6e789a33bdeb4e63525227b566642b.nq.gz
    ├── d34a2b6a807ba2c2b27d65b84d0e59b2888bbd20.nq.gz
    ├── d5e69a7534393d213c09b6dd4ea0c315bcac2749.nq.gz
    ├── d71d0037a0d5e4e5fb9da64ffeb977651b356ac2.nq.gz
    ├── dbcbff4ce426d586be8396ccc770808983b0aee0.nq.gz
    ├── dc7e153d9703a793cf6083c269aeec043067a613.nq.gz
    ├── dd0e4b6f96e543ed300799418a0dbf640ac7b92f.nq.gz
    ├── dd728ebd1deabd87bf8baf78acf30e1c2f022bd2.nq.gz
    ├── ddde3717cc7d2ed827b11449c93f83c2253c24bc.nq.gz
    ├── de982ef63c162eda1488fa76e73490181a73b102.nq.gz
    ├── dfec261ef32dd7851919f9c92931855c5009026d.nq.gz
    ├── e356dad03945675d02ef77fe77a5460094dac161.nq.gz
    ├── e47a6a72db112522167925c1096e78030bdcbe0d.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e75b3d3d6803053cbfedc038ad7ab37150618a6c.nq.gz
    ├── e8017d15229ea8e810d0b20844b694732f5f1ecb.nq.gz
    ├── e8bfb665b2effde3f962e0f0fbb630893ae6777d.nq.gz
    ├── eaf45485ff5d74254b2c31a704d7ceae35123808.nq.gz
    ├── ec45f70d8cdeb0f8b5e858f35a89a7d31549be20.nq.gz
    ├── edf6e75fa96d730a8cd903ae5c7deff60c410018.nq.gz
    ├── eed66b99ba8d9a00dd8982643ea8509bed7edc8a.nq.gz
    ├── ef7e9a466c2eda8b80a091d2ab312ccdcf3ac4f5.nq.gz
    └── eff433cfaaa6ba53de44b6f5e59fc304d8f5e6a7.nq.gz

7 directories, 200 files
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

[pydantic/ai-chat-ui](https://github.com/pydantic/ai-chat-ui)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
