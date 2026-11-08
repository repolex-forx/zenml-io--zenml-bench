# Repolex Knowledge Graph of zenml-io/zenml-bench

RDF knowledge graph data for [zenml-io/zenml-bench](https://github.com/zenml-io/zenml-bench), parsed by [repolex](https://repolex.ai).

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
rlex download zenml-io/zenml-bench
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3a5c89b2caa087c72aca0358325639a4abb3c823
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3a5c89b2caa087c72aca0358325639a4abb3c823
│           └── chunk-001.nq.gz
└── blob
    ├── 0048ff0a4856df36da0dfaa8b3aef9abb8086ff5.nq.gz
    ├── 0058874b4e4e907bcf434f75a4a395fbcff61c1d.nq.gz
    ├── 0186ee345d43bba7c9a6e7c0a8c8e8139b02169d.nq.gz
    ├── 01b245f0062cbb88f87e727d99ea6ce36a6fafee.nq.gz
    ├── 01fb0e509deff308dbeaa907459ba388de2040e9.nq.gz
    ├── 0336aa0102119cb05cd8a6af6a8a5f332800d04e.nq.gz
    ├── 03fc6a05dc5377fe9feeb0b29d76bec04d80b433.nq.gz
    ├── 04bba82f7720183f173c168dfa097556232ec365.nq.gz
    ├── 0513ff35f4588080cbd6f9acc0c8393183ecf22e.nq.gz
    ├── 0590f36b10b895d3b72be895b46d0dea55bea03e.nq.gz
    ├── 05a89fccb642a756c492648c7710a040dfac058f.nq.gz
    ├── 0646051c99f2bcefe03cfbc9db34c8d4fd8cc2f4.nq.gz
    ├── 06e7552a33b205bd3e81e45c5e0b615d9a9b7514.nq.gz
    ├── 0711ace12e98cd6d06256feffab3038bd3d84e50.nq.gz
    ├── 072f183abaa4b0d952fcc8ed20dc750d232ac9ab.nq.gz
    ├── 07b95a41469b60efc5ee6fd49ff5fab93e14b888.nq.gz
    ├── 07f4db1a48a6a321cd3890f673653ae69138bf7f.nq.gz
    ├── 088515b77545b8bf16d7508721dcdd7eeade9a48.nq.gz
    ├── 0893b002c88a6d90325d96258c5c65a98f8528ac.nq.gz
    ├── 096fa45171757e226b60b604a21d3d682614eb37.nq.gz
    ├── 09c9f0e196a2e95b191cae0e9b2af3f11c667ac3.nq.gz
    ├── 0a3ac1260648a7d52c8f6147127d6b1a4d49f50e.nq.gz
    ├── 0ae45cf812b92ee738dc93e05d008d3c1549f0f2.nq.gz
    ├── 0b6169d1de0f61243b765c78a06b46e98cb302c8.nq.gz
    ├── 0bf75ba034cbdd6dfb2376432c2574e6671ccd13.nq.gz
    ├── 0c7b8b2686ae0fbd725516867832ec67b6d28982.nq.gz
    ├── 0cca2da7e808162768402f406ba7aac2840149ee.nq.gz
    ├── 0d226f037d587eafbfa89863f2840254b5e5cd35.nq.gz
    ├── 0dda08a4405f4d6af710738d4894e6f61a9986ab.nq.gz
    ├── 0dfff385a9f6404e34f3e3f33f24f2d03ec9c89b.nq.gz
    ├── 0e215d0f7db46784920781dca0d261bf25939ca2.nq.gz
    ├── 0f4d5136a38b6f87042d83cd28a07ccccd8b0f23.nq.gz
    ├── 0f722c76147e267e0468804b0702ec3bd1eb8a48.nq.gz
    ├── 102f0bbd9b15124f07c885f4fedffeadbde5daab.nq.gz
    ├── 10607f31f57c8fdc521257a508cb2475e793a11a.nq.gz
    ├── 106c147b7d804c86015f28eeb186855e613e0247.nq.gz
    ├── 10d0210ca01840f011ae56cbb2c0d829e4e9416c.nq.gz
    ├── 10dfa0a385d5bd1341970647de1889d1b3b7617c.nq.gz
    ├── 11e0aee6d5a865ee868352901ce816046d89e151.nq.gz
    ├── 121a258a8886164da37db9e0c083d1d03bbba93c.nq.gz
    ├── 121a2ce1c9d7c0afc6e1f8663e039977d54c9533.nq.gz
    ├── 124e5607fb7f8c08b66e949124eee1eb57df11fe.nq.gz
    ├── 13b866f7083aa4397e659e2fcf74db3d33dc395c.nq.gz
    ├── 147eeeb40409f1c0ab09ab49696588b44e6c0327.nq.gz
    ├── 14b294fa0bb31a8799c7300fce4485fd256cb129.nq.gz
    ├── 151249d1948700fd3377805132ac417a0bfd9309.nq.gz
    ├── 1636494f08824c79c9a68a642f8697cb878389e2.nq.gz
    ├── 16ab834f849d270df6e6e6582d3c1047980df560.nq.gz
    ├── 16f1cf6a9f3d74f5984587694a123ba349a0fff2.nq.gz
    ├── 173fdfba22628d7fc73c3215db0aeb265d200604.nq.gz
    ├── 1760272d80962ae070d75b257395764e40668bb4.nq.gz
    ├── 17bcffb06c60404571e13803e0979fb046eb2fb3.nq.gz
    ├── 1817895ae4e8fbd72ab56073805887ebfbb5d57a.nq.gz
    ├── 181bba179622f5c01f19f47ce6f88d152d630abd.nq.gz
    ├── 18b41e305497bd887b11fc63b828f1385301043d.nq.gz
    ├── 1912afb3e2391a285cdf9995b54300225e8ac517.nq.gz
    ├── 1966c7202aa95ebc9fc0f114905f33e99709a162.nq.gz
    ├── 19775603853426babec282e3419149fcc6e12bc1.nq.gz
    ├── 198fb2946f75577b7dcc7b60dd4f1512be8625ae.nq.gz
    ├── 19f5c1d339e42ad76bf6b066e70d142f5d62ac8e.nq.gz
    ├── 1a41fbdcffc14f1b0fd8ff78ee6ddad4e7638990.nq.gz
    ├── 1a8777fc9eb24328339bf30f2c42347f468ac333.nq.gz
    ├── 1ab65d6eb71008f242852014cdae84ea7581eaab.nq.gz
    ├── 1aed0c7faba898261dfc7012499091b6a18fa2b0.nq.gz
    ├── 1afb4af8b759baaee5f63f8a0abcdb111ec16b83.nq.gz
    ├── 1b9867ba29416c4d37aebf66c5a94b1fe1bc2aea.nq.gz
    ├── 1c4058031a4cd723d09250cec726a0e3c37293e5.nq.gz
    ├── 1c4c89f90f1bfe5da42e78863abaff22785f7fd9.nq.gz
    ├── 1cee68569997280c98a57b88761dfc8c231b5306.nq.gz
    ├── 1d9b76c10fe7f8c5486ada90bca4102134a80e68.nq.gz
    ├── 1e5c7110e6c9c9e33365f883839b5b9eee10e046.nq.gz
    ├── 1e8eaf72f3b98a9a13c7e33896c3131b888ad97f.nq.gz
    ├── 1e9b295f8d8ae1b32410d289cb61ae7f9b8a8f39.nq.gz
    ├── 1fc40d87eabcf44a1844daeb1e23db1e440ebaf1.nq.gz
    ├── 205bb758b6921f8672d194d42b68f15afed2deb1.nq.gz
    ├── 219fbf8506748f38b186c7f99d00572c1252ace9.nq.gz
    ├── 22595a7d5087a75eed9fa9668035a7c5daa9e71a.nq.gz
    ├── 23e0ceb2c9edbbadffaec0b0eb6b99c29ada7f18.nq.gz
    ├── 24298e90b22010c5c8f4bc962ad5580ae2350853.nq.gz
    ├── 2484ea0f3f42d23df6ec62fc8ef1fdba960e536a.nq.gz
    ├── 2598c283326486cf14213e079ca45a386badb67e.nq.gz
    ├── 26338bc956c88f1fc56fe184dc4231d9b45bef7a.nq.gz
    ├── 26e6fe59e7bbfc48e43f34be20cf1f6d60fb3534.nq.gz
    ├── 27366e18141f909dd78c43dfebae75b3bf20d3bc.nq.gz
    ├── 27a7c8dd2f58abdc923777a3f820ad370c2e571c.nq.gz
    ├── 27badf38c878311f96016cb8c5b6b31f8e8eeee7.nq.gz
    ├── 2891124168a461f221eeaab5eab534cbfb6935f6.nq.gz
    ├── 28b68cd9d1dca991a8db70f18fa33bc2edc1cb71.nq.gz
    ├── 28fba05659ec9e6285bcb970e4ef7a7a5a461158.nq.gz
    ├── 2904ff1c35e3a45ff36445ef52a28a8b4dc3e1b7.nq.gz
    ├── 29722b26a957de21900b8806933f45ec524c607a.nq.gz
    ├── 29abd2fa1d32d6223baa64152a3df76dd3bf2c6d.nq.gz
    ├── 2bb870d072199752f059e29daad9c82424b8e06d.nq.gz
    ├── 2c314ae3dd0da44fc7c0c0995e77fd3ff02acdf4.nq.gz
    ├── 2c546df9292d5465a01f5b173a428429cc6d3b63.nq.gz
    ├── 2c9dd0c53c465080c6016f72178bc1c317ee2af7.nq.gz
    ├── 2d10b47ebaf1e2208145828968979eff3ce00ba9.nq.gz
    ├── 2df2e72373184b4872bb19dfd0b9e08d5b175388.nq.gz
    ├── 2e165d4b6ecede621067b015a3a54e0356a00f51.nq.gz
    ├── 2f23d1d661072600e2927d1ca3a96b6e4a4fbba3.nq.gz
    ├── 2fda232405c241686a984fd5524630be0f727ec0.nq.gz
    ├── 30241d8b21a89e2cf48054df4ebb957b8e93a9b6.nq.gz
    ├── 308b2aa1bbcfb06d949d9e1685b286caccf450c3.nq.gz
    ├── 30b8a73e6637dd9376c45a1914edfffcd53a173c.nq.gz
    ├── 31f29d4d6452c41e48b0a0d80aa6584eaf2c0990.nq.gz
    ├── 31f56a59c8b64fe0ee286651cf78f13c21c737c4.nq.gz
    ├── 33d0cc601b25b753cf74f35c25b716ac7151cf62.nq.gz
    ├── 34aa062c684e394be4f6b35a63a7bf5735be98f7.nq.gz
    ├── 34f4da767108a3fd6359a6ff3e32cdf924694d21.nq.gz
    ├── 353cd91b64f690eca213de8c68761c60de0f23c2.nq.gz
    ├── 35c14a1b6f3213e5899a2654177221cea9cabc65.nq.gz
    ├── 37157828d31aaf8fa60ab033bd377090f8863f72.nq.gz
    ├── 3779a0effd831f4a3f0e6133c38d3afd0c3b19fb.nq.gz
    ├── 37a94b806b8344182888c2b58e3f4757757486f9.nq.gz
    ├── 385a9c444ae5048f0d1e7abec351e631d915d10f.nq.gz
    ├── 38cc4ff0ee1a797e804ef69f9b9a5077e09b8aa9.nq.gz
    ├── 397d930d20725b3b1e67f6340bc8515ed8ded700.nq.gz
    ├── 39dbd1691e61967aafadf56e5aa0df2d22be20ae.nq.gz
    ├── 39fb768254bbd48ed6f550bacf07b4ab12c78cc8.nq.gz
    ├── 3a7d9c1513071df062169e2dc316559e086fd5c5.nq.gz
    ├── 3b104ce5aa128153ac6b7c4b18d22b3999ca6c97.nq.gz
    ├── 3c1cfd55107f5443bdc172aa0d6ed33ec217735b.nq.gz
    ├── 3cc29f7b68b0fa3e57b54a7a2a5020c63970bb50.nq.gz
    ├── 3d291288d06c8552ce3c6e7a337c174a9f1ebd64.nq.gz
    ├── 3d4ed50cbc9297c3520204da07b04f2d88794c8a.nq.gz
    ├── 3e76f7c89225dc56293446c1caf1721316bf04e9.nq.gz
    ├── 3ec802177b656087832cfd344858b67c4eb7f309.nq.gz
    ├── 3f25222c8dbb9977535ed6751525c7b7eeafd4db.nq.gz
    ├── 40ba290153c12ba3d2a6f85d74c934bc473d32a6.nq.gz
    ├── 40c81e55c6b60208a842fc34281ae8033ec0399b.nq.gz
    ├── 4115c6bb3d22b8c76b0e20557621ffc7d4f568a4.nq.gz
    ├── 41aeb6a15b3667c3abd45a49be044ab43dd9e5ff.nq.gz
    ├── 421205939c486a543d89b42ebd3321ca98c4aa42.nq.gz
    ├── 42133aaef57b31244184264e3592bf10a1f4e1d6.nq.gz
    ├── 426bfaa92c9d6e2faee0242836c1af9eddeadf68.nq.gz
    ├── 4476f86f4b112d05591b3c9c289cb7ee6a703048.nq.gz
    ├── 4481e5fa0e7592ef43cf2ec5a21dcd4dbb5b93af.nq.gz
    ├── 44ed8ef28dade393b89f7ff994a193fc4d01c3c5.nq.gz
    ├── 4575e0d13296555124592897c3724aa362efae1c.nq.gz
    ├── 46a07611f4186a275bda470537fe1b8fd5c2d765.nq.gz
    ├── 46a1538cd1683f3f75bb6a0893b6ef20590bd6c4.nq.gz
    ├── 473d4065cadf21a8c6615e516396e982a3b801dd.nq.gz
    ├── 474a0259054386e11848db52b0b8d30dcf97a45d.nq.gz
    ├── 478f352a691bf91dcc3e61436adc20148ae61ed2.nq.gz
    ├── 47f988c601805be4a6eeedf00b8384c5ca485b43.nq.gz
    ├── 4816377613cfb1a0512af9fe6ad1e72a444d0214.nq.gz
    ├── 4911dda256c535498de9c218b7102a8ce4dd7b9c.nq.gz
    ├── 4b2f96c288e86c6d7018f1d34571dae3d248e534.nq.gz
    ├── 4b8e50729f6d36cc98652f3783c9a6601bfb6e7c.nq.gz
    ├── 4bad313f4af8d7a2e1ec9b9a686fbdc8b99f5399.nq.gz
    ├── 4beb2551af8255e018b5a328d7dd5dcfaebd691d.nq.gz
    ├── 4c8610db5d4c2caf67be3c154eaae96fa6305902.nq.gz
    ├── 4d1c8360825c69e73afb81bd10f73b304d832273.nq.gz
    ├── 4d5b86132ba1fba2531ce75fda118133d7181050.nq.gz
    ├── 4dd6644f56cec3544df8e4babb951107e2efbbca.nq.gz
    ├── 4fad51b4ca7934180ce4c1e4822dd3ec5466ed71.nq.gz
    ├── 50a79ff4773a2a541d8c9337651a490458da0a69.nq.gz
    ├── 5243ef42d1538550a56d81e1677eb21f7401ba5d.nq.gz
    ├── 52c4b0b36c897c0645498aa60df7123b95435121.nq.gz
    ├── 53428d28d394ed175c1da9c5ec4ba0d3dc2eedbe.nq.gz
    ├── 53987b994caa3d13c4325685becfb28785ddcb73.nq.gz
    ├── 53cd079e78bc20e4c14f18a5701ca87412e5ba8e.nq.gz
    ├── 53f2d9e603bf9dbf92ce2a552ebf41e128ce2210.nq.gz
    ├── 53febd45702e0c542fff231774f8214429cf4208.nq.gz
    ├── 546b2324ad36bd6acd366c8ccc1657bc4373b960.nq.gz
    ├── 549d88695532661c61ee50f7bcfd80833ca5027b.nq.gz
    ├── 572ead727a9784e15dd2ff1f38b883da0a0b1a19.nq.gz
    ├── 578c4f30a3e43564607af05a801b49c604e8709b.nq.gz
    ├── 58978359eeecac01930e449ef89d53414e5b0a70.nq.gz
    ├── 590e95fef8ad9042c8f35d91d9dbc2bb7a503a15.nq.gz
    ├── 59d03c692b86d57d3aee447fccaff0e6d3814108.nq.gz
    ├── 5a615e1f25d326afcc45f503676a63e0e8d6e799.nq.gz
    ├── 5a6a9bad083e0e07797ea694f5bf033a71f2c0b9.nq.gz
    ├── 5a9e8e336066ca2c4e4c29b8e7ef8a8e3ccacd8a.nq.gz
    ├── 5ab8d2bc82358861c361957baf40a8ac7eca1288.nq.gz
    ├── 5b513c08e26932d82a6e61ba2054a7be6d2e3f70.nq.gz
    ├── 5b7e27c6ee63154712a92573d6488f0f52bd89ac.nq.gz
    ├── 5ba7ade8e56198e6e9adec1dcf493467a2c32ebe.nq.gz
    ├── 5c41eca2fb543451e927daf3d966936a138417cd.nq.gz
    ├── 5c53b02d48b9b001e8ef3c72db6376043ab539ed.nq.gz
    ├── 5e0f038754af3420d6455e5f6342b9636ddf704e.nq.gz
    ├── 5e12eafc7c9aaf29d3c4419a779427ad8b3eaf41.nq.gz
    ├── 5e2b692ae0eb5036c4dae28b7a0eae782f71a596.nq.gz
    ├── 5e8bfa376844ea3cb91b8ad3178ae83848e5747f.nq.gz
    ├── 5eec28b4c945a488b8b47d3e72f00584d4f2b694.nq.gz
    ├── 60173e515d9194dbe73d6c5e6b3e95931caf4e43.nq.gz
    ├── 60f71387cc7b53d87ddd2f2d5f4c1275f4b6f08f.nq.gz
    ├── 611d42cc8776c11a099db01d0208583d26b80e1a.nq.gz
    ├── 6335cadceb0248b2f5c6d7b97d867fb72d09ceb5.nq.gz
    ├── 63b8f939a438542df72a416282aa662e80ab97c1.nq.gz
    ├── 6425cb360bbe2eeafd6b6c6191218985d8624613.nq.gz
    ├── 64577a5421bcfc76e9a8693b35adec611c38959d.nq.gz
    ├── 64b4dc1ef451b8e6971ec65a4e8f6b6374dfbde2.nq.gz
    ├── 64de33ef071072684a1b085914b855993083752b.nq.gz
    ├── 655c0b8d35cc3499abcd25a8e347c995e30c9a85.nq.gz
    ├── 65b13e52bafe9f75d4d4a6b56d787728ef6440f3.nq.gz
    ├── 6705d2f982656b8cc40e86494f10b35135cc0497.nq.gz
    └── 670e1fb1b0f0f38b976648ea2c2b8cb4aca7b08a.nq.gz

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

[zenml-io/zenml-bench](https://github.com/zenml-io/zenml-bench)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
