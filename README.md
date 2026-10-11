# Repolex Knowledge Graph of litestar-org/branding

RDF knowledge graph data for [litestar-org/branding](https://github.com/litestar-org/branding), parsed by [repolex](https://repolex.ai).

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
rlex download litestar-org/branding
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6a4f90f42dbc5412c39a138fb5b8e6a3cd489590
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6a4f90f42dbc5412c39a138fb5b8e6a3cd489590
│           └── chunk-001.nq.gz
├── blob
│   ├── 01432f88c11043021c4fd5e948f4fecee2bf15e5.nq.gz
│   ├── 025c1f39b3cd6451c7fed711a0b1bfed2dba7b88.nq.gz
│   ├── 03d72f5694158427df0f7790fc0aeac4317fb4a1.nq.gz
│   ├── 04e20b16a5a1da4106116aa73bedbf1cb6413b48.nq.gz
│   ├── 066130ac194ffefd313addcfb065c72c5540318e.nq.gz
│   ├── 07e48e4b8bbb79db30098c946eb9383b83094784.nq.gz
│   ├── 085029e4e346515cfa408da1ebf411bd184ebe3d.nq.gz
│   ├── 0a6fb79c0586b578bdfa46662ca492d4d6494757.nq.gz
│   ├── 0b3018179c924593b36050f5a6816c35d373ed77.nq.gz
│   ├── 0b98c5d71442e278a25a0bf8118d29a8ce4fab3b.nq.gz
│   ├── 1594dfc5234436d6cb428efc4aa87c288fe1f788.nq.gz
│   ├── 184535492c5537872e58b1d549afdf928fb57251.nq.gz
│   ├── 187a54a4be0ae8a3a519976e869ef84bea839296.nq.gz
│   ├── 1a7b38e5a6d9d8a92cb0ba5bbf74907f4004b758.nq.gz
│   ├── 1a8168c462e94e3a3354db6fb03be9f834daa241.nq.gz
│   ├── 1deb43715f50696ee49461da6dddc285f012ddca.nq.gz
│   ├── 2245d9f7a30315273d2b0991d0d9df5de0b87f24.nq.gz
│   ├── 22744aa6f20ee9191970bde16028a8e8bcf9f134.nq.gz
│   ├── 22c5317ec6561c57642e19c5634cc6f42fe718a7.nq.gz
│   ├── 253050b927dc6310977d42d1d48576715d9f324e.nq.gz
│   ├── 2916ec801dd8a89bb38c52747d1b9afcc7de2b40.nq.gz
│   ├── 298617b11e7ec1f667ecd1e43a4ecaa975f420f3.nq.gz
│   ├── 2af32524cb0e0a182d9b98c346c35fd9dc3aaa55.nq.gz
│   ├── 2b63fa59419eeb7856475219e3524f975d12b5e3.nq.gz
│   ├── 2bc68c444e9a62cace3eda363ddc0d3d540065cd.nq.gz
│   ├── 331aca6dec137b37f57b15d665337fcfabbefe1c.nq.gz
│   ├── 338d56b222b20b1d5d702c9d7dc3e0ac7481b8be.nq.gz
│   ├── 349dbed312d5409ec7e3290b9d07be47d1c00110.nq.gz
│   ├── 34c9b4a13832b6721a3030f92170650f016cb577.nq.gz
│   ├── 36761b15480b1e0375e0212b56db8ab80553acd1.nq.gz
│   ├── 37979cf12080837f15584a058d4b9fbb2ca28c13.nq.gz
│   ├── 38f669468ade6f1a08152c03f90d028f7d488605.nq.gz
│   ├── 39c0b7f133abc458b8c23bef337a782a90f298dc.nq.gz
│   ├── 39db5158b4ef12a35b17513fcabb0cd44832f32e.nq.gz
│   ├── 3a98407eb2fa8b16dd154c90e6ace375991db90d.nq.gz
│   ├── 3c061af12630ca194902291f56389cf8be301649.nq.gz
│   ├── 3c7918e74b74ea28d5093950bddf0ffaada05ce7.nq.gz
│   ├── 3d2ba5cbdafd63817cef3f4d2ec02f31f255dd33.nq.gz
│   ├── 42ab040ea75b114b29294731c20800a6785a4d24.nq.gz
│   ├── 43aef16af0578a4e081db1f137d16409bc223c9a.nq.gz
│   ├── 45ff8bd77be2f8f7cb0316632d4845573950b404.nq.gz
│   ├── 4714fa51313427dabcf1c3cfad777990654b5fce.nq.gz
│   ├── 48fe6120d60510f8a06b4ca366f952985a2441fa.nq.gz
│   ├── 49504fae225824455f7a51836885e1183b6f7174.nq.gz
│   ├── 4b6702e38f251cce49c1d1b776a52cb45843b410.nq.gz
│   ├── 4ca498c5e8e6013adf2fa735b8d30acfe5b5e349.nq.gz
│   ├── 4cebed9ce294b3a2d8538cb8819c85fc5a0b495e.nq.gz
│   ├── 4f356d7285f90443baea80058079da8251ba039c.nq.gz
│   ├── 4f9de4990c6cbec77b12bbe385289352352740c6.nq.gz
│   ├── 51c6bcb5f9a4431d2737648c645dc45f2e10275e.nq.gz
│   ├── 5298146f9900cace0d0c63bb99603b813442a81e.nq.gz
│   ├── 5364fa16f95e8db68917bdaa9b88b33ac7645046.nq.gz
│   ├── 54495388b7aac5a8f5c04f3496945d45204c08c2.nq.gz
│   ├── 59df9d35799db78f2ed9d8327a530a0c2f0c13b1.nq.gz
│   ├── 5a78ad9820643d22f3e1fccf73a1965e998d395a.nq.gz
│   ├── 5c06a2ec32dbe0f79823a06db14ddfb0ca5f9a69.nq.gz
│   ├── 5d27bbddd986237d5fa0541d1689eaf787be279b.nq.gz
│   ├── 6114668a98a5f5ff1ee2a324d474df03e8549913.nq.gz
│   ├── 6180dcdab568bc5271498ab7a2c183331853c1b8.nq.gz
│   ├── 62e15b738a9bebaeccd44c4fdcb884148a9bbdd9.nq.gz
│   ├── 67ff14afa86ae951e2e2f0ab8cecc8c898bf36ea.nq.gz
│   ├── 699e60264a061b6388dff7a5a8499b6ce31c324d.nq.gz
│   ├── 69ba752ca4686729caa653c315d8712738c80664.nq.gz
│   ├── 69e092014f746ebe511e0973c1f005b47b011b4c.nq.gz
│   ├── 6d66eaf6f837d6dde09b5717f79dc475dbd71f22.nq.gz
│   ├── 6f06f3b9311f7d616765b0fd8d4d37860136c38d.nq.gz
│   ├── 75dfb397b0d90b1459c6d2ca7f91983d19f900d8.nq.gz
│   ├── 7638dbf3aadd4523861e0859de0d9db1e0a10e2d.nq.gz
│   ├── 76a1beca7ec2e2d77e27f8c95e1281253fee6d04.nq.gz
│   ├── 790107abfdac7afffa75a65d5b0d5710b53150c6.nq.gz
│   ├── 7c52eddd8ad1e03da190f71ec892a6533c4fcd40.nq.gz
│   ├── 7ed79c161dfda5daf83b24a3739c0921e4547824.nq.gz
│   ├── 821b7e7629b4df10ea33456eb8075584ffdc6e5e.nq.gz
│   ├── 85680d05b136121c1f58b228bffbad75af100a5a.nq.gz
│   ├── 87c37f11b22fbfda34f8b79be1d6308ba2247255.nq.gz
│   ├── 8aa42d305f6b50d7f4d7ec01d965c1db2351b0c5.nq.gz
│   ├── 8c3b4f1dbf3e3f54f73b3af7df9f8489be773b1f.nq.gz
│   ├── 8ccfd46ace8d9fdfed4b1d8cb2880b2ac3fca876.nq.gz
│   ├── 8cd188e5dd79e7d4b5d5017bfaf24e13df7477aa.nq.gz
│   ├── 93b11eed7cd5ca72526a9cec20fabb79cd2962cd.nq.gz
│   ├── 93bc226b2362ccf0377777b89695823ad92e6ae8.nq.gz
│   ├── 947edb9b377d155e6d64784763afd8e7d4c192b4.nq.gz
│   ├── 95f79ca10b022ecdbba3238e587952c4f4b80168.nq.gz
│   ├── 9dc29eb94b4cb64d4abb8ee68975885a91e477b3.nq.gz
│   ├── 9dfcc50c4fa3f5fef8051d0dc4e71c38639c425a.nq.gz
│   ├── 9fc38e9eebb3f5229ac8f53138f74e8a930aea63.nq.gz
│   ├── a020ce8781baa5931cea4b6950b7db0731a0f1ef.nq.gz
│   ├── a2a90661274f58f2c8f39af59ad0c2e60293a3e6.nq.gz
│   ├── a4417f1350dbab434e10bef5f3414c453a1db425.nq.gz
│   ├── a5c2d07851e3cc605147f40714db949ed2dc9ec5.nq.gz
│   ├── a65aace0d00443b470a8772b97caeb685a95d018.nq.gz
│   ├── a83904bef0a701e04a461f8665b192726c3f8f42.nq.gz
│   ├── ace21fff51297712a68a5c14853370f3ec9c9c69.nq.gz
│   ├── b0ed25f9c6a45fe79c20629bea53993174efdb80.nq.gz
│   ├── b215847397490b8fdbe5dfcc7abeab7b1aa841a6.nq.gz
│   ├── b26f77efa86c3d1de93f85d4cdd32f95ff076adc.nq.gz
│   ├── b2b26f90ba30700e21587cc4d909454ea54da2a2.nq.gz
│   ├── b324c01fcf711aea47c478a2344ccf6b6af4e413.nq.gz
│   ├── b33ff29c67ccb26053912a9fc6502e83868c1275.nq.gz
│   ├── b4c2099c8aa9633a9d50ee8d4925a681a17ff1a8.nq.gz
│   ├── b5f7697564354d4c8e4568bba138ca5105e21936.nq.gz
│   ├── b83359da1c9a40c04815d391a8453851b7ce7122.nq.gz
│   ├── b969ac75031e2eeb41e841eefcbf912fbff40c72.nq.gz
│   ├── bc0a3e369a856cc755158e0ce19c42f9245fc771.nq.gz
│   ├── bda6869bc0647fefeac14bd345e1b2915cd81616.nq.gz
│   ├── bdbefd1d43cf07230208996ece44995b5adede95.nq.gz
│   ├── bf3630b8bd2c399a8b95ee40829847028c122746.nq.gz
│   ├── bf41de6c2acb48e2dc9452bb346c8c5e130320eb.nq.gz
│   ├── bfededaef8f4bd3c3f4aa17e15191f3970f4efbf.nq.gz
│   ├── c04813f1f272d004ebe43949da4981cc78731986.nq.gz
│   ├── c2146c655a93b842048269f3ed60112eddd200c9.nq.gz
│   ├── cbe4a81b5116a47622333ddb2dff040e6191aee0.nq.gz
│   ├── cd9a3af2ac786eca61244c810300ee3223a29eed.nq.gz
│   ├── d39e0fddc2b8c74006d83c044dc656ea4d098abd.nq.gz
│   ├── d3a94ec83adb77fbe0f1d256d1aa8aadc3b499b7.nq.gz
│   ├── d667e4768baae51365322fa58680b3a63b7b25bd.nq.gz
│   ├── d6cba003c9b23e794e23de32b12ce45d345611dd.nq.gz
│   ├── d6d164cddbbd60742788b0eb6c80381aa3af8ad4.nq.gz
│   ├── dcc2ea55cfeb3d45f69c8dea546faf9eb5744e0d.nq.gz
│   ├── de3fb9c608766a81f3d0f7639f971da118a82f75.nq.gz
│   ├── de505caa26b6d962d85c02d43234dfa5add6dd45.nq.gz
│   ├── e69cc8490682537ccb33c433b1010f1a9f5792e5.nq.gz
│   ├── eae592a6ee36bdf519f9d6384051c2fd7da380ee.nq.gz
│   ├── eb1fd8da159f45883c6cb580df9d75f6f0e9ae85.nq.gz
│   ├── eccd6d9fd25a0c14755871c5c1c9dc7190ac2528.nq.gz
│   ├── ee94db8bb77cc392a8bf247cfda5637c32b54b1a.nq.gz
│   ├── eed2569b884db889dd34fa444356e24a368ad8fc.nq.gz
│   ├── f009732d17734d92a57559febe14185187608729.nq.gz
│   ├── f0a8468df74bb46c0b3cb4b5e9b9c6c47b8bfef5.nq.gz
│   ├── f110a0b5b1abcf939510b06476872ff594624cd1.nq.gz
│   ├── f18a8ae017fec070ddff116da710073afde32e25.nq.gz
│   ├── f319731086140db6a45bc693e0c9260c3a783af4.nq.gz
│   ├── f76bdaee2d922029e5877b91ee4802558389d6bb.nq.gz
│   ├── f7c2455f7912137960df8e0940e8d8477b399b90.nq.gz
│   ├── f96a23bf0845a890ba6817b4c597efdc9356cf5d.nq.gz
│   ├── fb700c4203d09811ed0e29ea8cedfac5f6df408b.nq.gz
│   ├── fb8e382c97ff855069339703dc7e1239f11f9aa2.nq.gz
│   ├── fc7ff01a48f13ff816f65cfcf6f97beaa7faa076.nq.gz
│   └── ffb6202c5d2de654aa8e5d382fe2e89344d3f3f3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6a4f90f42dbc5412c39a138fb5b8e6a3cd489590.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 147 files
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

[litestar-org/branding](https://github.com/litestar-org/branding)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
