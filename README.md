# Repolex Knowledge Graph of scrapinghub/number-parser

RDF knowledge graph data for [scrapinghub/number-parser](https://github.com/scrapinghub/number-parser), parsed by [repolex](https://repolex.ai).

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
rlex download scrapinghub/number-parser
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a1263578628a7743054879095e50532fba1cdb67
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a1263578628a7743054879095e50532fba1cdb67
│           └── chunk-001.nq.gz
├── blob
│   ├── 0202b5646a16f7b594bd31e796c93a8d44192c09.nq.gz
│   ├── 023eb111e1b95f7b479e6b711151b37ab2e8f3be.nq.gz
│   ├── 0652d3fd3925ebd39cc9792da983e25ba8597c5b.nq.gz
│   ├── 068b9a66c9ffcf271fe9ccc2401ffad2299c9d5f.nq.gz
│   ├── 0bbb080a2b4c764fb10176a0d1a7c4c1e512812b.nq.gz
│   ├── 0e6bda830b5f6d2dddd36a4427484a30b37bee1f.nq.gz
│   ├── 0f6963a330ba57a79542bf267274caf4af2f16d7.nq.gz
│   ├── 105323a7c55d73465b68df55d7d235a58be54aff.nq.gz
│   ├── 139ea4e6d2a9af783c5385a8fba289053f250649.nq.gz
│   ├── 1741533638a9c793dfa3afffd5581d4e43235124.nq.gz
│   ├── 18417e03a8c8b3a4c20c6776435e1c83b79b5cf6.nq.gz
│   ├── 19af1d2bea2474d3c6615afb72ecf7ec51b6aee1.nq.gz
│   ├── 1c50032b11f664cd383c71419c72d40b1e3edf32.nq.gz
│   ├── 1ca92e42883de7724c66bc13230ef2276a3298fc.nq.gz
│   ├── 22936a6be935d0d5a38397e95e43c2914a4b6702.nq.gz
│   ├── 22c77aaa1703f08137defc4a250c1103df948343.nq.gz
│   ├── 22d4e13587510a9aa776ecfb67f6412fa921b3de.nq.gz
│   ├── 256bcd23013b1684376ea7b422cadfc4a7bacf4b.nq.gz
│   ├── 26d0c8bec8cb80bd527cd1a17819f26e0a688566.nq.gz
│   ├── 27aa4232b5161f6f1c7988da76e36cda8c511766.nq.gz
│   ├── 2843ca50efd6963863675f09e2d9eef5f86d41ff.nq.gz
│   ├── 2893acd337d5d7de368b0ee9053c65fffce3c0c6.nq.gz
│   ├── 2a5973f19df9d05397f195429cce0556cb110999.nq.gz
│   ├── 2a716cac15f8fee5ede832aed88aecc0ebbeba70.nq.gz
│   ├── 2b86145c8190d305e71e286a6b70269c7500542b.nq.gz
│   ├── 2d95b3e1b03802b22ae0de922ce69f6a56020598.nq.gz
│   ├── 2f02193e95e154ec343d1f2392ce5a741e78cf10.nq.gz
│   ├── 3160032818159ea158d7e2397c0de2049888b051.nq.gz
│   ├── 31c9a472e79858d5510ba13fa1527966927e4bb3.nq.gz
│   ├── 37557f51a01114eb9d691c90a31b5efcd27f590b.nq.gz
│   ├── 3a7d65d4c38ad16ecb0d660f8151a0431feb6515.nq.gz
│   ├── 3abd521a848af08953dd575c7cf41ca8aa4eac3a.nq.gz
│   ├── 3e5f7960d3200949b6e3cf6373b8d21fe0ba9aa4.nq.gz
│   ├── 43591ac4777cef911d8566e10b78c4213b1f81e0.nq.gz
│   ├── 44d07b8c6906155a1cd84ceef3ffa2d12900dc6e.nq.gz
│   ├── 44ef93778530b2f82b78e0e220fe43dd45f22501.nq.gz
│   ├── 4770ccd0b5f4d7ca3dd4556f9275ce32f68ccb66.nq.gz
│   ├── 47ea35feed20bbedd402172ec4afe4ddd882b481.nq.gz
│   ├── 4a2b8ea42190c5bfe80b1e1e6bc213aeacfe93b4.nq.gz
│   ├── 4af4d46075211936fdc306e07f3f14054b596f50.nq.gz
│   ├── 4b65f231071a3c5e3cfb91d1c1ea3faec794d611.nq.gz
│   ├── 4d4fae0fbb68cddc098cb1cae71160bab8dfa15c.nq.gz
│   ├── 4dc0085070a050cd5d7ea25568f515889cb23928.nq.gz
│   ├── 4e74b89c855924fd0326f12dbc2b7f77339ff609.nq.gz
│   ├── 549f951b6a9933b73bd26f47ff3eec840a9c8d72.nq.gz
│   ├── 58806c27e1ab127470ce448d4d4c3c0bc6a80b92.nq.gz
│   ├── 62bc411242d46ed9e4933a3850d8efc0e238ed9b.nq.gz
│   ├── 69b403cd242372ca113d84ff670eff1fac57b2fa.nq.gz
│   ├── 6a285160d8d0315bfa8106766f0fed20dd83f3b9.nq.gz
│   ├── 6b24bf0e12719955cefb48648e6e7e8b393a6d6a.nq.gz
│   ├── 6b2e82cf7b9a2bd3bbc96cf0a8184404d72a0dac.nq.gz
│   ├── 6b8d6cd61948ac00f81090ae1e31eb1afc92d3b4.nq.gz
│   ├── 6bef56ceac0ba139202b08faabe2d98fbc1f8918.nq.gz
│   ├── 6d233c95cdaf7b3dcc301733c9a60b3c09a6533b.nq.gz
│   ├── 6f42ef27c2aeda3d498fa982b2813b84c734e0f9.nq.gz
│   ├── 6f6e016cc18cea964c533477c19f3202c8dc606e.nq.gz
│   ├── 729fd837dd9310ac4a2830c92341ebd3f85671c9.nq.gz
│   ├── 739c0fce005fed0c199fe15792fed2c2bd8644b6.nq.gz
│   ├── 78f9e9e8b5b5c41e3406a4698a2c63d3638583a7.nq.gz
│   ├── 7996a4b441e18c470ebe1482cb162c798194fb17.nq.gz
│   ├── 7ceab60fa7cfb46e264841927cd619156216b707.nq.gz
│   ├── 7f495ed44371a6c4c0a4705e29cdb77b8997fde8.nq.gz
│   ├── 82b79da163b6efa87de8312241af1b2a71c07133.nq.gz
│   ├── 863a0ed948d54130ed04e973e33b778500219108.nq.gz
│   ├── 8785e352e4454ab14f897b0769295fca0f4b85e7.nq.gz
│   ├── 8878128624171b731427f27b6cdbfce6d47f56ff.nq.gz
│   ├── 8b75dff199b7c44e4ea1eb68664fe61536b71500.nq.gz
│   ├── 92d93bc96ed3073db7cfac51f0cd78f6a882e62b.nq.gz
│   ├── 937ea95a491f32138cf6bb11f2b6247213e71814.nq.gz
│   ├── 96f06241d3ef6dab01dcdbd71d66286997e11cba.nq.gz
│   ├── 972701bd0c6912e8a503cccff287a1cee0a58a1d.nq.gz
│   ├── 978171a0201b5d9b2d5b596ff6732ebf747705ae.nq.gz
│   ├── 980bb51cc9ba832345e71a481851f87b15a19d7b.nq.gz
│   ├── 9de3d4a8642a25f701a13cf06639af6bf2b68d3a.nq.gz
│   ├── 9f8e9a5e27e0bcd61235f48fdf7e669cc3a7afc4.nq.gz
│   ├── a5160c890915fe20e741895f7ba994087901cb2c.nq.gz
│   ├── a7e08178184cf17c0f21bf47b93e820cc68c11df.nq.gz
│   ├── a8d3b623c3be27f65d3eaf17a4c1c682fb398ff6.nq.gz
│   ├── aea12daf550c0439fe4d608a4c3a832f0eaa5897.nq.gz
│   ├── aee6eb7469b2bf6cfe62c1b65ff8e81b7376550c.nq.gz
│   ├── b3cd31b4eb3565c3b6fce08422300c8765004124.nq.gz
│   ├── b6b1c7f35d5ed1a1dd2e1482254cb199fe3b271e.nq.gz
│   ├── b86a71e733a8a7e9385cf98ca21330648b31a170.nq.gz
│   ├── bafd07419c25c963957910b6ccb069153123bb00.nq.gz
│   ├── c0a6c902f256b16d397c7e0d0ad2f014c81cf978.nq.gz
│   ├── c130bb5d02aaa6c49f4094750d0e6c98ae61a3d7.nq.gz
│   ├── c80f0932be4e15fd665f85daf4cc84270151b083.nq.gz
│   ├── cac3e428fdeb741f129f8195961d3dd208e13677.nq.gz
│   ├── cb9f0def2fac7128e144a01a7697dc8bff12331d.nq.gz
│   ├── cc699ae2ca39b3326d2d10047c12595d50ec7b14.nq.gz
│   ├── ccce0c9f290ec1661dec473f07cec40fdb7e0c45.nq.gz
│   ├── cfe3aa39d85e166059b8f1ecead603e3b4f472f0.nq.gz
│   ├── cffeec658252c4285de76fc69815697f4517bc62.nq.gz
│   ├── d15723fbe8de36b1c3ae302c77d8095459ea88e6.nq.gz
│   ├── d18dff6b29c3e394d17a50930f70f8f86ea8b618.nq.gz
│   ├── d8aa6b984fa2c4c4891f114100d205ad99801b34.nq.gz
│   ├── d9c33bd5eeda4583f270c98ef3eed4d564647ffc.nq.gz
│   ├── da9597cce62271460b74da0a9933454805f20c5a.nq.gz
│   ├── dade07668b5bc57bce454fb351602a333e0f9101.nq.gz
│   ├── dcc05d1b30a9aafdcb2676eef47ed038bcd5b75d.nq.gz
│   ├── dee583f4aa13077628063c1f7ac3d0c77b98cd7e.nq.gz
│   ├── df341a7d2a21826c53e4aa4caabe8873551e9ef7.nq.gz
│   ├── e1a529ee8003ff8f5f05ece5f1093bea8bd37452.nq.gz
│   ├── e55db7ec9b3c663a5a87931e22e31444af9e0447.nq.gz
│   ├── e599e8780cf5f6e0f006a93943474eb0cae97d92.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb603c7cf815a51c7eb1ee702fc28ec34bf7c520.nq.gz
│   ├── ec10a2676e0d338202e31d8fe4ca0655bfd2975a.nq.gz
│   ├── edd2697948b94f9d64d8baa5c4f450db25ef2e88.nq.gz
│   ├── f43682e74392d27f15ed5216565dbf0f904b404e.nq.gz
│   ├── f9046c1e320ca0be31423a66f4a556be2172ea49.nq.gz
│   ├── fefb5e72532ee98f6c092210f9f373ce7ecc3cce.nq.gz
│   └── ff2d26e99f1ec40e836554e9018f0d7266a63366.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a1263578628a7743054879095e50532fba1cdb67.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 121 files
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

[scrapinghub/number-parser](https://github.com/scrapinghub/number-parser)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
